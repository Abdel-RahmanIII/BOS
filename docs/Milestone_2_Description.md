## German University in Cairo Faculty of Media Engineering and Technology Mervat AbuElkheir

## CSEN1096 Business of Software

Winter Term 2026

## Course Project – Build Your (First) Startup!

## Milestone 2 Description

In this document, a description of Milestone scope, deliverables, rubric, and deadline is provided. First, a quick recap of the overall investment readiness scale and VC scorecard from Milestone 1 description to keep you grounded.

## The Investment Readiness Scale

Every criterion in every rubric below is rated on the same scale that a VC partner uses after a meeting:

| Rating | Investor verdict | Meaning |
| --- | --- | --- |
| 5 | Strong conviction | “I would lead this round.” Clear, evidenced, and consistent with the rest of the case. |
| 4 | Interested | “Let’s schedule a follow-up meeting.” Strong, with minor gaps. |
| 3 | Interested, not convinced | “Come back when you have more evidence.” Reasonable, but key claims are not yet supported. |
| 2 | Skeptical | “I don’t see it yet.” Significant gaps, weak logic, or generic content. |
| 1 | Pass | “Not for us.” Claims without evidence, or the analysis is fundamentally wrong. |
| 0 | No show | The item is missing. |

A criterion’s score is (rating ÷ 5) × its weight. For example, a rating of 4 on a criterion weighted 15% earns 12 out of 15 points of that milestone.

## The VC Scorecard

Your startup will be assessed across the following dimensions. Each milestone focuses on some of them (● primary focus, ○ revisited), so that by Demo Day the panel has seen the complete investment case.

| Dimension | The question an investor asks | M1 | M2 | M3 |
| --- | --- | --- | --- | --- |
| Team & founder–market fit | Why are you the right founder(s) to build this, and how is the company structured? |   |   |   |
| Problem & customer | Is the problem real, painful, frequent and urgent? Where is the evidence? |   |   |   |
| Market opportunity | Is the market large and growing, and why is now the right time? |   |   |   |


| Dimension | The question an investor asks | M1 | M2 | M3 |
| --- | --- | --- | --- | --- |
| Product & differentiation | Is it clearly better than the alternatives, and what stops others from copying it? |   |   |   |
| Technical & operational feasibility | Can this be built, run and scaled at a cost that leaves a healthy margin, within the law? |   |   |   |
| Go-to-market | Is there a repeatable and affordable way to reach and win customers? |   |   |   |
| Business model & unit economics | Does each customer eventually make money? Does it get better with scale? |   |   |   |
| Evidence & traction | What have you proven with real people, not assumptions? |   |   |   |
| The deal | How much do you need, what will it buy, and what do investors get? |   |   |   |

After Milestones 1 and 2 you will receive a short investment memo from the instructor with one of three decisions: Proceed, Proceed with conditions (specific issues you must address in the next milestone), or Pivot recommended. The decision is feedback, not a grade: a team can receive “Pivot recommended” and still earn a high grade if its work was rigorous. Pivots after Milestone 1 are welcome. Pivots after Milestone 2 must be justified with evidence and approved by the instructor.

## Milestone 2: Software Architecture & Marketing Plan

Posted Week 8 · Due November 26 · VC stage: technical and commercial due diligence

Once an investor is interested, they check two things: can this team build and run the product at a sensible cost and risk, and can they get it into customers’ hands? The report has three parts (max. 15 pages in total, excluding appendices).

Deliverable 2.1: Architecture & Engineering Decisions

- Architecture style: monolith, modular monolith or microservices, justified by your team size, stage and expected load.

- Build vs. buy: for at least three capabilities (e.g., authentication, payments, analytics, search, AI models), compare building versus buying with a 3-year total cost of ownership (TCO) that includes engineering time and maintenance.

- Architecture Decision Records: at least three ADRs in a standard format (context, decision, alternatives considered, consequences).

- Cloud cost model: estimated monthly infrastructure cost at three scale points (e.g., 100, 10,000 and 100,000 active users), the cost per active user, and your main optimization levers. This number feeds your gross margin in Milestone 3.

- Regulation and compliance: what personal data you collect and where it is stored, and your obligations under the applicable rules (e.g., Egypt’s Personal Data Protection Law No. 151 of 2020, GDPR if you serve EU users, and sector rules such as Central Bank regulations for fintech).

- Vendors and platform risk: a mini-RFP scoring of candidate vendors for one critical service, the SLA and IP contract terms you would insist on, and a risk register for platform dependencies (e.g., app stores, a single AI API provider) with mitigations.

- Technical debt policy: which shortcuts you will deliberately take for the MVP and when you plan to repay them.


## Deliverable 2.2: Go-to-Market & Marketing Plan

- Positioning: a positioning statement

(for [ICP] who [need], [product] is a [category] that [key benefit]; unlike [main alternative], we

[key differentiator]) and your core messages.

- Growth motion: product-led (PLG), sales-led (SLG) or hybrid, justified by your expected contract value, who buys, and how complex the product is to adopt.

- Beachhead and launch sequencing: your first segment and the phases from private beta to public launch to expansion, each with a goal and an exit criterion.

- Channel strategy: at least three channels compared on cost, reach and fit with your ICP, with an expected customer acquisition cost (CAC) per channel, and your chosen primary channel.

- 90-day launch plan: activities, budget, owners and the funnel KPIs you will track. If you chose SLG, include your sales process (pipeline stages, expected sales cycle, who sells).

## Deliverable 2.3: Validation Experiment

Run at least one real, low-cost experiment that tests one of your riskiest assumptions from Milestone 1. For example, a landing page with a waitlist, a smoke-test ad, a clickable prototype test with at least five target users, pre-orders, or letters of intent (LOIs). No-code and AI tools can be used for this. Report the hypothesis, the success threshold you set before running it, the setup, the results, and the decision you made. Raw evidence (screenshots, analytics exports, signed LOIs) must be included in your Data Room.

## Milestone 2 Rubric

| Criterion (weight) | 5 – Strong conviction | 3 – Interested, not convinced | 1 – Pass |
| --- | --- | --- | --- |
| Build vs. Buy & TCO (15%) | 3+ capabilities with a 3- year TCO including engineering time, maintenance and lock-in. Decisions are based on the numbers. | Mostly qualitative; costs incomplete. | Decisions asserted without analysis. |
| ADRs & Technical Debt (15%) | 5+ ADRs with real alternatives and consequences. Explicit debt policy. | ADRs record decisions, but alternatives are straw men. | Fewer than five ADRs or no trade-offs. |
| Cost, Compliance & Risk (15%) | Cost at three scale points with cost per user. Regulations identified with concrete measures. Vendor and platform risks with mitigations and key SLA/IP terms. | Costs rough. Compliance mentioned generically. | No cost model. Compliance ignored. |
| Positioning & GTM Motion (20%) | Sharp positioning tied to ICP and alternatives. PLG/SLG choice justified. Entry point (beachhead) defined. | Positioning generic. Motion chosen without justification. | No clear target segment or motion. |
| Channels & Launch Plan (20%) | 3+ channels compared with expected CAC Sequenced 90-day plan with budget and funnel KPIs. | Channels listed without economics. Plan lacks KPIs or budget. | “Social media” is the entire plan. |


| Criterion (weight) | 5 – Strong conviction | 3 – Interested, not convinced | 1 – Pass |
| --- | --- | --- | --- |
| Validation Experiment (15%) | Real experiment with a falsifiable hypothesis. Threshold set in advance. Verifiable data and a clear decision. | Experiment run, but weak design or inconclusive results. | No experiment, or results cannot be verified. |

## Submission Instructions

Milestone reports are submitted as PDF files on a form by the founder or one of the co-founder(s). In addition, every team keeps a single shared Data Room (a Google Drive or OneDrive folder) whose link is given in the form as well, with view access for the instructor. If I cannot access your work because these directions are not followed correctly, I will not grade your work. The Data Room must contain: [URL 🔗](https://forms.gle/ewLg84WPAQmy1mi16)

- Milestone1, Milestone2, Milestone3 – the submitted reports and their appendices.

- Evidence – the experiment results and any LOIs, pre-orders or analytics exports.

- Financials – the financial model (with working formulas) and the cap table.

- README – a one-page index of the Data Room with the team name, founders, roles, and links to every item.

Milestones submitted after their due date will not be graded. Late days do not apply.

Deadline for submission is November 26th @ 11:59 PM. This is end of Academic Week 10.

## Academic Integrity and Use of AI

You may use generative AI tools for prototyping your experiment (Deliverable 2.3), provided you state in an appendix which tools you used and for what. You remain responsible for every claim and number you submit, and all market data must be cited to its original source.

## Grading Criteria

The project is worth 40% of your total course grade. These 40% will be divided as follows:

| Component | Weight | Graded with |
| --- | --- | --- |
| Milestone 1: Project Idea & Business Model Canvas | 25% | Milestone 1 Rubric |
| Milestone 2: Software Architecture & Marketing Plan 25% |   | Milestone 2 Rubric |
| Milestone 3: Growth & Monetization Plans (written deliverables) | 20% | Milestone 3 Rubric |
| Demo Day Pitch | 30% | Demo Day Rubric |
| Total | 100% |   |
| Best Investment bonus | up to +5% | Investor panel allocation |

Across all milestones, the grade corresponds to answers to questions that a VC would ask: Did you choose a problem worth solving? Did you gather real evidence? Is your reasoning sound and consistent? Would a rational investor put money into this company?
