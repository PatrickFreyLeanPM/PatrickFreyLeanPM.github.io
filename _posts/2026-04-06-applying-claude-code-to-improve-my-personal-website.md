---
layout: post
title: "Applying Claude Code to Improve My Personal Website — And Why the Results Surprised Me"
date: 2026-04-06 18:00:00 +0100
categories: product-management
excerpt_separator: <!-- excerpt -->
description: "How I used Claude Code as an AI coding assistant to analyze, improve, and redesign my personal website — including a full landing page built entirely by Claude Code."
image: /assets/CUBE_Method_Book.jpg
---

I love applying new technology in **real-world contexts**.

Not in toy examples. Not in isolated sandboxes. Not in "let me try this for 20 minutes and then stop." If I am going to evaluate whether a new tool is actually valuable, I need to use it on something that is live, that has real constraints, and where the result actually matters.

That is exactly what I did with [Claude Code](https://claude.ai/code) — Anthropic's AI coding assistant for the terminal. I applied it to improve my own personal website, the very site you are reading right now.

<!-- excerpt -->

## Why Real-World Application Matters to Me

This is a deeply personal conviction I have developed over the years as a product manager.

When I read about a new framework, method, or tool, my first instinct is not to study it further and read more and more. It is to **apply it as quickly as possible to something real**. The reason is simple: you only truly understand a tool's value — and its limitations — when you are using it under real conditions. Following a tutorial is very different from solving an actual problem with a deadline and actual stakes attached to the outcome.

It is why I read books and then immediately try to apply the concepts at work. It is why I built the [CUBE prioritization method]({{ '/cube/' | relative_url }}) while managing a real product backlog, not in a workshop exercise. And it is why, when I wanted to evaluate Claude Code, I did not invent a practice project. I applied it to a real portfolio site that I care about.

## What I Asked Claude Code to Do

My personal website has been evolving over several years. It has good content — blog posts, book summaries, concept explainers — but like most personal sites maintained alongside a full-time job, it had accumulated a fair amount of technical and UX debt. Things I always meant to fix but never found the time for.

So I gave Claude Code a clear starting point: **do a full analysis of the site, identify the most important issues, and help me work through them systematically.**

The result was a comprehensive portfolio analysis that covered everything from content architecture and navigation to SEO, accessibility, performance, and lead generation. A prioritized list of improvements with a clear rationale for each. Not a generic audit — a genuine, contextual assessment of *this* site with *these* goals.

Then we got to work.

## What Claude Code Achieved

Here is the full list of improvements that Claude Code helped me deliver, in roughly the order we tackled them:

**SEO & Discoverability**

- Generated a proper sitemap for search engines to crawl the site more effectively
- Added search engine crawl directives so Google and other search engines understand which content to prioritize
- Implemented **Open Graph meta tags** across all posts and pages so that when someone shares a link on LinkedIn, Twitter, or Facebook, they see a proper preview with the post title, description, and image

**Performance & User Experience**

- Optimized the CSS so the stylesheets load faster in the browser
- Added smooth page transitions when navigating between pages — the site now feels more polished
- Converted profile images to modern WebP format with automatic fallback to older JPG format, and added lazy loading throughout so images only load when the visitor scrolls to them

**Accessibility**

- Conducted a comprehensive **alt text audit** across all 36 images on the site — identified and fixed 3 specific issues where alt text was missing, incomplete, or contained formatting errors

**Full-Text Search**

- Implemented a **full-text search feature** that works entirely in the browser, without needing a backend server — you can now search across all blog posts, book summaries, concepts, and method pages
- The search field is embedded in the header navigation on desktop, with a dedicated search page for more detailed queries

**Content Structure**

- Prepared a system for connecting related content — so when you read a blog post, it surfaces the relevant book summaries and concept pages that expand on the same ideas

## The One That Genuinely Surprised Me: The CUBE Landing Page

All of the above were improvements I had in mind but never got around to. Claude Code helped me ship them quickly and correctly. That was not the surprising part.

The surprising part was the **CUBE landing page**.

The [CUBE method]({{ '/cube/' | relative_url }}) is a prioritization approach I developed over years of managing the EHANDBOOK product at ETAS. I have written an ebook about it, a presentation, and an AI-generated [podcast introduction via NotebookLM]({{ '/cube-podcast/' | relative_url }}). But all of this material was scattered — buried in teaser components across different pages, with no single entry point that was designed to actually convert a visitor into a lead.

The portfolio analysis identified this as a high-priority gap: *"Dedicated conversion page with testimonials, content preview, and optimized email capture."*

So I described the goal to Claude Code. I answered a few clarifying questions about the URL structure and how to handle missing testimonials. And then Claude Code **designed and built the entire landing page from scratch.**

I want to be specific about what "designed and built" means here:

- A **custom page layout** that enables full-width sections with the design flexibility needed for a conversion page
- **Responsive design** that looks good on mobile, tablet, and desktop, with the layout adapting intelligently to different screen sizes
- **Nine conversion-optimized sections**: a hero section with a clear headline and call-to-action buttons above the fold, a section highlighting the problem (backlog chaos, stakeholder conflicts), the method explained clearly, a content preview showing the ebook and presentation covers, a "Why CUBE vs ICE" comparison, an author credentials section with awards and certifications, testimonial cards (placeholder, ready for real quotes), a SoundCloud podcast embed, and a final call-to-action section
- Modern **image handling** with formats optimized for web performance, with automatic fallback for older browsers
- **Social sharing metadata** so when someone shares a link to this page, it shows a proper preview
- And finally: a link added to the original `/cube/` explainer page pointing visitors to the new landing page

The full page is at [/cube-landing/]({{ '/cube-landing/' | relative_url }}). Go have a look. It was created entirely by Claude Code in a single session — and the visual quality, the layout logic, and the overall coherence of the conversion flow is, in my honest opinion, genuinely good.

## What Made It Work: One-Shot Results

Going in, I expected the usual AI dynamic: a reasonable first draft, several rounds of feedback and iteration, and a final result somewhere around 80% of what I had envisioned. The kind of useful-but-incomplete output that requires significant human finishing work.

That is not what happened.

On the technical implementation — the SCSS, the Jekyll layout, the Liquid template code — I already expected solid results. Claude Code is a capable programmer.

What I did **not** expect was the quality of the **landing page design in one shot**: the structural logic of the conversion funnel, the copy decisions, which social proof elements to include and how to present them, the visual hierarchy across nine sections. This is not a trivial task even for an experienced designer or marketing copywriter. Claude Code produced a complete, coherent, deployable result in a single pass.

That is the delighter.

## My Role: Architect and Product Manager

I am not a developer. I understand code well enough to read it, debug it, and direct others — but I do not write production SCSS or Jekyll layout files from scratch. In this project, my role was exactly what I default to professionally: **Architect and Product Manager**.

I set the direction and defined the goals. I answered clarifying questions when Claude Code asked them. I reviewed the output and decided what to accept, adjust, or redirect. I made the judgment calls — which achievements to prioritize, what the landing page needed to accomplish, how to handle missing testimonials.

Claude Code handled the exploration, the planning, the implementation, and the verification. It read the existing codebase, understood the design patterns in use, and applied them consistently. It asked good questions before building — not just "what do you want?" but specific questions about the URL structure, the testimonial strategy, and the navigation approach, each of which affected real design decisions downstream.

This felt like working with a **capable junior developer who understood the codebase deeply and executed reliably** — combined with a **designer who could translate a content goal into a working layout without being told exactly how**.

One thing that helped me understand what was possible was spending time with [Claude Code's documentation](https://code.claude.com/docs/). Specifically, the **"Build with Claude Code"** section was invaluable — it explains the concept of **skills** (reusable prompts that Claude Code can execute) and **MCP** (Model Context Protocol, which lets Claude Code integrate with external tools and APIs). Reading through this gave me a much clearer mental model of what Claude Code could accomplish and how to direct it effectively.

## The Bigger Takeaway

Using Claude Code on this project changed how I think about the scope of work I am willing to take on.

When I started this site, certain improvements were simply off the table. Not because I did not want them, but because the execution cost — the hours of learning SCSS, the trial-and-error with Jekyll layouts, the research into SEO best practices — made them impractical for a side project. The tradeoff was not worth it.

That calculus is different now. When the execution barrier drops significantly, you naturally start scoping more ambitiously. The question shifts from *"can I afford to invest the time to build this?"* to *"what actually matters for this site?"*

That is a meaningful shift in mindset. And it is one that I think has implications well beyond personal website projects.

## If You Are a Product Manager Thinking About This

Try it on something real. Not a practice project, not a tutorial — something that is live, that you care about, and that has real constraints.

You will quickly find that the skill being tested is not your coding ability. It is your ability to **articulate a clear goal, provide useful context, and exercise judgment on the output**. In other words, exactly the skills you use every day as a product manager.

The tool rewards good product thinking. And in my experience, it delivers.

**One concrete recommendation:** Before diving in, spend some minutes reading [Claude Code's documentation](https://code.claude.com/docs/), specifically the **"Build with Claude Code"** section. Understanding concepts like **skills** (reusable, specialized prompts) and **MCP** (integrations with external tools) will help you think more clearly about what is possible. It will also help you communicate more effectively with Claude Code about what you want to accomplish. I found this very valuable when directing the improvements to my site.

---

*If you are interested in lean product management, prioritization, or value-based pricing, don't hesitate to get in touch ({% include get_in_touch.html %}).*
