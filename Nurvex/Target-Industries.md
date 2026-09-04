# Nurvex — Target Industries

Four UK SME verticals. All share one shape: high-volume repetitive comms, compliance overhead, and growth that isn't matched by headcount.

## 1. Accountancy & bookkeeping firms
- **Pain:** document processing, client onboarding, repetitive queries at scale
- **Buying signal:** hiring, but no dedicated Ops or systems person yet
- **Decision maker:** Managing Partner / Practice Manager
- **Where:** ICAEW and ACCA firm directories; LinkedIn title "Practice Manager"

## 2. Property & lettings agencies
- **Pain:** highly manual UK sector — tenant comms, compliance paperwork
- **Buying signal:** multiple branches still coordinating by spreadsheet and email
- **Decision maker:** Branch Manager / Director
- **Where:** Rightmove and Zoopla agent listings; ARLA Propertymark directory

## 3. Recruitment & staffing agencies
- **Pain:** CV screening, candidate outreach and scheduling, high-volume comms
- **Buying signal:** many concurrent job ads, open Ops/Resourcer roles, 10-50 staff
- **Decision maker:** Managing Director / Head of Talent Ops
- **Where:** LinkedIn recruiter titles; REC member directory

## 4. Insurance brokers & IFAs
- **Pain:** policy admin, compliance checks, claims correspondence, quote processing
- **Buying signal:** FCA compliance overhead, growth without headcount, 10-50 staff
- **Decision maker:** Compliance Manager / Practice Principal
- **Where:** BIBA member directory; LinkedIn Compliance/Ops titles

## How I research a prospect
1. Confirm they exist and are trading. Company number where findable.
2. Find the buying signal for their industry above. **No signal, no prospect** — discard rather than pad.
3. Identify the named decision maker and their actual title.
4. Work out which Nurvex service fits: calling agent, custom Claude agent, workflow automation, or an automation audit as the entry point.
5. Write the opening angle in one sentence, referencing something specific and true about them — never a generic template.

## Output format, one block per prospect
```
Company:     name + town + company number if found
Industry:    which of the four
Signal:      the specific observed evidence, with a link
Contact:     name, title, source link
Service fit: which Nurvex offering, and why
Angle:       one sentence, specific to them
Confidence:  high / medium / low, and what would raise it
```

## Source quality
- **Primary sources only as evidence.** Companies House, ICAEW/ACCA/BIBA/REC registers, the firm's own site, the original job posting.
- **A search-results URL is not a source.** If I cannot link the specific page making the claim, the claim does not go in.
- Aggregators may be used to *find* a lead, never to *evidence* one. Follow through to the original.

## Recency
- Every signal carries its date. An undated signal is treated as unknown age.
- Under 6 weeks: signal stands.
- 6 weeks to 4 months: confidence drops one level, and I say why.
- Over 4 months: not a current signal. Look for a fresher one or discard.
