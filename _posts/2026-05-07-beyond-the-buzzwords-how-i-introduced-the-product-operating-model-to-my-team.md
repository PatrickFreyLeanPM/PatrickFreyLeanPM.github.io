---
layout: post
title: "Beyond the Buzzwords: How I Introduced the Product Operating Model to My Team"
date: 2026-05-07 20:00:00 +0100
categories: product-management
excerpt_separator: <!-- excerpt -->
description: "A real-world account of introducing Marty Cagan's Product Operating Model and Itamar Gilad's Lean Product Management Stack to a development team, moving from theory to practical application."
image: /assets/posts/GIST_Framework_Diagram.jpg
---


I'm convinced that to build great products and solutions, we need a great way of working. The methods proposed by pioneers like Marty Cagan and Itamar Gilad can massively increase our chances of success, but a blueprint is useless if it stays on paper.

My conviction is that to truly improve how we work, these powerful concepts must be applied to a real team, with a real product, facing real constraints. They can't be confined to a workshop or a theoretical exercise. The goal isn't just to talk about a better way of working; it's to actually *work* that way.

That is exactly what I did recently when I synthesized the Product Operating Model and the Lean Product Management Stack and presented them to my entire development team, kickstarting our journey to put these ideas into practice.

<!-- excerpt -->

## The Shared Reality Most Product Teams Face

This isn't about fixing something that's broken. It's about acknowledging a shared reality that many of us in product development experience. How often do we dedicate immense effort to building a feature, only for its impact to fall short? How often do we start working on topics before we've truly understood the problem we're trying to solve?

This is the classic "feature factory" trap. We get busy, we ship, but we don't necessarily make progress on the outcomes that matter. The cost is significant:

* **Wasted effort** building things that aren't used or don't unfold as desired.
* **Missed opportunities** to work on topics that could have delivered immense value.
* **The risk of building unnecessary things**, which is especially high with new technologies like Generative AI where the problem space is still emerging.

The ambition is to move from being a feature factory to becoming a true value creator. It's not about working harder, but *smarter*. And that requires a shift in our operating model.

## The Three Pillars of a Modern Product Operating Model

Based on Cagan's work, I introduced three core pillars that frame this new way of working.

### 1. Empowered Teams

This is the foundation. An empowered team isn't just handed a list of features to build. They are given a *problem to solve* and the autonomy to figure out the best solution. The key shift, as Cagan says, is moving beyond simply executing tasks to truly understanding the 'why' and owning the 'what' and 'how'.

### 2. Continuous Discovery

This is our engine for reducing uncertainty. It's the ongoing process of learning from our users and the market to ensure we're always working on the right problems and designing the right solutions. It's about moving from "let's build it and see" to "**let's experiment and learn quickly**." This involves user interviews, observing behavior, prototyping, and running small, fast experiments to validate our assumptions *before* we commit to building.

### 3. Dual-Track Approach

This is how we integrate learning and building. Discovery (figuring out *what* to build) and Delivery (actually building it) happen continuously and in parallel. The Discovery track feeds the Delivery track with validated ideas, ensuring our development effort is always focused on things that have a high probability of success.

## Making It Real: The Lean Product Management Stack

Talking about these pillars is one thing. Actually implementing them is another. This is where the practical tools from Itamar Gilad's Lean Product Management Stack become invaluable. I introduced three to the team as a starting point.

### The Idea Bank

This is a central, organized repository for *all* product ideas and opportunities. It's crucial to understand that an **Idea Bank is not a Product Backlog**. The backlog is for validated, prioritized work we've committed to. The Idea Bank is the messy, creative space where raw ideas land before they are properly understood, researched, and validated.

<img src="{{ '/assets/posts/Itamar_Gilad_Working_with_an_idea_bank.png' | relative_url }}" alt="Working withg an idea bank" loading="lazy">

### The GIST Framework

This is a powerful tool for structuring our thinking from goals to action.

* **Goals:** The high-level outcomes we want to achieve.
* **Ideas:** The potential solutions that *might* help us achieve those goals.
* **Steps:** The experiments we'll run to validate our ideas. This is the heart of Continuous Discovery.
* **Tasks:** The development work that follows a *validated* idea.

The 'Steps' phase is the critical link that is often missing. It forces us to de-risk our ideas before committing to expensive development cycles.

<img src="{{ '/assets/posts/Itamar_Gilad_GIST_board.png' | relative_url }}" alt="GIST board" loading="lazy">

### RICE Prioritization

Once we have a set of validated (or semi-validated) ideas, how do we choose what to work on? The RICE scoring model provides an objective framework:

* **Reach:** How many users will this impact?
* **Impact:** How much will it impact each user?
* **Confidence:** How confident are we in the idea, backed up by evidence? Here, the confidence meter is a valuable instrument.
* **Ease:** This captures the effort required to realize the idea, typically estimated in person-months or sprints. In the RICE formula, this number goes in the denominator, so ideas that are easier (require less effort) will get a higher score.

The simple formula `(Reach * Impact * Confidence) / Effort` gives us a score that helps us move away from "gut feeling" prioritization. It's worth noting that Itamar Gilad often promotes the simpler ICE scoring. I chose RICE because in our context, the notion of 'Reach' is important to capture how many users and customers are covered by an idea.

## The Bigger Takeaway: It's Hard, and That's Okay

Presenting these concepts led to one of the most fruitful discussions we've had as a team. The most important realization for everyone was this:

**Talking about being evidence-guided is one thing. Actually doing it is something different and much harder than you might expect.**

It requires a cultural shift. It requires product managers and product owners to be comfortable with uncertainty and to kill ideas that aren't validated, even if they love them. It requires developers and designers to participate in the discovery process, not just wait for specs. It requires everyone to be relentlessly curious and to constantly ask, *"How do we know this is the right thing to build?"*

My role in this is to be the architect and facilitator of this change. To provide the tools, champion the process, and create a safe environment for us to experiment and learn not just in our product, but in our way of working.

The journey is just beginning, but starting the conversation is the most important first step.

*If you are interested in lean product management, evidence-guided prioritization, or want to share your own experiences, don't hesitate to get in touch ({% include get_in_touch.html %}).*

*The illustrations for the Idea Bank process and [GIST framework](https://itamargilad.com/the-gist-board-and-other-gist-tools/){:target="_blank"} are based on the excellent work of Itamar Gilad.*