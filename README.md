# AGI Timeline — Job Displacement Scenario Model

**Live site:** [jacobjake1.github.io/agi-timeline](https://jacobjake1.github.io/agi-timeline/)

An interactive scenario model exploring what US job displacement could look like after AGI/ASI-level capability is publicly deployed. This is a reasoned "what if" built from real signals — not a forecast, not a calculation with verified inputs. Every number below is either sourced (marked) or an assumption I chose to make the model run (also marked). Treat it as a way to think about scale and sequencing, not a prediction to plan around.

---

## What this models

- **Wave 1 — Cognitive displacement** (Day 1 through Month 9): knowledge work, white collar, professional services, logistics, transportation, engineering, government, retail — under the assumption that AGI-level capability is available and adopted.
- **Wave 2 — Humanoid robot & autonomous vehicle wave** (Month 6–18): physical labor and driving roles, under the assumption that robot deployment scales rapidly once cost/capability thresholds clear — which is already happening in early form (real, named pilots: BMW, Mercedes, Amazon, GXO Logistics).
- **Productivity multiplier (assumption, not measured):** Wave 1 ÷5.0 — modeling one person + AGI tools doing roughly the work of 5 knowledge workers, so companies shrink via non-replacement rather than direct firing. Wave 2 ÷1.5 — physical deployment is more capital- and hardware-constrained, so the multiplier is smaller.
- **Cascade Lost (assumption):** every direct job eliminated is modeled as removing ~0.55 additional downstream jobs through reduced local spending. This ratio is a reasonable estimate based on how spending-multiplier effects work in recessions generally — it is not a number specific to AI displacement that's been independently verified.

---

## Core assumptions — clearly labeled as assumptions

- **AGI arrival window: 2027–2029, with 2028 as the most-cited single year.** This reflects public statements from people like Dario Amodei and other AI researchers, not a consensus forecast. Treat it as "informed guess from people close to the work," not fact.
- **AGI → ASI gap:** modeled as very short (the recursive self-improvement argument — a system that can improve itself has no obvious ceiling). This is a real, seriously-discussed possibility in AI safety circles, not a settled timeline. I'm modeling the fast case, not asserting it's certain.
- **ASI deployed at full capability day one, no ramp-up** — a simplifying assumption to make the model tractable. Real deployment would almost certainly be more gradual and uneven across companies and sectors.
- **30-day immediate displacement window for Wave 1** — modeling the fastest plausible case (contract non-renewals, hiring freezes converting to cuts) rather than a measured average.
- **US workforce baseline: 160M** — close to actual BLS civilian labor force figures, used as the denominator for percentage calculations.
- **Cascade multiplier ×0.55** — see above, reasonable estimate, not independently verified for this specific scenario.

---

## Real, sourced signals this model is responding to (as of June 2026)

- SHRM survey (20,000+ workers, Mar 2026): 15.1% of US employment already has 50%+ of tasks automated.
- 88,000+ AI-attributed layoffs in 2026 YTD — already exceeding all of 2025 (Challenger, Gray & Christmas).
- S&P 500 companies cut 400,000+ roles in the past year — first annual employment decline since 2016.
- Real, named humanoid robot deployments: BMW, Mercedes-Benz, Amazon, GXO Logistics.
- Anthropic's own published capability data: large theoretical task coverage across most occupational categories, much smaller observed usage so far — the gap between what's possible and what's deployed is real and wide right now.

These are the reasons the scenario is worth building. They are not proof the specific percentages and dates below are correct.

---

## The headcount compression argument (reasoning, not a measured mechanism)

The logic: if one person with strong AGI-class tools can do the work that previously took a team, companies don't need to fire people loudly — they just stop backfilling roles when people leave or contracts end. Headcount shrinks through attrition rather than headline layoffs. Once the cost/quality math clearly favors automation for a given role, competitive pressure pushes every company in that sector toward the same decision within a similar window, because no single company can afford to keep a cost structure its competitors have already shed. This is sound economic reasoning. It is not a verified, measured pattern with a known speed — "within one or two quarters" is a plausible guess about competitive dynamics, not a timed mechanism.

---

## What this doesn't model

Jobs that plausibly survive and increase in relative value: live officiating, coaching, physical presence roles, creative arts, anything where the value is specifically that a human is doing it. These aren't modeled with numbers because their resilience is about why people value them, not a quantifiable automation percentage — putting a precise number on that would be the same overconfidence problem the rest of this README is trying to avoid.

---

## Sectors covered (v5)

| Sector | Notes |
|---|---|
| **Mid & Senior Management** *(added v5)* | Middle managers, operations managers, directors, VPs, department heads |
| Knowledge Work & Office | 32 roles including management analysts, telemarketers, grant writers |
| Software & Tech | Junior through senior, DevOps, cybersecurity |
| Media, Creative & Marketing | UX/UI, animators, voice actors, fashion/interior designers |
| Finance & Banking | Tellers through actuaries, mortgage brokers, title examiners, underwriters, loan processors, stockbrokers |
| Transportation & AV | Taxi, rideshare, bus drivers, school buses, subway, last-mile delivery |
| Engineering & Technical | CAD drafters, industrial/mechanical/electrical engineers, cost estimators |
| Food Service & Hospitality | Chain through fine dining |
| Healthcare (Cognitive) | Radiology, pathology, diagnostic roles, sonographers, medical scribes, vet techs, OT assistants |
| Legal & Professional Services | Document review through architects |
| Education & Training | Test prep through K-12 standardized content, academic research assistants |
| Retail & Customer-Facing | Inside and outside sales, real estate |
| Logistics & Warehousing | Dispatchers through airline pilots |
| Government & Public Sector | Admin, DMV, benefits case workers, 911 dispatchers, court clerks, customs agents |
| Personal Services & Wellness | Trainers, coaches, security monitoring |
| Robot & AV Wave | 18 physical roles including hotel housekeeping, phlebotomists, dental hygienists |

*(Note: the specific percentages assigned to individual roles within each sector are estimates for scenario-building purposes — useful for seeing relative ordering and scale, not precise forecasts for any specific job title.)*

---

## Changelog

| Version | Changes |
|---|---|
| **v5** | New sector: Mid & Senior Management (~3.8M). Cascade Lost and Total Effective stats added. Finance: insurance underwriters, loan processors, stockbrokers. Healthcare: medical scribes, vet techs, OT assistants. Government: 911 dispatchers, court clerks, customs agents. Education: academic research assistants. Estimate adjustments: school bus drivers 68%→38%, dentists 46%→22%. |
| v4 | 2 new sectors (Transportation & AV, Engineering & Technical). 40+ new roles added across all sectors. |
| v3 | Split multiplier system (Wave 1 ÷5.0, Wave 2 ÷1.5). "To Run Economy" stat. Stats row layout fixed. |
| v2 | 15 new job categories. Multiplier reframed from spending collapse to non-replacement productivity amplification. Stats expanded. |
| v1 | Initial release. 12 sectors, 80+ roles, four-line macro chart, humanoid robot wave, singularity annotation. |

---

## More to come

This is the first in an ongoing series tracking the AI displacement story in real time — as real data comes in, I'll update the sourced sections above. The scenario sections will get revised too, as the assumptions get tested against what actually happens.

---

*Built by Jacob. Tracking this since before most people were paying attention — trying to stay honest about what's known vs. what's a reasoned guess along the way.*
