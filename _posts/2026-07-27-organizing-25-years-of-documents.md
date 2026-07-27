---
layout: post
title: "Organizing 25 Years of Documents: Getting My House in Order"
date: 2026-07-27 06:00:00 +0100
categories: product-management
excerpt_separator: <!-- excerpt -->
description: "In this article, I describe how the challenge of messy file organization in my private household and how AI and a Claude Code skill I quickly developed helped me to better organize our documents."
image: 
---

## The Problem That Kept Growing    

Over the past 20 to 25 years, my family has accumulated an enormous amount of documents. Bank statements, tax records, insurance paperwork for cars and properties, medical files, utility bills—the usual chaos that accumulates when you're too busy living life to organize it.

A decade ago, we invested in a Synology NAS to solve the storage and archiving problem. Also: hard-disks fail, and the disaster of data loss is real. 

The NAS works great: documents are safe from hard drive failures, accessible from any device, and centrally backed up. Hardly anything to maintain (i.e., not a [Tamagotchi](https://en.wikipedia.org/wiki/Tamagotchi) that I have to take care of daily). Problem solved, right?

Not quite.

<!-- excerpt -->

The real challenge wasn't storage—it was *finding* anything. We had countless folders scattered across different naming conventions. Utility bills mixed with insurance documents. Multiple versions of the same file in different locations. Half-organized directories that sort of made sense six months ago but now? Good luck remembering where anything is.

## My Old Solution: The Script Band-Aid

Over the years, I'd tried to fix this with small scripts that would sort files into folder structures based on their names. It worked—for a while. I'd run a script, organize a section, feel satisfied. But it was always a one-time effort. A temporary fix to a recurring problem.

The real issue was that I kept accepting the chaos. Some new documents arrive, I throw them on the NAS in some directory I find meaningful, and move on. Multiply that by hundrets of documents over years, and you get what I had: semi-organized mess that worked just well enough not to force me to fix it properly.

## The Shift: Why AI Changed My Thinking

Two-and-a-half years ago, as I started working more intensively with AI—both professionally and personally—something clicked. I realized that **well-organized data isn't optional when you want to work effectively with AI. It's fundamental.**

Machine learning requires carefully curated datasets. Data science is essentially about bringing structure to chaos. When companies build AI systems, they invest heavily in data quality and organization first. The better organized your data, the better AI can help you use it.

At work, I experienced this firsthand. About six months ago, I took over as product manager for EHANDBOOK and inherited a Confluence space that had grown organically over years—useful, but scattered. I spent time reorganizing and restructuring our knowledge base. It wasn't glamorous work, but suddenly I could find and point out information faster. And now, when we work with AI to help us document and analyze our product, the structured knowledge is far more useful.

Insight: **If I want AI to help me manage my personal documents, I need to organize them first.**

## The Weekend Project

So I decided to tackle the problem properly. I used Claude Code to create a script that would analyze a folder structure and suggest a better organization system. I then turned the script into a skill such that I can apply it repetitively. 

When it comes to privacy, I didn't want to upload the contents of my documents to any public AI system. That felt wrong for private financial and medical records. Instead, I set a clear constraint in my CLAUDE.md file: **the AI can only work with file and folder names, plus metadata like creation dates. No document contents.**

This constraint turned out to be sufficient. You'd be surprised how much organization insight you can get from just filenames and folder structures. The AI can see patterns: "You have 15 files with 'Tax' in different folders. Here's a better way to organize them." That's useful.

As I worked with the initial script, I kept finding small improvements. The analysis output should go directly to my working directory. The skill should assume I'm working in the folder where I call it. Keep it simple. Don't accumulate unnecessary markdown files.

That evolved Python script became a Claude Code Skill. And I learned something important in that process: **Skills should be lean and focused. One thing, done well.**

## What I Learned

**1. Structure enables AI, not the other way around.**
Before you expect AI to help you organize or analyze documents, those documents need some baseline structure. AI can help *improve* organization, but it can't create organization from pure chaos (yet). Not effectively, anyway.

**2. Constraints clarify thinking.**
By saying "AI can only see filenames and metadata," I forced myself to think about whether that's actually enough. It is. Often, we add unnecessary complexity. The constraint made the solution simpler and more private.

**3. Even small improvements compound.**
I didn't need perfect organization from day one. The skill generates a report showing the current state and suggesting improvements. I apply some, learn, iterate. It's incremental, but it works.

**4. Lean solutions are better than comprehensive ones.**
My first instinct was to build something that could handle multiple scenarios, edge cases, different folder structures. But the most useful version was the one that did one thing well: analyze a folder and suggest a numbering system for the top level based on the content patterns it found.

## The Bigger Picture

Here's what struck me as I did this: **The problem I faced in my home office is the same problem many organizations face.**

Teams accumulate files, documents, and knowledge over time without a coherent strategy. Someone leaves, nobody knows where the important stuff is. You need information, but searching feels futile. You end up asking colleagues instead of finding it yourself.

Then you want to bring in AI—for documentation, for knowledge retrieval, for analysis—and suddenly you realize: the AI needs structure to be useful. You can't just dump everything into a large language model and hope for the best.

Whether it's your home file system or your company's knowledge base, the principle is the same: **good organization isn't just about tidiness. It's about future-proofing your data for the tools and AI systems you'll want to use.**

## What keeps me thinking

I'm curious how you handle this in your own context—private or professional:

- How do you organize documents and files where you work?
- Have you tried to make your file systems "AI-ready"? What does that look like for you?
- Are there tools or practices you've found that work better than starting from scratch each time?
- What's your biggest friction point when trying to keep things organized?

I'd love to hear what's worked (or what hasn't) in your experience. I suspect many of us are figuring out how to solve it as we begin integrating AI into our daily workflows.

---

*If you're curious about the technical side: I have shared the Claude Code Skill I built in the following repo: [Organize directory skill](https://github.com/PatrickFreyLeanPM/organize-directory). It might help you organize your own files, or you have improvement suggestions. Let me know.*   
