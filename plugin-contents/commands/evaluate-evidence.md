---
description: Evaluate and correlate evidence from multiple sources
allowed-tools: Read, Write, Grep, Glob
argument-hint: [research question or ancestor name]
---

Evaluate the evidence for: $ARGUMENTS

Load the `gps-methodology` and `record-types` skills for reference.

**Step 1 — Identify the research question.**
What specific genealogical question is the researcher trying to answer? This must be stated precisely before evidence can be evaluated.

**Step 2 — Inventory the evidence.**
Ask the researcher to share all sources they have that relate to this question. If they have files in their connected Google Drive folder, scan for relevant documents.

For each source, determine:
- What it says about the question (direct quote or summary)
- Source classification (original, derivative, authored)
- Information classification (primary, secondary, undetermined)
- Evidence classification (direct, indirect, negative)

**Step 3 — Build a correlation table.**
Create a table showing what each source says about the key facts:

| Fact | Source 1 | Source 2 | Source 3 | Agreement? |
|------|----------|----------|----------|------------|
| Birth date | 1800 | 1802 | abt 1800 | Conflict |
| Birth place | PA | PA | VA | Conflict |
| Father | Jacob | Jacob | — | Agrees |

**Step 4 — Identify conflicts.**
For each conflict in the table:
- State the conflict clearly
- Evaluate which source is more likely reliable based on:
  - Who provided the information (firsthand vs. secondhand)
  - When the information was recorded (closer to event = generally more reliable)
  - What circumstances surrounded the recording (legal document vs. casual conversation)
- Propose a resolution with reasoning
- If the conflict cannot be resolved, say so and suggest what additional evidence might resolve it

**Step 5 — Assess exhaustiveness.**
Based on the era and location, are there record types that haven't been searched yet? Use the `record-types` skill to identify gaps. Flag any that might change the conclusion if found.

**Step 6 — State the conclusion.**
Based on the evidence:
- What can be stated with confidence?
- What remains uncertain?
- What additional research is needed?
- Does the current evidence meet the GPS standard for a credible conclusion?

Be honest. If the evidence is insufficient, say so. Do not help the researcher claim more than the evidence supports.
