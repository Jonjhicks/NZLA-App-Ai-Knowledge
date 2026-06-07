---
title: Growing Degree Days (GDD)
category: Basics
subcategory: GDD
tags: [gdd, growing-degree-days, base-temperature, pgr-timing, pre-emergent-timing]
products: [NZLA PGR, NZLA Paclo, Blockade]
related: [pre-emergents, nzla-application-guide]
---

# Growing Degree Days (GDD)

## What it is

GDD is a measure of accumulated heat over time. Plant development and pest activity track temperature, not the calendar. A cold spring delays everything; a warm one fires it earlier. GDD captures that variability in a number.

The calculation: for each day, take the daily mean temperature minus a base temperature. If the result is positive, add it to the running total. If it's zero or negative (temperature at or below the base), add nothing.

**Example.** Base temperature 0°C, day's mean temperature 12°C: that day contributes 12 GDD. A cold day at 5°C contributes 5 GDD. A day at or below 0°C contributes nothing.

## Base temperatures — why they differ

The base temperature represents the threshold below which the process you're tracking doesn't meaningfully happen.

**Base 0°C** — used for general growth tracking and trinexapac-ethyl (NZLA PGR) re-application timing. Counts all warmth above freezing. A standard spring day at 12°C mean contributes 12 GDD base 0.

**Base 10°C** — more conservative, closer to where cool-season grass growth actually starts firing. A 12°C day contributes only 2 GDD base 10. An 8°C day contributes nothing. Used when you want to track meaningful grass growth rather than all temperature accumulation.

**Base 13°C** — used for pre-em timing on summer annual around the germination threshold for summer grass and crabgrass.

**Why it matters:** when reading PGR re-application recommendations, check which base temperature is being used. Mixing them up leads to mistimed applications.

## Practical uses in turf management

**PGR re-application.** Trinexapac-ethyl (NZLA PGR) typically needs re-applying every 150 to 200 GDD base 0, depending on rate and conditions. Track GDD from the previous application and reapply when you hit the target. More accurate than calendar days because it adjusts for temperature variation between seasons.

**Pre-emergent timing.** Summer grass and crabgrass germinate as soil temperatures reach 12°C. Blockade needs to be in place beforehand. GDD models can help predict when that threshold is approaching in a variable spring.

**Disease prediction.** Some  models use GDD combined with humidity data to predict outbreak windows.

## For most NZ home lawns

GDD is overkill. Calendar plus soil temperature reading works fine for home lawn management. If you're in Northland wondering whether to apply the spring pre-em, checking that soil temperatures are approaching 12°C at 50 mm depth is more useful than running a GDD calculation.

For fine turf professionals, sports turf managers, or anyone running a tight PGR programme across multiple properties, GDD tracking makes programmes more precise and reduces both under- and over-application. Local weather apps and NIWA data for your region can provide GDD running totals if needed.
