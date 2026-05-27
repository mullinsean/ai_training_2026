# AI Adoption Training — Spring 2026

Welcome! This repository hosts materials for a Spring 2026 hands-on workshop series on AI adoption for Canadian non-profits. The program builds practical skills for using Large Language Models (LLMs) and related AI tools across writing, analysis, operations, research, and advanced applications.

Materials — slide decks, examples, and resources — will be added to this repo as each workshop is delivered.

---

## 📚 Program Overview

The training consists of **five hands-on workshops** totaling roughly eight hours, progressing from foundational AI literacy to advanced applications:

1. **Workshop 1** — Introduction to LLMs & Context Engineering *(2 hours)*
2. **Workshop 2** — AI for Writing, Communications & Presentations *(90 minutes)*
3. **Workshop 3** — AI for Analysis & Operations *(90 minutes)*
4. **Workshop 4** — AI for Research *(90 minutes)*
5. **Workshop 5** — Advanced AI — Coding Tools, Models & Agents *(90 minutes)*

**Recommendation:** Join Workshop 1 first to build foundational knowledge, then select additional workshops based on your interests and work needs.

---

## 📅 Workshop Schedule

Each workshop is offered twice — attend whichever session works best for your schedule. All times Eastern.

| # | Workshop | Duration | Session A | Session B | Session C |
|---|----------|----------|-----------|-----------|-----------|
| 1 | Introduction to LLMs & Context Engineering | 2 hrs | Tue, Apr 28 · 11:00 AM – 1:00 PM | Thu, Apr 30 · 1:00 PM – 3:00 PM | Mon, May 4 · 10:00 AM – 12:00 PM |
| 2 | AI for Writing, Communications & Presentations | 90 min | Tue, May 5 · 11:00 AM – 12:30 PM | Fri, May 15 · 1:30 PM – 3:00 PM | — |
| 3 | AI for Analysis & Operations | 90 min | Tue, May 19 · 11:00 AM – 12:30 PM | Thu, May 21 · 1:30 PM – 3:00 PM | — |
| 4 | AI for Research | 90 min | Wed, May 27 · 1:30 PM – 3:00 PM | Tue, Jun 2 · 11:00 AM – 12:30 PM | — |
| 5 | Advanced AI — Coding Tools, Models & Agents | 90 min | Tue, Jun 16 · 11:00 AM – 12:30 PM | Thu, Jun 18 · 1:30 PM – 3:00 PM | — |

**Delivery:** All sessions will run via Microsoft Teams. Meeting links will be shared by email closer to each session date.

---

## 🧭 Workshop Descriptions

### Workshop 1 — Introduction to LLMs & Context Engineering *(2 hrs)*
A foundational deep dive into Large Language Models: how they work, where they excel, and where they fall short. We'll establish team norms for effective and responsible AI use — including data privacy, security, and safe input practices — and spend most of the session in a hands-on lab on **context engineering**: structuring prompts with clear instructions, relevant context, useful examples, and appropriate constraints to get reliable, high-quality outputs.

**Materials**
- [Slide deck](./slide_decks/AI%20Training%20-%20Workshop%20%231%20-%20Spring%202026.pdf)

**Examples**

| # | Description | Model | Supporting Files |
|---|-------------|-------|------------------|
| 1 | [Knowledge cutoff date](https://chatgpt.com/share/69f0ec45-44c4-83ea-b50e-77d583da4833) | ChatGPT | |
| 2 | [Model knowledge and tool use](https://chatgpt.com/share/69f0ec11-9884-83ea-b887-6a6baa8d4194) | ChatGPT | |
| 3 | [Summarize a podcast (simple)](https://claude.ai/share/0d79f0d2-09cf-4b86-a29b-eb6b3bb9eb5c) | Claude | [podcast transcript](https://api.omny.fm/orgs/e73c998e-6e60-432f-8610-ae210140c5b1/clips/2ff3db06-a25b-4d7b-9de9-b42f01476d14/transcript?format=TextWithTimestamps&t=1776455746) |
| 4 | [Generating a prompt](https://claude.ai/share/f318a4d8-844c-4761-8459-d40f1e6c1b98) | Claude | |
| 5 | [Summarize a podcast (enhanced)](https://claude.ai/share/f54b968a-2952-48fd-9ad4-7ceb91a1e668) | Claude | [podcast transcript](https://api.omny.fm/orgs/e73c998e-6e60-432f-8610-ae210140c5b1/clips/2ff3db06-a25b-4d7b-9de9-b42f01476d14/transcript?format=TextWithTimestamps&t=1776455746) |
| 6 | [Modifying an existing proposal](https://gemini.google.com/share/c325f66dc580) | Gemini | [Backyard Fusion project proposal](./examples/workshop1/Project%20Backyard%20Fusion%20-%20Project%20Proposal.pdf) |

**Additional Resources**

*Andrej Karpathy*
- ["How I use LLMs"](https://www.youtube.com/watch?v=EWvNQjAaOHw)
- ["Intro to Large Language Models"](https://www.youtube.com/watch?v=zjkBMFhNj_g)

*Prompting Guides*
- [OpenAI – GPT-5.5 Prompting Guide](https://developers.openai.com/api/docs/guides/prompt-guidance)
- [OpenAI – Using GPT-5.5](https://developers.openai.com/api/docs/guides/latest-model)
- [Anthropic – Claude Prompting Best Practices](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/claude-prompting-best-practices)
- [Google – Gemini 3 Prompting Guide](https://docs.cloud.google.com/vertex-ai/generative-ai/docs/start/gemini-3-prompting-guide)

*Learning Academies*
- [Anthropic Academy](https://anthropic.skilljar.com/)
- [OpenAI Academy](https://academy.openai.com/)

---

### Workshop 2 — AI for Writing, Communications & Presentations *(90 min)*
Using AI to accelerate writing, analysis, and communications work. We break the writing process into stages — background materials, rough outline, annotated outline, draft, and final document — and apply human review at each stage so the LLM speeds up the drudge work without flattening the analysis. Then we extend the resulting memo into other formats (blog post, social posts, long-form article, slide deck) using style guides, templates, and Claude Skills / Custom GPTs to keep tone and structure consistent. We also touch on brainstorming, verification and stress-testing of arguments, and structured data extraction from long documents — and note how style guides double as translation guides (e.g., English → French Canadian).

**Materials**
- [Slide deck](./slide_decks/AI%20Training%20-%20Workshop%20%232%20-%20Spring%202026.pdf)

**Examples**

#### Writing a Synthesis Memo (Budget 2025 example)

| # | Process Step | Activity | Example |
|---|--------------|----------|---------|
| 1 | Prepare Background Materials | Extract key elements of Budget 2025<br>Conduct media + stakeholder scan | Budget 2025 initiatives: [chat](https://claude.ai/share/a9453aec-79e1-4bb8-a244-c7c9dff052d5), [output](https://claude.ai/public/artifacts/b2f15ad5-0fda-49fb-a3b1-cf918f0aaef8)<br>Media/stakeholder scan: [chat](https://gemini.google.com/share/1f9039ad51ca), [output](https://docs.google.com/document/d/1cPRbp3oeI-QTctMVzrjaasX6Az3CGWKUwMKHyjc17uw/edit?usp=sharing) |
| 2 | Generate a rough outline of memo | Review and iterate | Rough outline: [chat](https://claude.ai/share/1c2abd44-bf7a-4b6b-a852-814375e45908), [output](https://claude.ai/public/artifacts/7da4c5b3-e6fe-4de9-8c1d-65d85cd75768) |
| 3 | Generate an annotated outline of memo | Include data sources, references | Annotated outline: [chat](https://claude.ai/share/c79954a6-a6a5-49f0-95ec-37a103fc441e), [output](https://claude.ai/public/artifacts/dfaacde5-8067-404f-907b-16cf0040bf05) |
| 4 | Generate rough draft of memo | Optional: Apply a template and/or style guide<br>Review and iterate | Rough draft:<br>• Claude: [chat](https://claude.ai/share/307b6b0f-2a05-4de8-9b19-a036d997b454), [output](https://claude.ai/public/artifacts/a86d4ab2-598d-4236-b77f-f61c89aeff7b)<br>• ChatGPT: [chat](https://chatgpt.com/share/69f9efae-5b08-83ea-aafb-047832683201), [output](https://chatgpt.com/canvas/shared/69f9efe1b1208191860fcf4c25ec2787)<br>• Gemini: [chat](https://gemini.google.com/share/ea1485e7a57e), [output](https://gemini.google.com/share/78f1301e3fe4) |
| 5 | Generate final draft of memo | Review, proof-read and iterate | Do this in a word processor! |

#### Generating Additional Documents (Extending the memo)

| # | Document Type | Concept | Example |
|---|---------------|---------|---------|
| 1 | Blog Post | Applying a style guide | Creating a style guide: [chat](https://chatgpt.com/share/69f9f088-0470-83ea-afa6-98ad60feadd8), [output](https://chatgpt.com/canvas/shared/69f9f21cc7948191a360dd60903bffe1)<br>Blog post: [chat](https://claude.ai/share/9b6d32dc-ca47-41e3-ab73-27ffecd95735), [output](https://claude.ai/public/artifacts/2cb1a7e6-547a-4630-af2a-eb39ec5324a9) |
| 2 | Social Media Posts | Using examples | Social media posts: [chat](https://chatgpt.com/share/69f9f90b-a970-83ea-a064-d186331ee8e1) |
| 3 | Article for The Economist | Using a Claude Skill to apply a style guide | Creating Claude Skill: [chat](https://claude.ai/share/01171078-5c5f-4c65-bb76-0b690cbf6423), [output](https://claude.ai/public/artifacts/ac89f54e-e0f5-4f4a-9a2e-9f0262831298)<br>Writing article: [chat](https://claude.ai/share/834d8074-ff5b-4b82-8ea6-ad86e0e49d53), [output](https://claude.ai/public/artifacts/089ad074-850b-4827-b7be-3f6454d3a20b) |
| 4 | Slide deck | Experimental: testing the [perplexity.ai](https://www.perplexity.ai/) slide deck feature | Slide deck: [chat](https://www.perplexity.ai/search/3dc12b68-e48d-4110-8de4-d4bdd823874d?preview=1) |

**Additional Resources**

- [Claude Use Cases](https://claude.com/resources/use-cases)
- [ChatGPT for Government: Prompt-Pack for Leaders (OpenAI Academy)](https://academy.openai.com/home/blogs/government-prompt-pack-for-leaders)
- [Using Generative AI — University of Waterloo Writing Centre](https://uwaterloo.ca/writing-and-communication-centre/Resources-AI-Overview)
- [Guide on the Use of Generative AI — Government of Canada](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/responsible-use-ai/guide-use-generative-ai.html)

---

### Workshop 3 — AI for Analysis & Operations *(90 min)*
AI-driven approaches to internal operations and quantitative work. We start with project management workflows — using LLMs across the meeting cycle to generate agendas, transcripts, summaries, and status updates. Next we look at how to connect AI tools to your data (direct uploads, project files, shared drives, and MCP connectors), including how Retrieval Augmented Generation (RAG) works behind the scenes. We then turn to hands-on quantitative work: exploring datasets, building models, and generating insights in Excel. We close with creating presentations from source documents and a set of productivity techniques — image generation, scheduling recurring queries, and using AI for brainstorming and rapid prototyping.

**Materials**
- [Slide deck](./slide_decks/AI%20Training%20-%20Workshop%20%233%20-%20Spring%202026.pdf)

**Examples**

#### Project Management

- [Project Overview Example: "Beyond Zero"](./examples/workshop3/Project%20Overview%20Example%20%28Beyond%20Zero%29.pdf) — sample project overview document used to provide context across the project management cycle

#### Data & Quantitative Analysis with Excel

A fuel consumption ratings analysis using [NRCan open data](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64):

| # | Process Step | Activity | Example |
|---|--------------|----------|---------|
| 1 | Explore Data Set | Generate a table of average fuel efficiency by manufacturer | Claude: [chat](https://claude.ai/share/372ef98d-d2de-41b0-9b4b-0777eea61653), [output (.md)](https://claude.ai/public/artifacts/9f77c1a6-543c-4ac1-9943-bfe1871c1152)<br>ChatGPT: [chat](https://chatgpt.com/share/6a0bc333-51e8-83ea-9d77-d72356485f24), [output (.xlsx)](./examples/workshop3/2025_canada_fuel_efficiency_by_manufacturer%20-%20chatgpt.xlsx) |
| 2 | Build a Model in Excel | Build a model that calculates the value of fuel efficiency savings between two vehicles | Claude: [chat](https://claude.ai/share/372ef98d-d2de-41b0-9b4b-0777eea61653), [output (.xlsx)](./examples/workshop3/hybrid-breakeven-model%20-%20claude.xlsx)<br>ChatGPT: [chat](https://chatgpt.com/share/6a0bc333-51e8-83ea-9d77-d72356485f24), [output (.xlsx)](./examples/workshop3/hybrid_vehicle_breakeven_model%20-%20chatgpt.xlsx)<br>Gemini: [output (.xlsx)](./examples/workshop3/Break_Even_Calculator%20-%20gemini.xlsx) |
| 3 | Investigate Trends & Answer Detailed Questions | Which vehicles showed the biggest fuel efficiency increase over 2014–2025? What was the average increase from introducing a hybrid model? | [chat](https://claude.ai/share/528f80e9-6881-4227-9926-a759f711cce9), [output (.xlsx)](./examples/workshop3/canada_fuel_economy_change_2015-2025.xlsx) |
| 4 | Generating Insights from Data | Ask the model to generate insights from the data | [chat](https://claude.ai/share/528f80e9-6881-4227-9926-a759f711cce9), [output (.md)](https://claude.ai/public/artifacts/682b58c6-13f0-43d0-9059-b0455338d9d2) |

#### Creating a PowerPoint Presentation

Building a presentation from a source document — a House of Commons committee report on Canada's Defence Industrial Strategy:

| # | Process Step | Activity | Example |
|---|--------------|----------|---------|
| 1 | Generate Outline | Generate a rough outline, then a more detailed outline, from the original report | [chat](https://claude.ai/share/289f56fe-6024-49a1-a415-ef8ed594897f), [output (.md)](https://claude.ai/public/artifacts/84afed48-3985-4754-bda2-ddea8fd0d9f2) |
| 2 | Generate the Presentation | Generate a draft presentation using the outline | Claude: [chat](https://claude.ai/share/15fd24b7-a019-4fc0-be7d-fa2a1415d073), [output (.pptx)](./examples/workshop3/Canada_DIS_Report_Presentation%20-%20Claude.pptx)<br>ChatGPT: [chat](https://chatgpt.com/share/6a0c53bd-1a80-83ea-9587-4571131d28d4), [output (.pptx)](./examples/workshop3/DIS_report_overview_draft%20-%20ChatGPT.pptx)<br>Gemini: [chat](https://gemini.google.com/share/06f93314be95), [output](https://gemini.google.com/share/e60a3b8bb50b) |

---

### Workshop 4 — AI for Research *(90 min)*
Techniques for more efficient research and synthesis. We'll cover finding and extracting information with LLMs, using Deep Research features for complex topics, summarizing diverse media (academic papers, reports, video), in-depth policy document analysis, stakeholder mapping, and integrating AI with research tools like NotebookLM and Zotero.

**Materials**
- [Slide deck](./slide_decks/AI%20Training%20-%20Workshop%20%234%20-%20Spring%202026.pdf)

**Examples**

#### Deep Research

| # | Description | Model | Output |
|---|-------------|-------|--------|
| 1 | Geopolitical situation in South Korea | ChatGPT | [pdf](./examples/workshop4/Recent%20Political%20and%20Geopolitical%20Developments%20in%20South%20Korea%20%282022%E2%80%932025%29.pdf) |
| 2 | [History of Bill C-27 (Digital Charter Act)](https://gemini.google.com/share/a07a94650ae7) | Gemini | [pdf](./examples/workshop4/Bill%20C-27%20Hansard%20Review.pdf) |
| 3 | [Media & Stakeholder Reception to Budget 2025](https://gemini.google.com/share/1f9039ad51ca) | Gemini | [pdf](./examples/workshop4/Budget%202025%20Climate%20Policy%20Scan.pdf) |
| 4 | [Analysis of Canada's Critical Minerals Sector](https://www.perplexity.ai/search/510af542-fb98-4a22-b2ce-264d733663c7?preview=1) | Perplexity.ai | [output](https://www.perplexity.ai/computer/a/5c01fcba-6254-4012-b2d2-ac66dd86cf4c) |

#### Research Tools & Advanced Techniques

- [NotebookLM example](https://notebooklm.google.com/notebook/ea1a2092-36a8-47ee-9727-dfb48baa4293) — using NotebookLM for multi-document research synthesis
- [Advanced techniques](https://gemini.google.com/share/3b05ae3a781f) — comparison matrix, red teaming, and gap analysis with Gemini

---

### Workshop 5 — Advanced AI — Coding Tools, Models & Agents *(90 min)*
A preview of the frontier: using AI to write and debug code for automating analysis (Python, R), and an introduction to **AI agents** — systems that perform multi-step tasks with tools. We'll look at the three levels of coding with LLMs (chat-window "vibe coding," IDE integration, and full agentic coding with tools like Claude Code) and close with an interactive session to identify AI applications each participant can explore over the following month.

*Materials: coming soon.*

---

## 📧 Contact

**Instructor:** Sean Mullin
**Email:** sean.mullin@gmail.com
**Website:** [www.seanmullin.com](https://www.seanmullin.com)

---

*This training program is supported by the Ivey Foundation.*
