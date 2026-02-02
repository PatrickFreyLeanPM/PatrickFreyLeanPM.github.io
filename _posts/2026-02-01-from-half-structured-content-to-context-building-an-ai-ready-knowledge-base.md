---
layout: post
title: "From Half-Structured Content to Context: Building an AI-Ready Knowledge Base"
date: 2026-02-02 09:00:00 +0100
categories: product-management
excerpt_separator: <!-- excerpt -->
#permalink: documentation-ai-agents
---

In my [first post on LinkedIn this year](https://www.linkedin.com/posts/freypatrick_etas-ehandbook-productmanagement-activity-7412851566908575744-E969?utm_source=share&utm_medium=member_desktop&rcm=ACoAAAy3fMABdRHS-IHJ4YuMaaVL7OFYF5j2mx4){:target="_blank"}, I shared the goals I set for myself upon rejoining the **EHANDBOOK** team as a Product Manager. One specific objective stood out: *providing an improved internal team knowledge base structured to be AI-ready and easier to navigate.*

Today, I want to share the "why," the "how," and the insights I gained during this transformation.

<!-- excerpt -->

## The Challenge: Knowledge Debt

As ETAS EHANDBOOK has grown over the years, so has the team behind it. However, our internal knowledge base hadn't kept pace with this expansion, and the era of AI-driven productivity was fast approaching.

Upon my return, I noticed a few critical issues:

* **Information Decay:** Outdated content was mixed with new updates, making it hard to trust the source.
* **Discoverability:** Even as a "re-joinee" with prior context, I struggled to find specific information quickly.
* **AI Readiness:** This sparked a realization: if a human familiar with the product can't find the right information, how can we expect an AI assistant to retrieve relevant context?

This "knowledge debt" was the trigger for change.

## The Transformation Process

I didn't start with a 50-page master plan. Instead, I followed an iterative approach where every small change provided immediate value.

1. **Structural Foundation:** Defined a high-level taxonomy to categorize information logically.
2. **Content Refinement:** This involved reordering pages, introducing a logical numbering system, and crucially writing header sections designed for both humans and AI.
3. **Collaborative Ownership:** I involved subject matter experts to make this a collective team effort rather than a solo project.
4. **Continuous Iteration:** A knowledge base is a living organism. The goal is to "leave the campsite cleaner than you found it."

### Top-Level Structure

Finding a good top-level structure was especially challenging as many pages were previously unordered. With the support of AI to cluster existing topics and identify gaps, I established the following structure:

| Chapter | Chapter Title | Description | Owner |
| :--- | :--- | :--- | :--- |
| 01 | 🧠 Product & Strategy | Product direction and execution: vision, mission, strategy, metrics, and topic planning (OKRs/PIs). | PM |
| 02 | 🏗️ Architecture & Technology | Architecture documentation, design decisions, quality attributes, and technical debt. | Product Architect |
| 03 | 🎨 User Experience (UX) | UX project methodologies, research findings, and design system guidelines. | UX Lead |
| 04 | 👥 Team | Team roster, roles, responsibilities, and internal contact information. | Team Lead / PM |
| 05 | 📘 Process Handbook | Development and operational processes: ceremonies, deployment, and security standards. | Scrum Master / Ops |
| 06 | ✅ Quality & Testing | QA framework, test automation, system validation, and release strategies. | Testing Team |
| 07 | 📗 Developer's Guide | Technical onboarding, coding standards, and API documentation. | Architect & Dev Team |
| 08 | 📦 Release Preparations | Checklists and procedures required to finalize a new version release. | Release Manager |
| 09 | ⚙️ Release Build & Infra | Technical details on CI/CD pipelines and deployment infrastructure. | DevOps / Infra |
| 10 | 🎬 Demos | Recordings, slides, and summaries of internal and stakeholder demonstrations. | PM and Team |
| 11 | 🎯 Special Initiatives | Documentation for high-priority, time-bound strategic projects. | PM / Lead |
| 12 | 💰 Sales & 🛟 Support | Sales/Support topics: license management, troubleshooting, and customer info. | Sales & Support Lead |
| 13 | ➕ New Acquisitions | Tracking and documentation for ongoing acquisition projects and pilots. | PM |
| 14 | 📰 Weekly Customer News | Updates on customer developments to drive transparency and business growth. | PM |

### Structure of Product & Strategy Content

As a Product Manager, I am directly responsible for the 🧠 **Product & Strategy** section. Structuring this area was a priority.

I am a strong advocate for lean software product management. The frameworks of **Itamar Gilad** and **Marty Cagan** have significantly influenced my work. Specifically, Itamar’s evidence-based approach helped me define this subsection:

| Section | Section Title | Description | Owner |
| :--- | :--- | :--- | :--- |
| 00 | ℹ️ About | General overview of the solution, its purpose, and core value proposition. | PM |
| 01 | 👁️ Vision | The long-term aspirational future state of the solution. | PM |
| 02 | 🎯 Mission | The daily focus and purpose of the team to achieve the vision. | PM |
| 03 | 🗺️ Strategy | The high-level plan and choices made to achieve the mission and vision. | PM |
| 04 | ⭐ North Star Metrics | The primary metric capturing the core value delivered to customers. | PM |
| 05 | 🔝 Top KPI | The primary business-oriented performance indicator. | PM |
| 05 | 📈 Health Metrics | Secondary metrics monitoring product stability and growth performance. | Shared (PM/UX/Arch) |
| 06 | 🚀 Growth Loops | Models describing how the product acquires and retains users via self-reinforcing cycles. | PM |
| 07 | 🔭 Strategic Horizons | Analysis of future trends, market disruptions, and competitive threats. | PM |
| 08 | 📊 Market Analysis | Research on market trends, competitor landscapes, and industry shifts. | PM |
| 09 | 👤 Personas | Detailed profiles of our target users, their behaviors, and their needs. | PM / UX |
| 10 | 🧰 Jobs-to-be-done | Framework focusing on the specific tasks users are trying to accomplish. | PM / UX |
| 11 | 🔍 Discovery | Documentation of experiments, user interviews, and hypothesis testing. | PM / UX |
| 12 | 🗓️ Annual Planning | Tactical execution: Objectives and Key Results (OKRs) and PI planning. | PM |
| 13 | 🛣️ Roadmap | Visual representation of the product's evolution over time. | PM |

*Note: This is a re-start. While the structure is in place, we are still migrating and refining content to fully meet the standards of the framework.*

## Bridging the Gap: Human-Centric vs. AI-Ready

Many organizations (including Bosch/ETAS) are deploying AI platforms that connect internal knowledge to chat assistants. To make this work, your data structure matters.

While I have a personal favorite platform that connects our Confluence Space with an AI chat agent, the specific tool is secondary. The real value lies in the **content and its structure**. AI assistants may change, but well-organized, high-quality data will always be the prerequisite for success.

### Leveraging Atlassian Confluence

We use a Confluence Space as our "central source." During the process, I rediscovered several features essential for maintaining an AI-friendly space:

* **Page Reordering:** Using "Reorder Pages" in the Space Tools helped me drag-and-drop the hierarchy to visualize the "knowledge map."
* **Dynamic Page Trees:** I introduced page trees with search bars at the top of major chapters. This helps humans navigate while keeping related topics grouped for better AI indexing.
* **Improving Content Quality with AI and Markup:** LLMs are naturally strong at formatting text. To bridge the gap between an AI chat and Confluence, I heavily used the **"Insert Markup"** feature. This small hack proved to be a massive efficiency booster for cleaning up messy legacy pages.
* **Standardized Templates:** I created templates for recurring content like *Weekly Customer News*. This ensures consistency, making data extraction significantly easier for AI agents.

If you're a Confluence user: Here's how to get Markdown from LLM into Confluence page:

**Step 1:** Choose "Insert Markup" from the Confluence menu.

![Choose "Insert Markup" from Confluence menu]({{ '/assets/posts/confluence_insert_markup_step1.png' | relative_url }}.)

**Step 2:** Paste Markdown and insert.

![Paste Markdown and insert - Done]({{ '/assets/posts/confluence_insert_markup_step2.png' | relative_url }}.)

*Note: I could also have set up an agent that automates the transfer of content into the Confluence page. While this is possible, my focus was on getting the results and not on automation yet.*

## Results

So what are the results from all these efforts?

**For the Team:** The Confluence Space has moved from a "digital attic" to a structured library. The cognitive load required to navigate the space has dropped significantly.

**For the AI:** Our internal AI assistant is now significantly more reliable. Because the data is partitioned into logical chapters with clear owners and descriptions, the RAG (Retrieval-Augmented Generation) process fetches more relevant chunks.

**For Stakeholders:** Transparency has increased. Stakeholders can now find specific updates (like Chapter 14: Weekly Customer News) without being overwhelmed by the noise of technical developer guides.

The organization of the Confluence Space is now significantly more intuitive.

![EHANDBOOK Confluence Space]({{ '/assets/posts/ehandbook_confluence_space.png' | relative_url }}.)

The AI chat assistant provides answers rooted in content from our internal knowledge base.

![EHANDBOOK Confluence Space]({{ '/assets/posts/ai_chat_assistant_ehandbook_confluence_space.png' | relative_url }}.)

## Key Insights

* **Action over Perfection:** Starting the reorganization is more important than having the "perfect" final plan. The structure often reveals itself as you clean.
* **Shared Accountability:** Involving the team creates a sense of pride. For example, our Testing team now takes full ownership of the "Quality & Testing" section, ensuring it stays "small but mighty."
* **"Say what you do, and do what you say":** I often think of this motto from ETAS CEO [Thomas Irawan](https://www.linkedin.com/in/dr-thomas-c-irawan-%E4%BF%9E-%E7%A4%BD-%E8%A4%94-73a3152/){:target="_blank"}. By sharing this journey publicly, I’m holding myself accountable to the standards I’ve set for myself working on EHANDBOOK.

## What’s Next?

The heavy lifting is done, but the real work **discipline** begins now. Maintaining a high-quality knowledge base requires constant pruning. Fortunately, I now have an AI assistant helping me manage the Confluence space, making the maintenance much less daunting.

**For internal stakeholders:** I invite you to visit our revamped Confluence space. Explore the new structure, try the search, and let me know how we can make it even better. If you're interested in how to use an internal AI assistant with the contents, let me know and I will show you.

**For external readers:** I'd love to hear about your experience. Get in touch if you are interested in the process or want to exchange ideas on AI-ready documentation!
