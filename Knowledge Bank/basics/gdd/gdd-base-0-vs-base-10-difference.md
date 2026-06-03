---
question: What is the difference between GDD base 0 and base 10?
category: Basics
subcategory: GDD (Growing Degree Days)
tags: [gdd, base-temperature, pgr-timing, calculation]
products: [NZLA PGR, NZLA Paclo]
related: [gdd-basics, pgr-application]
---

# What is the difference between GDD base 0 and base 10?

Different base temperatures for different applications.

GDD calculation takes daily mean temperature minus a base temperature. If positive, add to the running total. The base is the temperature below which the process you're tracking doesn't happen.

**Base 0°C.** Used for general growth tracking and trinexapac-ethyl (NZLA PGR) re-application timing. Counts every degree of warmth above freezing. Standard reference for cool-season turf development. A typical NZ spring day with mean temperature 12°C contributes 12 GDD base 0.

**Base 10°C.** More conservative — counts only warmth above 10°C, which is closer to the actual threshold where cool-season grass growth starts firing properly. A 12°C day contributes 2 GDD base 10. A cool spring day at 8°C contributes nothing.

Why the difference matters in practice:

For PGR re-application, base 0 is the standard because trinexapac metabolism in the plant tracks all temperature contributions, not just temperatures above the growth threshold. Standard re-application interval is roughly 200 GDD base 0 for ryegrass and 150 to 200 GDD base 0 for warm-season turf, depending on rate.

For warm-season pest emergence and warm-season disease prediction, higher base temperatures (15°C or higher) are sometimes used because the pathogens or pests don't develop below those thresholds.

For most NZ home lawn use, GDD is overkill — calendar plus soil temperature works fine. For fine turf and sports turf running tight PGR programmes, GDD base 0 is the working unit.

Online tools and weather apps for your region will give GDD totals if you want to track them. Calculate from daily mean temperatures (not minimum or maximum alone).

The practical takeaway: when reading PGR timing recommendations, check which base temperature the recommendation uses before applying. Mixing the two leads to mistimed applications.
