# KPI-Storyteller
KPI Storyteller is a web app that turns raw data into KPI updates and executive-ready commentary. Paste your data + metrics + context and get a clear narrative: what changed, likely drivers, risks, and recommended next steps, written like a senior data analyst.

## What it does

- You paste KPI values (and optionally comparisons like WoW/MoM/YoY)
- Add business context (team, product, goals, recent changes)
- Get a structured analysis written like a senior data analyst:
  - Key wins/losses
  - Likely drivers + hypotheses
  - Risks and anomalies to validate
  - Recommended next actions + follow-up questions

---

## Great for

- Weekly business reviews (WBR)
- Exec summaries and stakeholder updates
- Experiment readouts (before you write the slide)
- “Why did this number move?” triage

---

## Suggested input format

You can paste KPIs as:
- a small table (Metric | Current | Previous | Target)
- bullet points
- CSV-like text

**Example**
Metric: Activation Rate | Current: 21.4% | Prev: 19.8% | Target: 22%
Metric: DAU            | Current: 142k  | Prev: 151k  | Target: 155k
Context: New onboarding flow launched mid-week; paid spend reduced 15%.

---

## Output structure (example)

- **Headline summary** (1–2 sentences)
- **What moved** (top changes, magnitude, direction)
- **Why it might have moved** (ranked hypotheses)
- **Checks to run** (segments, channels, cohorts, data quality)
- **Actions** (ship/iterate/investigate + owners)
- **Questions for stakeholders** (what info would confirm the story)
