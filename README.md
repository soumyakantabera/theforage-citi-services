# Commercial Card Analytics Case Study: Client Needs Assessment to Executive Reporting

<p>
  <img src="https://img.shields.io/badge/Program-Citi%20Treasury%20%26%20Trade%20Solutions-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-The%20Forage-lightblue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

**Citi Treasury and Trade Solutions (TTS) — Forage Virtual Experience Program**

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Program Context](#program-context)
- [Tasks, Approach, and Results](#tasks-approach-and-results)
  - [Task 1 — Client Discovery and Needs Assessment](#task-1--client-discovery-and-needs-assessment)
  - [Task 2 — Commercial Card Product Concept and Pitch Deck](#task-2--commercial-card-product-concept-and-pitch-deck)
  - [Task 3 — Fee Modelling and Transaction Analysis](#task-3--fee-modelling-and-transaction-analysis)
  - [Task 4 — Leadership Insights Presentation](#task-4--leadership-insights-presentation)
- [Skills Demonstrated](#skills-demonstrated)
- [Limitations and Scope](#limitations-and-scope)
- [Repository Structure](#repository-structure)
- [Conclusion](#conclusion)

---

## Project Overview

This repository documents the end-to-end commercial card case study I completed as part of the **Citi Forage Virtual Experience Program (Treasury and Trade Solutions track)**. The program simulates the day-to-day work of a junior product or business analyst on Citi's commercial card team, and is structured as four progressive exercises that build on one another — from initial client discovery all the way through to a polished executive presentation.

The scenario centres on a long-standing Citi client named **Joe**, who owns a growing multi-location food-franchise chain. Joe's business is expanding rapidly, his expense management is becoming unmanageable, and Citi sees an opportunity to deepen the relationship by introducing a tailored commercial card product. The four tasks trace that opportunity from the first client conversation through product design, financial modelling, and leadership sign-off.

All client details, transaction data, and business figures are **synthetic and provided by the Forage program** for educational purposes. No real Citi client data or live systems are involved.

---

## Program Context

| Item | Detail |
|---|---|
| **Program** | Citi Forage Virtual Experience — Treasury and Trade Solutions |
| **Track** | Commercial Card Analytics |
| **Completed** | May 2026 |
| **Format** | Self-paced; four sequential case exercises |
| **Dataset** | 5,000-row synthetic corporate card transaction file |

---

## Tasks, Approach, and Results

### Task 1 — Client Discovery and Needs Assessment

#### Background
Before recommending any product, a good analyst needs to understand the client's world. Joe's franchise chain has grown to multiple locations, each with its own expenses, employees making purchases on various cards, and limited central visibility. Citi needs structured information to design the right solution.

#### Approach
Using the email template and question-design guidance provided by the program, I drafted a professional client-discovery questionnaire addressed directly to Joe. The questionnaire was structured in three logical sections:

1. **Current expense management** — How does Joe track spending today? What tools, cards, or processes are already in place? How many employees make purchases on behalf of the business?
2. **Pain points and friction** — Where does the current process break down? Are there recurring issues with receipts, reconciliation, reimbursements, or spend limits?
3. **Business direction** — How many locations does Joe plan to open in the next 12–24 months? Does he anticipate international expansion? What does "better expense management" look like to him?

The questions were written to balance open-ended responses (which surface unexpected pain points) with structured options (which make it easy for a busy client to respond quickly). The tone was warm, professional, and mindful of Joe's time.

#### Result
A polished questionnaire email delivered in both DOCX and PDF formats. The document gives a Citi relationship manager a ready-to-send asset that will generate the exact information needed to move from discovery to recommendation — covering spend volume, employee headcount, current banking relationships, and growth trajectory.

**Output files:** `Task_1_Client_Discovery/output/Questionnaire_Email_to_Joe.docx` · `.pdf`

---

### Task 2 — Commercial Card Product Concept and Pitch Deck

#### Background
Armed with the client profile from Task 1, the next step is to translate those needs into a concrete product pitch. The goal is to propose a commercial card that genuinely solves Joe's problems while demonstrating Citi's competitive advantage.

#### Approach
I designed a four-slide pitch deck (built on the programme template) introducing the **FranchiseFlex Commercial Card** — a product concept tailored specifically to franchise businesses with distributed employee spend. The deck was structured as follows:

1. **Slide 1 — The Client Challenge:** A concise summary of Joe's pain points: fragmented spend across locations, lack of real-time visibility, manual reconciliation burden, and plans to expand internationally.
2. **Slide 2 — Product Overview and Key Features:** The FranchiseFlex card offers per-location spend controls, a centralised online dashboard with real-time transaction feeds, automated monthly reporting, built-in foreign transaction capability for international growth, and an integration API for popular accounting software.
3. **Slide 3 — Pricing and Incentives:** A transparent fee structure (annual card fee, foreign transaction rate, and a tiered cashback scheme on high-volume spend categories) plus a limited-time launch offer waiving the first-year fee for clients who onboard within the quarter.
4. **Slide 4 — Why Citi:** A brief competitive positioning slide highlighting Citi's global network, TTS platform stability, and dedicated relationship-manager support.

The design choices were intentional: minimal text per slide, one key message per section, and a visual hierarchy that lets a decision-maker absorb the core value proposition in under two minutes.

#### Result
A professional four-slide pitch deck that a Citi product or relationship manager could present to a franchise client with minimal modification. The deck directly connects Joe's stated challenges to specific product capabilities, making the value case clear without relying on jargon.

**Output file:** `Task_2_Card_Pitch/output/Citi_FranchiseFlex_Commercial_Card_Pitch.pptx`

---

### Task 3 — Fee Modelling and Transaction Analysis

#### Background
The most analytically intensive task: the program provided a raw Excel file containing **5,000 synthetic corporate card transactions** spanning multiple clients, regions, payment types, and months. The goal was to build a well-structured financial model that calculates fee revenue, surfaces patterns, and allows scenario testing.

#### Approach
I constructed the fee analysis workbook from scratch in Excel, organising it into clearly labelled worksheets:

**Fee Calculation Engine**
- Applied dynamic fee formulas referencing a centralised parameter table (interchange rate, foreign transaction surcharge, annual card fee per client tier) so that changing any single rate instantly recalculates revenue across all 5,000 rows.
- Separated domestic and international transactions to apply the correct surcharge logic.

**Summary Tables (Pivot-style)**
- *By Client:* Total spend, total fees generated, average transaction size, and fee yield percentage — immediately showing which clients drive the most fee income.
- *By Region:* Spend and fee breakdown across geographies, revealing whether certain regions are over- or under-represented.
- *By Payment Type:* Split between credit, charge, and virtual card transactions, highlighting the mix and its fee implications.
- *By Month:* A 12-month trend view to identify seasonality or growth patterns in spend and fee income.

**Competitive Fee Comparison**
- Mapped Citi's fee structure against two competitor commercial card products (constructed from publicly available reference data provided in the programme), comparing annual fees, foreign transaction rates, and cashback terms side-by-side.

**Charts (three embedded visualisations)**
- *Spend Distribution by Client:* Bar chart showing relative client contribution to total portfolio spend.
- *Payment Mode Mix:* Pie chart of transaction volume by payment type.
- *Monthly Fee Revenue Trend:* Line chart showing fee income over the 12-month window.

#### Result
A transparent, formula-driven Excel workbook that serves as both a revenue model and an analytical summary. Key findings from the dataset:

- A small number of clients account for a disproportionately large share of total spend, indicating **client concentration risk** that deserves attention in the leadership presentation.
- Virtual card transactions, while fewer in number, carry a higher average transaction value and therefore a higher fee yield per transaction.
- Spend peaks in certain months, suggesting seasonal patterns that could inform targeted promotions or limit adjustments.
- Citi's fee structure is competitive on annual fees but has room to improve on foreign transaction rates relative to at least one competitor.

The model is designed so a colleague can update the fee parameters and immediately see the impact without needing to understand every formula.

**Output file:** `Task_3_Fee_Analysis/output/Citi_Commercial_Card_Fee_Analysis.xlsx`

---

### Task 4 — Leadership Insights Presentation

#### Background
The final task is to synthesise everything — client insight, product concept, and data findings — into a concise five-slide executive presentation that senior leadership can review quickly and act on.

#### Approach
I built the leadership deck on the programme slide template, focusing on clarity and decision-readiness. Each slide has one central message supported by a chart or table pulled directly from the Task 3 workbook:

1. **Portfolio Snapshot:** High-level metrics — total spend, total fee income, number of active clients, and portfolio growth rate — giving leadership an immediate sense of scale.
2. **Client Concentration Analysis:** A ranked view of spend by client with a visual callout of the top-three clients' combined share. This slide explicitly names the concentration risk and frames it as both a vulnerability and a cross-sell opportunity.
3. **Payment Mix and Fee Yield:** The payment type breakdown with an overlay of fee yield per type, making it clear that shifting clients toward virtual or charge products would improve fee income without increasing spend volume.
4. **Competitive Positioning:** A simplified side-by-side fee comparison showing where Citi leads and where there is a gap, informing potential product or pricing adjustments.
5. **Recommendations:** Three concrete, actionable recommendations:
   - **Diversify the client base** — prioritise onboarding mid-tier franchise clients to reduce reliance on the top-three accounts.
   - **Promote virtual card adoption** — run a targeted campaign for existing clients to migrate routine purchases to virtual cards, improving fee yield.
   - **Review the foreign transaction fee** — consider a rate reduction for high-spend clients to close the competitive gap and support clients with international operations (directly relevant to Joe).

Formatting decisions: charts were sized and positioned so they read clearly at a glance, slide titles were written as conclusions rather than topic labels (e.g. "Top 3 clients represent 58% of portfolio spend" rather than "Client Breakdown"), and no slide exceeds five bullet points.

#### Result
A polished five-slide presentation that senior leadership can act on in a single meeting. The deck tells a coherent story: we understand the portfolio, we see the risks, we see the opportunities, and here are three steps we can take immediately. The narrative flows directly from the data in Task 3 and the product thinking in Task 2, giving the work end-to-end integrity.

**Output file:** `Task_4_Leadership_Insights/output/Yoyo_Card_Leadership_Insights_Final.pptx`

---

## Skills Demonstrated

| Skill Area | How It Was Applied |
|---|---|
| **Client discovery** | Structured questionnaire design; translating business context into targeted questions |
| **Product thinking** | Mapping pain points to product features; building a business case narrative |
| **Financial modelling** | Dynamic, parameter-driven fee calculations; scenario sensitivity |
| **Data analysis** | Aggregation and summarisation of 5,000 transactions; identifying concentration and mix patterns |
| **Data visualisation** | Chart selection and design for different audiences (client vs. leadership) |
| **Executive communication** | Slide decks written for decision-makers; conclusion-first titles; no unnecessary detail |
| **Assumption documentation** | Clearly scoping what is known, estimated, and out of scope at every stage |

---

## Limitations and Scope

This is a structured learning simulation with clear boundaries:

- **All data is synthetic.** The 5,000-row transaction file and all client details were provided by the Forage programme. They do not represent real Citi clients, actual transaction volumes, or live revenue figures.
- **The FranchiseFlex card is illustrative.** The product concept, its features, pricing, and promotional offer were designed to satisfy the case requirements. They are not a real Citi product.
- **No advanced modelling.** The analysis relies on aggregation, pivot-style summaries, and charting — which is appropriate for the scope of the exercise. Forecasting, regression, or ML-based approaches were not within scope.
- **Single data source.** In a real engagement, the recommendations would be validated against additional data (client interviews, market benchmarks, internal pricing databases). Here they are grounded in the provided dataset and case prompts only.
- **No live systems.** Nothing in this repository connects to any Citi platform, API, or internal system.

---

## Repository Structure

```
theforage-citi-services/
├── README.md
├── Task_1_Client_Discovery/
│   ├── input/
│   │   ├── Task 1 - Tips on asking questions_.pdf    ← programme guidance
│   │   └── Task_1-Email Template.docx                ← starting template
│   └── output/
│       ├── Questionnaire_Email_to_Joe.docx           ← final deliverable
│       └── Questionnaire_Email_to_Joe.pdf
├── Task_2_Card_Pitch/
│   ├── input/
│   │   ├── Citi - TTS - Task 2 - Template.pptx      ← slide template
│   │   └── Task_2-Customer Finding_.pdf              ← client profile brief
│   └── output/
│       └── Citi_FranchiseFlex_Commercial_Card_Pitch.pptx
├── Task_3_Fee_Analysis/
│   ├── input/
│   │   ├── Task_3-Raw Data.xlsx                      ← 5,000-row transaction file
│   │   └── Task_3-Model Solution_.xlsx               ← reference model
│   └── output/
│       └── Citi_Commercial_Card_Fee_Analysis.xlsx    ← fee model + charts
└── Task_4_Leadership_Insights/
    ├── input/
    │   └── Citi TTS - Task 4 - Slides Template.pptx
    └── output/
        └── Yoyo_Card_Leadership_Insights_Final.pptx
```

---

## Conclusion

This case study traces a realistic analyst workflow from the very first client conversation through to a boardroom-ready presentation. Each task feeds directly into the next: the discovery questionnaire shapes the product concept; the product concept informs what the fee model needs to prove; and the fee model's findings drive the leadership recommendations.

The most important takeaway from the analysis is that **portfolio health depends on more than total spend**. The data revealed significant client concentration, an underutilised payment type with a better fee profile, and a pricing gap in foreign transactions — three issues that are easy to overlook when looking only at top-line revenue numbers. Framing those findings in a way that is actionable for senior leadership, without drowning them in spreadsheet detail, is the core skill this programme tested.

Beyond the deliverables themselves, the exercise reinforced a discipline that matters in any analytical role: **document your assumptions explicitly, keep your models transparent enough for someone else to audit, and always connect data findings back to a business decision**. A well-built Excel model that no one can interpret is no better than a rough estimate on a whiteboard.

This repository demonstrates that I can navigate an end-to-end analytical engagement — understanding a client, designing a solution, modelling the financials, and communicating the results — within a structured, professional framework. I am happy to walk through any part of the work in detail during an interview.

---

*Completed May 2026 · Citi Forage Virtual Experience Program — Treasury and Trade Solutions, Commercial Card Track*
