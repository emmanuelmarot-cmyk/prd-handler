---
name: prd-handler
description: "Generate or update a Product Requirements Document (PRD) for a technical project. Use when asked to create a PRD, to plan a feature, to start a new project, or to continue working on an existing PRD. Triggers on: create a prd, write prd, update prd."
---

# PRD Generator

Create and update detailed Product Requirements Documents that are high quality, clear, short, actionable, and suitable for implementation.

## Project Milestones

1. **Proposal** — a new idea is accepted or rejected.
2. **Project review** — lengthy projects need an intermediary checkpoint.
3. **Launch review** — cross-functional alignment around dates, scope, and messaging; no remaining blockers.
4. **Retrospective** — 90 days after launch, compare actual efforts and impact against initial projections.

## Behavior

Base your writing on a series of questions you will ask and the answers provided by the user.

**Important:** Keep this document as short as possible. Write as concisely as possible while keeping the meaning intact. Do not start implementing — just create or update the PRD.

- If it is a **new document**, create a PRD that follows the template below. Save the output as a Google Doc at the end.
- If it is the **continuation of an existing document**, ask what needs to be changed and follow through. Make sure that any significant change in the project, or any important steps (such as a required approval), is properly documented in the Logs section.

Systematically revisit sentences and paragraphs to shorten them whenever possible.

## Question Guidelines

- Follow the template below and keep asking questions to the user.
- Ask only critical questions where the input is ambiguous, more clarification is needed, or some sections are still unfilled.
- Decompose the questions. It's better to ask many simple questions one by one rather than throwing 5 questions at once.
- When possible, provide potential answers so that it's possible to click and select them to answer the questions. Make the interactions as visual as possible.

## PRD Template

### Document Header

| Field     | Value              |
|-----------|--------------------|
| **Title** | Feature/Product name |
| **Author** | PM name           |
| **Created** | YYYY-MM-DD       |

---

### Proposal

> The goal of this section is to provide a brief description, and describe the opportunity and the resources needed. This section should be fully completed before the "Proposal review" step.

#### Description

The very first step is to create a description summary. Ask as many questions as needed until you can produce a high-quality paragraph (20–200 words) that explains the project in clear language. This paragraph is a kind of "executive summary" for a press release.

#### Problem(s)

Why does this matter? Ground everything in the customer pain point.

- What specific pain point or unmet need exists?
- Who is affected?
- What is the cost of inaction?
- **Evidence:** what data, research, or customer signals validate this problem and its importance?

#### Opportunity & Success Metrics

- What is the business or market opportunity? Why now?
- What does "done well" look like, in measurable terms? List goals, expected impact with concrete numbers, and alignment with existing OKRs.

#### Go to Market

- Who are we building for, specifically? And who do we expect to be the first 5 users or customers?
- What is the pricing model?

#### Non-Goals

What are we deliberately NOT solving? This prevents scope creep and is as important as goals.

#### Costs & Efforts

Short, ballpark estimate. Provide a short, ballpark estimate of the total engineering effort in person-weeks (not just the longest-path task). Assume ~80% of an engineer's time per week is available for this project.

---

### Description & Requirements

> This section needs to be complete for the project review.

#### User Experience

How will real people use this? Write as a narrative, use a user story format. What does it look like and feel like? Include mock-ups or links to artifacts or a prototype.

#### Functional Requirements

What must the product do? Prioritized and testable. Use MoSCoW prioritization:

- **Must Have**
- **Should Have**
- **Could Have**
- **Won't Have**

#### Non-Functional Requirements

How must the product behave beyond features? For instance, latency or security requirements.

#### Dependencies

- Teams or projects that this project depends upon.
- Teams or projects that depend upon this project.

#### Risks & Mitigations

What could go wrong and what's our plan?

#### Release Plan & Milestones

When and how will we ship?

---

### Logs

This section keeps track of all the important changes to the project, as well as its milestones. Maintain a list with dates and clear, short descriptions.
