# AI-Assisted Virtual Workshop Framework

A reusable workshop framework for structured collaboration, asynchronous facilitation, knowledge transfer, and responsible AI-assisted documentation.

> **Portfolio project:** This repository contains only public-safe demonstration material. Internal company processes, participant information, customer data, operational details, and confidential workshop material are intentionally excluded.

---

## Overview

This project demonstrates a workshop framework I designed to help distributed and cross-functional teams:

- understand the current situation
- generate ideas independently
- structure and cluster input
- prioritise improvement opportunities
- define actions and ownership
- document outcomes more efficiently
- continue the workshop even when the original facilitator is unavailable

The complete internal workshop included facilitator guidance, step-by-step workshop videos, practice boards, participant training, and AI-assisted Whiteboard support.

Due to confidentiality requirements, this public repository contains only one public-safe **participant training video** and a description of the overall design approach.

The purpose of this repository is therefore to demonstrate the **design thinking, facilitation structure, governance approach, and reusable operating model** behind the workshop rather than reproduce internal company material.

---

## The Design Challenge

Cross-functional workshops can become difficult when:

- participants have different levels of process understanding
- discussions become unstructured
- important ideas are lost
- prioritisation consumes significant time
- documentation requires additional manual effort
- the original facilitator is unavailable
- internal process information cannot be shared outside the organisation

The main design question became:

> **How can a workshop remain structured, repeatable, and usable even when the original designer is not present?**

---

## Workshop Architecture

The workshop is divided into two main phases.

### Part 1 — Understand and Structure

1. **Current Situation**
2. **Brainwriting**
3. **Clustering**

The objective is to collect and structure perspectives from all relevant participants before moving into prioritisation.

### Part 2 — Decide and Act

4. **Prioritisation**
5. **Action Definition**
6. **Closing and Ownership**

If workshop time is limited, Part 1 can be completed with the wider participant group while Part 2 can later be completed by a smaller decision-making group.

---

## Workshop Flow

```mermaid
flowchart LR
    A[Current Situation] --> B[Brainwriting]
    B --> C[Clustering]
    C --> D[Prioritisation]
    D --> E[Action Definition]
    E --> F[Ownership & Closing]

    C --> G[AI-Assisted Draft Summary]
    G --> H[Human Validation]
    H --> D
```

---

## Asynchronous Facilitation

A change in priorities meant that I was not able to be physically present during the workshop.

Instead of making the activity dependent on the original facilitator, I created reusable digital guidance covering:

- workshop introduction
- Part 1 facilitation
- Part 2 facilitation
- AI-assisted Whiteboard usage
- participant preparation
- facilitator practice material
- sample workshop structure

The objective was to reduce single-person dependency and enable other facilitators to understand the intent and execute the workshop independently.

The internal facilitator videos, Whiteboards, examples, and company-specific process material are not included in this public repository.

---

## Public Participant Training Video

The repository includes one public-safe participant training video.

The video helps participants understand:

- how to prepare for the workshop
- how to use the digital Whiteboard
- how to contribute ideas independently
- how workshop input is captured
- how collaboration happens before prioritisation

### Watch the Participant Guide

[▶ Watch Workshop Participant Guide — English (Microsoft Whiteboard)](https://github.com/prbh695a/ai-assisted-virtual-workshop-framework/blob/d7ab6cc806e3641b7615ac82f907017d52f511ca/Workshop%20Participant%20Guide_EN_Microsoft%20Whiteboard.mp4)

---

## AI-Assisted Layer

AI-assisted Whiteboard capabilities were explored to support:

- clustering ideas
- identifying recurring themes
- creating first-draft summaries
- reducing administrative effort
- accelerating preparation of follow-up documentation

AI is used as an **assistant**, not as a decision-maker.

The intended operating model is:

```text
Participants
    ↓
Digital Whiteboard
    ↓
AI-Assisted Draft / Clustering
    ↓
Human Review
    ↓
Validated Workshop Outcome
    ↓
Actions + Ownership
```

The Whiteboard and participant discussion remain the **source of truth**.

Any AI-generated output must be reviewed before it is accepted as a final workshop record.

---

## Human-in-the-Loop Principle

The framework follows a simple governance model:

| Component | Responsibility |
|---|---|
| Participants | Provide ideas, observations, and context |
| Whiteboard | Captures the primary workshop input |
| AI | Supports clustering and first-draft summarisation |
| Facilitator | Reviews structure and guides the process |
| Humans / Decision Makers | Validate outcomes and define final actions |

AI does not replace human judgment, accountability, or ownership.

---

## Digital Twin / AI-Generated Presentation Support

Some internal facilitator material was created using an AI-generated digital representation / voice.

The **workshop concept, structure, scripts, facilitation logic, and guidance were designed and reviewed by me**.

The digital representation was used only as a delivery mechanism to support asynchronous knowledge transfer when physical participation was not possible.

Those internal videos are not published in this repository due to confidentiality requirements.

---

## Design Principles

The framework was developed around the following principles:

- **Reduce single-person dependency**
- **Keep the process simple before adding technology**
- **Participation before prioritisation**
- **Human-in-the-loop AI**
- **Transparent AI usage**
- **Clear ownership of final decisions**
- **Reusable participant guidance**
- **Asynchronous knowledge transfer**
- **Governance before deployment**
- **Confidentiality by design**
- **Continuous improvement through feedback**

---

## Governance and Confidentiality

The complete workshop was developed for an internal business environment.

To protect confidentiality, this repository intentionally excludes:

- internal workshop recordings
- company-specific processes
- internal Whiteboards
- participant names
- participant recordings
- customer information
- internal screenshots
- internal templates
- operational or production data
- internal links
- confidential technical information

Only public-safe demonstration material is included.

This reflects an important principle of the project:

> **Knowledge sharing should not compromise confidentiality, governance, information security, or responsible AI practices.**

---

## What This Project Demonstrates

This project demonstrates my approach to:

- engineering and process leadership
- structured problem solving
- reusable capability development
- digital facilitation
- asynchronous knowledge transfer
- distributed-team collaboration
- responsible AI adoption
- human-in-the-loop governance
- process scalability
- reducing dependency on individual facilitators
- balancing innovation with confidentiality and governance

---

## Leadership Reflection

The key learning from this project was that a useful process should not depend entirely on the person who created it.

When changing priorities meant that I could not participate personally, I converted my facilitation approach into reusable guidance, participant training, structured workshop steps, and AI-assisted support.

The objective evolved from:

> **Running a workshop**

to:

> **Building a reusable capability that another facilitator could execute independently.**

This shift toward repeatability, knowledge transfer, governance, and reduced single-person dependency is the most important outcome of the project.

---

## Portfolio Relevance

From a software-engineering and digital-solutions leadership perspective, this project demonstrates how I approach:

**Problem → Process Design → Digital Enablement → AI Assistance → Human Validation → Reusable Capability**

The same principles can be applied to engineering delivery, technical governance, onboarding, process improvement, knowledge management, and AI-enabled transformation.

---

## Disclaimer

This repository is a personal portfolio demonstration.

It contains only public-safe material and does not include confidential company, customer, production, operational, or participant information.

Any references to internal implementation concepts have been generalised or removed to protect confidentiality.
