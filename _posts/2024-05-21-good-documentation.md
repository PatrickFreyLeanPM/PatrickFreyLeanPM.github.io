---
layout: post
title: "Why Good Documentation Matters and How Diátaxis Makes It Better"
date: 2024-05-21 05:00:00 +0100
categories: product developmnent
excerpt_separator: <!-- excerpt -->
source: 
---

## Why Good Documentation Matters

Good documentation is crucial for the success of any software project. It ensures that users can effectively understand and utilize a product, reduces the need for extensive support, and helps maintain a high standard of quality. Despite its importance, many projects suffer from poor documentation, which can lead to frustration and inefficiency for both users and developers.

### Common Pains for Readers of Documentation

1. **Difficulty Finding Information**: Users often struggle to locate the specific information they need due to poor organization or unclear navigation.
2. **Lack of Clarity**: Documentation that is unclear or overly complex can confuse users, making it hard for them to understand how to use a product effectively.
3. **Inconsistency**: Inconsistent terminology, style, and format can lead to misunderstandings and a lack of trust in the documentation.
4. **Outdated Content**: Documentation that is not regularly updated can provide incorrect or irrelevant information, leading to further frustration.
5. **Incomplete Coverage**: Missing information or gaps in documentation can leave users without the guidance they need to fully utilize the product.

### Common Pains for Writers of Documentation

1. **Unclear Objectives**: Writers often struggle with understanding what type of documentation is needed and what the specific goals are for different user groups.
2. **Maintaining Consistency**: Ensuring a consistent style and format across various documents can be challenging, especially in large projects.
3. **Keeping Documentation Updated**: Regularly updating documentation to reflect changes in the product can be time-consuming and is often neglected.
4. **Balancing Detail and Brevity**: Finding the right balance between providing enough detail to be helpful and keeping documentation concise can be difficult.
5. **User Feedback**: Collecting and incorporating user feedback into documentation can be a daunting task, but it is crucial for maintaining its relevance and usefulness.

One effective approach to addressing these pains and achieving high-quality documentation is through the Diátaxis framework.


## Diátaxis: A Comprehensive Approach to Documentation

[Diátaxis](https://diataxis.fr/){:target="_blank"} is a structured methodology for creating and organizing documentation. This approach, derived from the Ancient Greek words διά (dia, meaning "across") and τάξις (taxis, meaning "arrangement"), emphasizes a holistic view of documentation that ensures clarity, usability, and maintainability. Created by [Daniel Procida](https://www.linkedin.com/in/danieleprocida/){:target="_blank"} during his work on the [Django project](https://www.djangoproject.com/){:target="_blank"}, a popular Python web framework, Diátaxis offers a user-centered focus beneficial to both writers and readers of documentation.

Diátaxis is also known under the name [Divio Documentation System](https://docs.divio.com/documentation-system/){:target="_blank"}. 
It was created and maintained by Daniel Procida when working at [Divio](https://www.divio.com/){:target="_blank"}, a company that provides cloud infrastructure management for web apps. 

What I personally and specifically value about the Diátaxis approach is **the user-centered focus on both the writers as well as the readers of documentation**. It thus fits very well to many other methods and techniques thatare user- and/or customer-centered.    

<!-- excerpt -->

## The Four Forms of Documentation

Diátaxis identifies four distinct user needs, each corresponding to a specific form of documentation. These are:

1. **Tutorials**: Tutorials are designed to introduce users to a topic or tool by guiding them through a series of steps to achieve a specific goal. They are narrative-driven and assume minimal prior knowledge, making them ideal for beginners.

2. **How-To Guides**: These guides provide step-by-step instructions for performing specific tasks. Unlike tutorials, how-to guides do not necessarily follow a narrative structure and are more focused on achieving particular outcomes. They are practical and often used by users who need to accomplish a specific task quickly.

3. **Technical Reference**: This form includes comprehensive, structured information about a subject, such as API documentation or command syntax. Technical references are detailed and precise, serving as an authoritative source for users who need to understand every aspect of a tool or system.

4. **Explanation**: Explanatory documentation delves into the concepts, principles, and reasoning behind a subject. It provides the theoretical background and context, helping users understand the "why" behind the "what" and "how." This form is essential for users who need to gain a deeper understanding of a topic.

![Diataxis]({{ '/assets/posts/diataxis.webp' | relative_url }})

## The Diátaxis Framework

The Diátaxis framework places these four forms of documentation in a systematic relationship, proposing that documentation should be organized around these structures. This approach solves three critical problems in documentation:

1. **Content (What to Write)**: Diátaxis helps documentation creators determine the appropriate content for each form of documentation, ensuring that all user needs are addressed comprehensively.

2. **Style (How to Write It)**: By defining clear purposes for each documentation type, Diátaxis guides writers in adopting the right style and tone. For instance, tutorials should be engaging and accessible, while technical references should be precise and exhaustive.

3. **Architecture (How to Organize It)**: Diátaxis provides a blueprint for organizing documentation, making it easy for users to find the information they need. This organization enhances usability and ensures that the documentation is coherent and logically structured.

## Benefits for Documentation Creators and Maintainers

Diátaxis is not only beneficial for documentation users but also for those who create and maintain documentation. Its lightweight and easy-to-grasp nature make it straightforward to implement without imposing strict constraints. Here are some key advantages:

- **Enhanced Quality**: Diátaxis brings an active principle of quality to documentation, encouraging creators to think critically about their work and how it serves user needs.
- **Efficiency**: By providing a clear framework, Diátaxis helps avoid redundancy and ensures that every piece of documentation serves a specific purpose.
- **Maintainability**: Documentation organized according to Diátaxis principles is easier to update and expand, as the systematic structure allows for straightforward modifications and additions.

<!--
## Conclusion

Diátaxis offers a comprehensive, user-centered approach to documentation that addresses the diverse needs of its users. By clearly delineating the purposes and styles of tutorials, how-to guides, technical references, and explanations, it creates a cohesive and effective documentation system. This methodology not only enhances the user experience but also supports documentation creators and maintainers in producing high-quality, well-organized content. Embracing Diátaxis can transform documentation from a necessary chore into a strategic asset, providing significant value to both users and creators.

-->


## History and Creation of Diátaxis

Diátaxis was created by [Daniele Procida](https://www.linkedin.com/in/danieleprocida/){:target="_blank"}, a developer and documentation expert, as part of his work on improving documentation practices. The concept and framework were formalized and introduced around 2020-2021. Procida's experience with the Django project, where he contributed significantly to its documentation, informed the development of Diátaxis.

The creation of Diátaxis was driven by the need to address common issues in software documentation, such as unclear purposes, inconsistent styles, and disorganized content. Procida aimed to create a systematic approach that would be easy for documentation creators to adopt and that would effectively serve the diverse needs of documentation users.

The Diátaxis framework emerged from the recognition that different types of documentation serve different purposes and that these purposes should guide both the content and the organization of documentation. By categorizing documentation into tutorials, how-to guides, technical reference, and explanation, Procida provided a clear structure that could be applied universally to improve the quality and usability of documentation.

To disseminate the Diátaxis framework, Procida published articles, gave talks, and provided resources on platforms like GitHub, where he detailed the principles and applications of the framework. This made Diátaxis accessible to a broad audience and facilitated its adoption by various projects and organizations.


## Example documenations using Diátaxis

There are numerous projects that have successfully applied the Diátaxis framework:

* [django CMS, a modern web publishing platform built with Django](https://docs.django-cms.org/en/latest/){:target="_blank"}
* [Gatsby, a React-based open source framework for creating websites](https://www.gatsbyjs.com/docs){:target="_blank"}
* [Cloudflare](https://developers.cloudflare.com/){:target="_blank"}

## Getting started with Diátaxis

Both the websites of [Diátaxis](https://diataxis.fr/){:target="_blank"} and the [Divio](https://docs.divio.com/documentation-system/){:target="_blank"} Documentation System are good sources with information about the system. 
Nevertheless, I recommend the [Diátaxis](https://diataxis.fr/){:target="_blank"} as it is maintained by the original mastermind behind the framework, [Daniele Procida](https://www.linkedin.com/in/danieleprocida/){:target="_blank"}. 
Also, it provides more information on backgrounds and is 

I recommend to read the [theory behind Diátaxos](https://diataxis.fr/theory/){:target="_blank"} to understand the principles of writing good documentation. 
For docs-as-code approaches, I recommend to read the article on [structuring documenation contents](https://diataxis.fr/complex-hierarchies/){:target="_blank"}.

Daniele Procida has also been speaking publicly about Diátaxis / Divio documentation system. Here are two videos I can recommend to watch:

<iframe width="560" height="315" src="https://www.youtube.com/embed/qC1OYK5oqDo?si=GzH88W3G19DblD2T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/t4vKPhjcMZg?si=DPL1t20--fmr6Riv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## Own experiences with Diátaxis / Divio

During my time as product manager for the [ETAS EHANDBOOK solution](http://www.etas.com/ehandbook){:target="_blank"}, our earlier documentation was primarily based on PDF documents as well as an online help system that were shipped with the products. Although most topics were covered content-wise, many users as well as internal colleagues still consulted us for rather easy questions. 

The insights from user research revealed that the knowledge we provided as documentation was both hard to discover and difficult to use. 

We then decided to switch from PDF-based documentation to a modern web-based, online documenation. 
While for writing and generating documenation, we rather quickly decided for a docs-as-code approach[^1], a still remaining key question was how to arrange and organize the documentation contents.

This was when I discovered the Diátaxis framework / Divio documentation system. We decided to give it a try and rework our documentation contents. It worked really well, and we received very positive user feedbacks on the new documentation. 

Check out the [EHANDBOOK Docs & Tutorials](https://ehandbook.etas.com/docs/ehandbook/container_build.html){:target="_blank"} to get a glimpse.

![EHANDBOOK Docs & Tutorials]({{ '/assets/posts/ehandbook_docs_diataxis.jpg' | relative_url }})

## Get in Touch

I have extensive experience in creating software documentation using docs-as-code approaches, including:

- [AsciiDoc](https://asciidoc.org/){:target="_blank"} and [Antora](https://antora.org/){:target="_blank"}
- [RestructuredText](https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html){:target="_blank"} and [Sphinx](https://www.sphinx-doc.org/){:target="_blank"}
- [Markdown](https://www.markdownguide.org/){:target="_blank"} and [MkDocs](https://www.mkdocs.org/){:target="_blank"}

Feel free to reach out and drop me an email for an exchange.

<br/>
<br/>
<br/>
<hr/>



[^1]: For docs-as-code, we decided for [Antora](https://antora.org/) with [AsciiDoc](https://asciidoc.org/).