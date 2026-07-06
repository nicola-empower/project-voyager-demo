# Project Voyager - Travel Architecture & AI Spike

[![Stack](https://img.shields.io/badge/Architecture-Vanilla%20%2B%20Tailwind%20v3-blue?style=flat-square)](#)
[![Workflow](https://img.shields.io/badge/Pattern-Human--in--the--Loop-purple?style=flat-square)](#)
[![Compliance](https://img.shields.io/badge/Compliance-Corporate%20Policy%20Engine-emerald?style=flat-square)](#)

An interactive corporate travel dashboard prototyping a seamless, natural language itinerary generator. It demonstrates how autonomous language models can be safely paired with human verification layers to completely eliminate business booking friction.

---

## 🎯 The Product Concept: The Travel Desk, Accelerated

Corporate travel booking is historically high-friction, forcing employees to bounce between separate, rigid booking portals to manually stitch together flights, accommodation, and ground transfers. 

The core architectural thesis of this system challenges that fragmentation: **Booking business travel should be as simple as sending a single text message to an executive assistant.** By typing an itinerary in plain English, the system instantly processes the prompt, maps flight parameters, checks real-time accommodation proximity to business meetings, balances spend targets against a strict corporate policy matrix, and prepares a structured, multi-tier itinerary sheet ready for final human agent sign-off.

---

## 💼 Real-World Operational Context: Empowering the Modern VA

While this repository operates as a public client-side prototype, the full production architecture serves as a core internal automation asset for **Empower Virtual Assistant Services**. 

In high-end executive support, cross-referencing flights, calculating localised ground transfers, and balancing multi-tier corporate travel budgets represents a significant manual time sink. This tool was engineered to collapse that timeline entirely. By using structured natural language parsing to handle the initial research and layout generation, a virtual assistant can review a completely optimised, policy-compliant itinerary in seconds. This architecture preserves strict human oversight for final seat selection, luggage verification, and booking execution, allowing the business to deliver elite, rapid corporate travel coordination with zero administrative drag.

---

## ⚙️ Architectural Intent & Strategy

Deploying fully autonomous agents with direct API booking access introduces massive operational risks, including fluctuating market costs, unapproved expenses, and broken cancellation policies. This repository isolates and validates a stable alternative: **a robust Human-in-the-Loop (HITL) system pattern.**

This static prototype achieves three primary engineering goals:
1. **Natural Language Scope Transformation:** Simulates the translation of unformatted, conversational text inputs into distinct database arrays (categorised into flights, accommodation fields, and train or car transfer objects).
2. **Synchronous Policy Validation:** Intersects calculated financial state totals against a hardcoded background corporate allowance limit, instantly returning dynamic visual compliance states based on the budget headroom.
3. **Stateful Multi-View Navigation:** Manages a single-page application (SPA) routing engine entirely client-side using clear class toggle matrices. This ensures that historical trip data records, dashboard event logs, and the onboarding wizard retain consistent memory boundaries without introducing sub-page lag.

---

## 💎 Core Features & Engineering Highlights

### 📋 Asynchronous Processing & State Mocking
* Implements a coordinated multi-tier wizard progression (`#step-1-prompt` to `#step-2-loading` to `#step-3-results`) driven by standard event listeners.
* Curates a stylised processing screen utilizing structured string arrays to sequentially cycle through complex procedural metrics (flight queries, hotel indexing, and calendar conflict checks), giving the user a highly responsive feedback loop during long simulated API calls.

### 🛡️ Automated Compliance Ledger
* Models a live policy verification container that cross-examines estimated aggregate balances against a strict £500 corporate expense cap.
* Evaluates financial parameters in real-time, outputting clean, semantic indicators that calculate remaining cash margins automatically to prevent rogue overspending before the document moves to procurement teams.

### 🔀 Modular Data Content Injector
* Features isolated view architectures capable of parsing distinct travel history items dynamically based on element click states (`data-trip="london"` vs `data-trip="paris"`).
* Employs clean object visibility resets on detail navigation, instantly updating global layout states while cleanly forcing the navigation bar back into an active sync position.

---

## 🎨 Design Philosophy: Cognitive Flow
* **Inter Font Foundation:** Structured around a highly clean, sans-serif design system token engineered specifically to handle dense data matrices, financial ledgers, and multi-leg transit tables comfortably.
* **Semantic Status Palette:** Uses premium royal indigo tones (`#4F46E5`) for active user navigation paths, balanced with rich emerald green environments for validated policy metrics and slate tones for historical archives.
* **Friction-Free Backdrops:** Implements delicate, animated transparent black blurs (`backdrop-blur-sm`) to isolate notification layers cleanly, maintaining a spacious, executive aesthetic throughout.

---

## 🛠️ Stack & Dependencies
* **Tailwind CSS Utility Wrapper** - Rapid layout tokens, responsive responsive flex grids, and smooth transform scales.
* **Lucide Iconography Core** - Modern vector icons mapped uniformly across transport classifications.
* **Vanilla JavaScript DOM API** - Dynamic class list arrays, element query matching, and interval event pipelines.

---

> 🧠 **Engineering Retrospective:** *This project proves that integrating a validation step into AI workflows creates a far more stable and reliable business process. By letting language models handle the tedious work of digging up flights and mapping distances, and then routing that structured data to an expert agent for final confirmation, the system achieves ultimate speed without sacrificing security or oversight.*

---

## Nicola Berry
