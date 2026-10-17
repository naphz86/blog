# When Is the Data Network Good Enough for AI?

**An Economic Approach to Using AI in Companies and Large Enterprises**

*Basis: the author's own guiding thoughts, combined with the statements of the BE-terna webinar "Data Product and AI in Controlling" (speaker: Michael Sullmann, October 2026). Sections marked "own elaboration" go beyond the webinar and extend the author's thoughts.*

---

## Table of Contents

1. [Guiding Thoughts](#1-guiding-thoughts)
2. [Executive Summary](#2-executive-summary)
3. [Starting Point: The Gap Between AI Ambition and Data Readiness](#3-starting-point-the-gap-between-ai-ambition-and-data-readiness)
4. [The Case Study: Why Is the Margin Falling?](#4-the-case-study-why-is-the-margin-falling)
   - 4.1 [The situation](#41-the-situation)
   - 4.2 [What the AI answered](#42-what-the-ai-answered)
   - 4.3 [What the controlling department found](#43-what-the-controlling-department-found)
   - 4.4 [Lessons from the case](#44-lessons-from-the-case)
5. [The Core Question: When Is It "Good Enough"?](#5-the-core-question-when-is-it-good-enough)
   - 5.1 [Trust is a question of error size, not error-freedom](#51-trust-is-a-question-of-error-size-not-error-freedom)
   - 5.2 [The data network is "good enough" when …](#52-the-data-network-is-good-enough-when-)
   - 5.3 [Error budget and stakes (own elaboration)](#53-error-budget-and-stakes-own-elaboration)
   - 5.4 [Levels of reliability (own elaboration)](#54-levels-of-reliability-own-elaboration)
6. [AI as a Hint and as a Cross-Check](#6-ai-as-a-hint-and-as-a-cross-check)
   - 6.1 [AI as a hint](#61-ai-as-a-hint)
   - 6.2 [AI as a cross-check](#62-ai-as-a-cross-check)
   - 6.3 [The learning loop](#63-the-learning-loop)
   - 6.4 [Reading deviations correctly (own elaboration)](#64-reading-deviations-correctly-own-elaboration)
7. [The Foundation: The Data Product](#7-the-foundation-the-data-product)
   - 7.1 [Component 1: Data](#71-component-1-data)
   - 7.2 [Component 2: Meaning](#72-component-2-meaning)
   - 7.3 [Component 3: Label](#73-component-3-label)
   - 7.4 [One data product, many applications](#74-one-data-product-many-applications)
   - 7.5 [Rule of thumb](#75-rule-of-thumb)
8. [Responsibility: Three Accountabilities Before Go-Live](#8-responsibility-three-accountabilities-before-go-live)
9. [Step-by-Step Approach in Practice](#9-step-by-step-approach-in-practice)
10. [Companies and Large Enterprises](#10-companies-and-large-enterprises)
    - 10.1 [Comparison](#101-comparison)
    - 10.2 [Approach for mid-sized companies](#102-approach-for-mid-sized-companies)
    - 10.3 [Approach for large enterprises](#103-approach-for-large-enterprises)
11. [Typical Pitfalls (own elaboration)](#11-typical-pitfalls-own-elaboration)
12. [Measuring Progress (own elaboration)](#12-measuring-progress-own-elaboration)
13. [Checklist: May We Trust This AI Answer?](#13-checklist-may-we-trust-this-ai-answer)
14. [Conclusion](#14-conclusion)
15. [Appendix: Glossary](#15-appendix-glossary)

---

## 1. Guiding Thoughts

> When does a company have the certainty that the data in its fundamental data network is in such a state that it can trust the AI's answers? When the error in the answer is small enough?
>
> When is the data network good enough for the company? When are the relationships and connections within the company's data network such that the AI's answers are good enough?
>
> AI answers are worthwhile at least as a hint for, or a cross-check against, one's own economic strategy or way of proceeding.

These three thoughts carry the entire document:

1. **Trust is a matter of error size**, not of error-freedom. The question is not "Is the answer perfect?" but "Is the possible error small enough for this purpose?"
2. **"Good enough" refers to the data network**, meaning the data *and* the connections between them, not to the AI model. The same model gives good answers on a well-connected data network and misleading ones on a fragmented one.
3. **AI is first of all a source of hints and a means of cross-checking**, not a decision-maker. Used this way, it is valuable long before the data network is perfect.

Together they form an economic way of thinking: AI is neither blindly trusted nor dismissed. It is used proportionally, according to what is at stake and how reliable the underlying data is.

---

## 2. Executive Summary

- Almost every company wants AI (97 %), but only very few consider their data ready for it (5 %). The bottleneck is the **data network**, not the AI model.
- A practical case shows what happens when the data network is incomplete: an AI assistant explained only about **14 % of a margin gap** (60 of 440 T€) and recommended renegotiating discounts with a customer who was not responsible for the main cause.
- The answer to "When is it good enough?" is **economic**: when the remaining error is small enough relative to the **stakes of the decision**.
- Until then, AI is already useful **as a hint and as a cross-check** against one's own analysis. Every deviation from the company's own view points to **gaps in the data network**.
- The webinar's solution is the **data product**: data, meaning and label packaged together, with clear owners. It is built once and used by many applications (controlling, management, sales, AI agents).
- **Three named accountabilities** are required before go-live: who defines (Data Owner), who delivers (Data Product Owner), and who approves (Use-Case Owner).
- The approach is the same for mid-sized companies and large enterprises. What differs is scope, governance and the risk of conflicting definitions.

---

## 3. Starting Point: The Gap Between AI Ambition and Data Readiness

| Finding | Statement |
|---|---|
| Ambition | 97 % of companies have AI initiatives |
| Data readiness | Only 5 % consider their data fully ready |
| Obstacles | Restricted access to data (50 %), data quality (40 %), disconnected systems (38 %) |
| AI agents | 11 % already use them, another 29 % plan to |
| Investment | Companies with AI success invest up to 4× more in data quality and governance |

*Sources as given in the webinar: Dun & Bradstreet (10,000 companies, 32 countries, 2026), Bitkom 2026, Gartner 2026.*

**Webinar key message:** A better AI model does not close this gap. Better data does.

### What this means

The three obstacles are not model problems. They are problems of the **data network**:

- **Restricted access** means relevant data exists but cannot be reached by the AI (or by the people asking).
- **Data quality** means the data exists but cannot be relied upon in detail.
- **Disconnected systems** means the data exists in several places but is not linked, so the relationships between facts (for example freight costs and the order that caused them) are lost.

This ties directly to the second guiding thought: the question "Is the AI good enough?" is the wrong one. The right question is **"Is our data network good enough for this question?"**

AI also arrives faster than the data is ready. Agents are already being deployed (11 %) or planned (29 %) while only 5 % consider their data ready. The result is a growing gap between what AI is *asked* to do and what the data network can *support*. Closing it is an investment decision, and the data on companies with AI success suggests the investment goes into data quality and governance rather than into models.

---

## 4. The Case Study: Why Is the Margin Falling?

An illustrative case from the webinar: a supplier in mechanical engineering, Q1–Q3 2026.

### 4.1 The situation

| Indicator | Value |
|---|---|
| Revenue | €11.0 m (+10 % vs. prior year, €10.0 m) |
| Contribution margin II (DB II) | 24.0 % (prior year 28.0 %, i.e. −4 percentage points) |
| Gap in DB II | €440 k (€3.08 m at 28 % vs. €2.64 m at 24 %) |

Revenue grew, yet profitability fell. The question the company asks its AI assistant, which is connected to its analytics environment: *"Why is our margin falling, and what should we do?"*

### 4.2 What the AI answered

The AI explained that the margin fell mainly because of **increased discounts**. The average discount rate had risen from 6.1 % to 6.7 %, especially for large customers. Its recommendations:

- Discounts above 5 % only with approval from sales management
- Renegotiate special conditions with the top-10 customers
- Report discount development monthly to management

The answer sounds plausible and actionable. Two things were missing: **no sources were given, and the data timestamp was unknown.** The audience was asked: *Would you follow this recommendation? Yes, rather yes, or no?*

### 4.3 What the controlling department found

| Cause | Amount | Share of gap* | Found by the AI? | Why (not)? |
|---|---|---|---|---|
| **Express freight:** a supplier part was scarce, so 31 expensive rush deliveries were needed to supply customer "Nord" on time | €230 k | ≈ 52 % | No | Booked in logistics, invisible to the AI |
| **Product mix:** more low-priced standard parts were sold, on which the company earns less | €150 k | ≈ 34 % | No | The product group is missing in the data |
| **Discounts:** slightly increased from 6.1 % to 6.7 % | €60 k | ≈ 14 % | Yes | Visible in the sales data the AI could access |
| **Total gap** | **€440 k** | 100 % | | |

*\*Shares calculated for this document from the webinar figures.*

The AI's advice was to renegotiate discounts with top customers such as customer Nord. But customer Nord generates €2.0 m of revenue, and **the rush deliveries were not its fault.** Following the recommendation would have pressured a good customer over the smallest of the three causes while the largest remained unaddressed.

### 4.4 Lessons from the case

1. **A plausible answer is not the same as a reliable one.** The AI's answer was coherent, specific and wrong in proportion: it addressed about 14 % of the problem.
2. **The cause was the data network, not the model.** Freight was booked in logistics and not linked to the order. The product group was missing. A better model would have had the same blind spots.
3. **Missing provenance made the answer unassessable.** Without sources and a timestamp, the audience could not judge how far to trust it.
4. **A wrong recommendation has costs beyond the numbers.** Here it risked damaging the relationship with a customer worth €2.0 m in revenue.
5. **The partial answer was not worthless.** Discounts did rise, and the finding was true. It was just incomplete. Taken as a *hint*, it was useful. Taken as the *whole truth*, it was dangerous. This is exactly the distinction developed in section 6.

---

## 5. The Core Question: When Is It "Good Enough"?

### 5.1 Trust is a question of error size, not error-freedom

No data network is complete or perfectly accurate, and none will ever be. Waiting for perfect data means never using AI. The sensible question is therefore whether the **remaining error is small enough for the concrete purpose**.

This reframes the problem: instead of a yes/no question about data quality, it becomes a **proportionality question**. The same data network can be good enough for one purpose (spotting a trend) and insufficient for another (renegotiating a key customer contract).

### 5.2 The data network is "good enough" when …

The webinar provides the building blocks. Combined with the guiding thoughts, the data network is good enough when:

1. **The main influencing factors** of a question are present in the data network and linked (in the case: freight, express, discounts, product mix).
2. **Key figures are clearly defined**, and someone is accountable for the definition ("margin" = DB II; express freight belongs to the order).
3. **Quality and timeliness are measured** and known (for example product group ≥ 99 % populated, checked daily; freight updated weekly).
4. **The AI answer carries its provenance:** definition, source and data timestamp.
5. **The possible remaining error is in proportion to the stakes** of the decision.

The fifth point is the economic core: **the greater the stakes of a decision, the smaller the accepted error must be.**

### 5.3 Error budget and stakes (own elaboration)

A practical way to make "small enough" concrete is to think in terms of an **error budget** per use case:

| Question | Typical stakes | Acceptable error | Consequence for the data network |
|---|---|---|---|
| "Which product groups sell best?" | Low, informational | Fairly high | Core data suffices |
| "Where are we losing margin, and why?" | Medium to high, steers management attention | Moderate: main drivers must be covered | Main influencing factors must be linked |
| "Which customers should we renegotiate with?" | High, affects relationships and revenue | Low | Complete causal picture and quality evidence needed |
| "Automatically create a task / trigger an action" | Very high, acts without human review | Very low | Full governance, approval and logging |

Applied to the case: the AI covered about 14 % of the gap. For an *informational* question, that might be tolerable as a first hint. For the question *"What should we do?"* regarding a €2.0 m customer, it is clearly **not** good enough. The data network was not "bad" in general. It was **insufficient for that question**.

A simple rule can be derived from this: **before using an AI answer, ask what share of the effect it has demonstrably explained, and whether that share suffices for the decision at hand.**

### 5.4 Levels of reliability (own elaboration)

| Level | Role of the AI | Requirement on the data network | Example |
|---|---|---|---|
| 1 | **Hint** | Low, gaps are acceptable | "Take a look at discount development." |
| 2 | **Cross-check** | Medium, core figures linked and defined | Compare the AI breakdown against the controlling analysis |
| 3 | **Decision preparation** | High, measurable quality, source and timestamp | Recommendation with reasoning, a human decides |
| 4 | **Automated action** | Very high, approval and logging | AI creates tasks (only with clear approval) |

Companies do not have to wait for level 4 conditions. They can start at level 1 and 2 today and raise the level step by step as the data network proves itself.

---

## 6. AI as a Hint and as a Cross-Check

The third guiding thought is the pragmatic entry point: **AI answers are worthwhile today, provided they are classified correctly.**

### 6.1 AI as a hint

The AI points out directions and anomalies that might otherwise be overlooked. A hint is not a verdict. Its value lies in prompting a closer look. In the case, "discounts have increased" was a valid hint: true, checkable, and worth a look. The mistake would have been to treat it as the complete explanation.

### 6.2 AI as a cross-check

The AI answer is compared with the company's own strategy, analysis and experience:

- **Does it match the controlling analysis?** Then confidence in both rises.
- **Does it deviate?** Then the deviation is informative, because it shows **where the data network is missing something**. In the case, the deviation (discounts only vs. freight and product mix) would have exposed the gap in the data network immediately.

### 6.3 The learning loop

```
Question to the AI
        ↓
AI answer (with definition, source, timestamp)
        ↓
Cross-check against own strategy / controlling
        ↓
Deviation? → look for the cause in the data network
        ↓
Improve data, connection or definition
        ↓
(back to the next question)
```

Each pass through the loop improves the data network. The cross-check is thus **both a safeguard and a diagnostic tool**: the AI is used while simultaneously testing the data network.

### 6.4 Reading deviations correctly (own elaboration)

A deviation between the AI answer and the company's own view can have several causes. Distinguishing them is the actual work of the loop:

| Possible cause | Typical sign | Response |
|---|---|---|
| **Missing data** | The AI cannot see a factor (e.g. freight booked in logistics) | Connect the data source to the data product |
| **Missing attribute** | A needed dimension is absent (e.g. product group) | Add and maintain the attribute, then monitor its completeness |
| **Unclear definition** | Different people mean different things by the same term ("margin") | Have the Data Owner define it and record synonyms |
| **Outdated data** | The answer is correct for an older state | Clarify update frequency, show the timestamp |
| **Own analysis is wrong or incomplete** | The AI finds something the company overlooked | Examine it, learn from it, and correct the company's view |

The last row matters: the cross-check works in **both directions**. The AI can reveal gaps in the data network, and it can reveal gaps in the company's own thinking.

---

## 7. The Foundation: The Data Product

The webinar's answer to "Where does the knowledge go?" is: **into a data product**. Using the example "Sales Result 360" (data, meaning and label for all questions about revenue, margin and their drivers), a data product consists of three components.

### 7.1 Component 1: Data

Several tables and documents, linked around a defined granularity.

- **Center:** order items (revenue, production cost, discount, quantity). **One row = one order item.**
- **Linked dimensions:** customer, product, time, sales, freight per shipment, plan and prior year.
- **Documents:** framework agreements (PDF).

The decisive point is that these elements are **linked**. In the case, the missing link between freight and order was the root of the faulty answer.

### 7.2 Component 2: Meaning

What the numbers mean, so that people and AI interpret them identically.

| Element | Content in the example |
|---|---|
| **Key figures** | DB I, DB II, discount rate, freight rate |
| **Synonyms** | "Margin" = DB II |
| **Rule** | Express freight belongs to the order |
| **Influencing factors** | Freight, express, discount, product mix |
| **Comparison** | Prior year, plan |

The *rule* "express freight belongs to the order" would, if recorded, have changed the case: the AI could have attributed the €230 k to customer Nord's orders and correctly seen that it was not caused by discounts.

### 7.3 Component 3: Label

What one must know before use. It answers the guiding question "How far can I trust this?" directly, because it makes **reliability visible**.

| Element | Content in the example |
|---|---|
| **Owner** | Controlling, contact person named |
| **Quality** | Product group ≥ 99 %, checked daily |
| **Timeliness** | Daily, freight weekly |
| **Access** | By role, also for AI via MCP |
| **Version** | 1.2, changes announced |

Think of it as a nutrition label for data: whoever uses the data (human or AI) can see how complete, current and reliable it is, and who answers for it.

### 7.4 One data product, many applications

A data product is built once and used by many:

- **Controlling:** Qlik Answers or Copilot in Power BI ("Why did our DB II margin fall in September?")
- **Management:** in Teams or Copilot ("Where are we losing margin through rising freight costs?")
- **Sales:** in the AI assistant Claude ("Which customers bring a lot of revenue but little margin?")
- **Your AI agent:** via MCP, with approval ("Find unusual orders and explain possible causes.")

The three advantages named in the webinar:

- **Reusable:** the business logic is built only once.
- **Scalable:** each new application connects without a new data pipeline.
- **Secure:** same definition, same rights, one log.

Economically, this is the central lever: **the cost of making the data network trustworthy is incurred once, while the benefit accrues in every application.** Without a shared data product, each application would have to rebuild definitions and connections, with the risk that each one answers differently.

### 7.5 Rule of thumb

> **One business domain, one granularity, one owner, many questions.**

Starting small and well-defined is better than attempting a company-wide data model in one step.

---

## 8. Responsibility: Three Accountabilities Before Go-Live

Trust in data needs names. The webinar identifies three decisions that each need a named person:

| Role | Decides on | Typical holder | Guiding question |
|---|---|---|---|
| **Define** · Data Owner | **Meaning:** what a key figure means, which exceptions apply, what counts as a correct answer. In daily work supported by a Data Steward. | Business department, e.g. head of controlling | Who signs off the definition of "margin"? |
| **Deliver** · Data Product Owner | **Data:** ensures the data product is complete, current, checked and correctly authorized | Data team or IT | Who reacts when freight data is missing? |
| **Approve** · Use-Case Owner | **Use:** approves the AI application, maintains the test questions, decides when a human decides | Business department with IT | Who decides whether the AI may create a task? |

### Why this matters

- Without a **Data Owner**, no one is accountable for what "margin" means, so different tools may answer differently.
- Without a **Data Product Owner**, missing or stale data goes unnoticed (for example when freight data stops arriving).
- Without a **Use-Case Owner**, AI applications go live without defined test questions or limits on autonomy.

The three questions in the table are a useful **go-live check**: if any of them cannot be answered with a name, the application is not ready.

---

## 9. Step-by-Step Approach in Practice

*(Own elaboration, condensed from the guiding thoughts and the webinar.)*

1. **Clarify purpose and stakes.** Which decision should the AI support? How large may the error be there? (See the error budget in 5.3.)
2. **Identify the influencing factors.** What really drives the answer, not only the obvious factors? Ask the experts: in the case, controlling knew immediately that freight and product mix mattered.
3. **Inspect the data network.** Are these factors present, linked and of sufficient quality? Where are the gaps?
4. **Define meaning.** The Data Owner defines key figures, synonyms and rules, and signs them off.
5. **Build the data product.** Data, meaning and label, including owner, quality, timeliness, access and version.
6. **Define test questions.** Questions with a known correct answer, for example the margin analysis by controlling as a reference. These are maintained by the Use-Case Owner.
7. **Use AI as a hint and cross-check.** Hold the answers against the company's own strategy and evaluate deviations (section 6).
8. **Raise the trust level step by step.** From hint to cross-check to decision preparation. Automation only with explicit approval and logging.
9. **Readjust regularly.** The data network changes. Quality, definitions and test questions must evolve with it. Announce changes through the version number.

---

## 10. Companies and Large Enterprises

The principle is the same. The implementation differs.

### 10.1 Comparison

| Aspect | Mid-sized company | Large enterprise |
|---|---|---|
| **Data network** | Manageable, often few core systems | Many systems, divisions and locations, often grown silos |
| **Starting point** | One department, one data product, a few core questions | Several data products per business domain, aligned through shared definitions |
| **Responsibility** | Roles often held by one person | Roles clearly separated, Data Steward supports in daily work |
| **Main risk** | Gaps go unnoticed because nobody does the cross-check | Conflicting definitions ("margin" means something different in each division) |
| **Lever** | Quick benefit through cross-checking against controlling | Scaling: one data product serves many applications and AI agents |
| **Governance** | Lean: definition, owner, label | Formal: same rights, one log, approval processes |

### 10.2 Approach for mid-sized companies

*(Own elaboration.)*

- **Start with the question that matters most**, for example "Where do we lose margin?", and build the one data product behind it.
- **Use the people you already have.** Controlling usually knows the true drivers. Their analysis is the first reference for the cross-check.
- **Keep governance lean but explicit.** Even if one person holds several roles, write down who defines, who delivers and who approves.
- **Use AI at levels 1 and 2 first.** Hints and cross-checks bring benefit without demanding a perfect data network.
- **Expand along the questions** the business asks, not along the systems IT owns.

### 10.3 Approach for large enterprises

*(Own elaboration.)*

- **Cut by business domain, not by technology.** One domain, one granularity, one owner. Several such data products can coexist.
- **Harmonize definitions across domains early.** If "margin" differs between divisions, either unify the term or record clear synonyms and scopes. Otherwise AI answers will be inconsistent across the enterprise.
- **Separate the roles.** Data Owner, Data Product Owner and Use-Case Owner should be different people or teams so that definition, delivery and release check one another.
- **Make reuse the default.** New applications should connect to existing data products rather than build their own pipelines.
- **Standardize access and logging.** Same definition, same rights, one log across all applications, including AI agents.
- **Stage the autonomy.** Higher levels (decision preparation, automated action) are released per use case, based on test results and the stakes involved.

For both: **do not wait for the perfect data network.** Start with a bounded area, keep the error measurable, and extend the reach step by step.

---

## 11. Typical Pitfalls (own elaboration)

| Pitfall | What happens | Counter-measure |
|---|---|---|
| **Trusting fluent answers** | A well-worded answer is mistaken for a correct one | Require definition, source and timestamp with every answer |
| **Blaming the model** | Teams swap models while the real gaps remain | Diagnose deviations in the data network first |
| **Waiting for perfection** | AI is never used because data "is not ready" | Start at hint/cross-check level and improve iteratively |
| **Using the AI as the sole authority** | Decisions follow one unverified answer | Always cross-check against one's own analysis, especially for high stakes |
| **Undefined key figures** | Different tools and people calculate "margin" differently | Data Owner defines and signs off, synonyms recorded |
| **Invisible data** | Relevant data sits in a different department's system | Link it into the data product, assign a Data Product Owner |
| **No test questions** | Nobody notices when quality drops | Use-Case Owner maintains test questions with known answers |
| **Autonomy too early** | The AI triggers actions on incomplete information | Release automation only with approval, logging and a defined human decision point |

---

## 12. Measuring Progress (own elaboration)

To answer "Is the data network getting good enough?" over time, a few indicators help:

| Indicator | Question it answers |
|---|---|
| **Explained share** | On test cases, what share of the known effect does the AI explain? (In the case: ≈ 14 %, to be raised step by step) |
| **Test question pass rate** | How many of the maintained test questions does the AI answer correctly? |
| **Completeness of key attributes** | How well are critical fields populated (for example product group ≥ 99 %)? |
| **Timeliness** | Is data updated within the promised interval (daily, weekly)? |
| **Answers with provenance** | What share of AI answers shows definition, source and timestamp? |
| **Deviations resolved** | How many cross-check deviations led to a documented improvement? |
| **Reuse** | How many applications use the same data product? |

These indicators make the guiding question measurable: the data network is "good enough" for a use case when these values reach the level that the stakes of the use case demand.

---

## 13. Checklist: May We Trust This AI Answer?

- [ ] Is the **question** clear, and are the **stakes** of the decision known?
- [ ] Are the **main influencing factors** present in the data network and linked?
- [ ] Is the **key figure defined**, and does the definition have an owner?
- [ ] Does the answer state **definition, source and data timestamp**?
- [ ] Are **quality and timeliness** known and sufficient?
- [ ] Has the answer been **cross-checked against our own analysis or strategy**?
- [ ] Is the **possible remaining error** acceptable in relation to the decision?
- [ ] Is it clear **when a human decides**?

---

## 14. Conclusion

1. **The quality of the AI answer is the quality of the data network.** Data, connections and meaning decide, not the model.
2. **"Good enough" is an economic term.** The remaining error must be in proportion to the stakes of the decision.
3. **Trust can be built**, through definition, measurable quality, a label and named people who are accountable.
4. **AI is already worthwhile today as a hint and cross-check** against one's own strategy. Every deviation also shows where the data network must be improved, and sometimes where the company's own view is incomplete.
5. **A data product is the reusable foundation**, for mid-sized companies and large enterprises alike. The effort of making data trustworthy is invested once and pays off in every application.
6. **Responsibility must have names.** Defining, delivering and approving each need an accountable person before go-live.

> **Maxim:** Do not ask "Is the AI good enough?" Ask "Is our data network good enough for this question?" And until it is: use AI as a hint, cross-check it against your own strategy, and learn from every deviation.

---

## 15. Appendix: Glossary

| Term | Meaning |
|---|---|
| **Data network** | The totality of a company's data and the connections between them |
| **Data product** | A packaged, reusable unit consisting of data, meaning and label, with a named owner |
| **DB I / DB II** | German contribution margin levels (*Deckungsbeitrag I / II*); in the webinar "margin" = DB II |
| **Data Owner** | Business-side person accountable for the meaning of key figures |
| **Data Steward** | Supports the Data Owner in day-to-day work |
| **Data Product Owner** | Accountable for delivery: complete, current, checked, correctly authorized |
| **Use-Case Owner** | Accountable for approving an AI application, maintaining test questions and defining when a human decides |
| **MCP** | Model Context Protocol, a standard through which AI applications access data and tools (in the webinar: access by role, also for AI) |
| **Granularity** | The level of detail of one data row (here: one row = one order item) |
| **Provenance** | Information about definition, source and timestamp of an answer |
| **Error budget** | The amount of error acceptable for a given use case, depending on its stakes |
| **Cross-check** | Comparing an AI answer with one's own analysis or strategy |
