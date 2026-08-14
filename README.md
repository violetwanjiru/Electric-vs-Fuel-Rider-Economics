
# Rider Economics: Electric vs ICE Motorcycle Taxis in Nairobi

## Goal of the Project

The goal of this project is to determine whether electric motorcycles offer better economics than petrol (ICE) motorcycles for boda boda riders in Nairobi, and to identify the specific factors driving any difference. The analysis is intended to help e-mobility operators make an evidence-based case for—or against—electrifying their fleets.

## Background

Nairobi's boda boda sector is one of Africa's fastest-growing electric vehicle segments, but the economic case for individual riders is not yet settled. Electric motorcycles carry a higher upfront cost, and whether that premium pays back depends on day-to-day operating economics that most public commentary does not examine closely.

This project uses real GPS-tracked trip data and daily financial survey data from **120 Nairobi riders**, collected across a controlled transition study, to answer that question directly.

## Objectives

1. Compare daily profit, cost structure, and unit economics between Electric and ICE (Control) riders operating in the same time period.
2. Identify the underlying driver of any profit gap—whether it stems from cost, revenue, or utilisation—rather than reporting the gap alone.
3. Translate the findings into a clear investment case: does the electric premium pay back, and if not yet, what would need to change?

## Dataset Structure

The data consists of two linked sources per rider group (ICE Baseline, ICE Control, Electric):

* **GPS-derived trip-level records:** distance, duration, speed, idle time, and timestamps.
* **Daily financial survey records:** revenue, maintenance cost, and fuel or battery-swap cost.

**Source:** [Nairobi Motorcycle Transit Comparison Dataset](https://data.mendeley.com/datasets/nv3rkn24zv/1), Mendeley Data (2023).

Because financial figures were collected via daily phone survey, a subset of records contained internally inconsistent values—for example, a rider logging zero revenue on a 90 km tracked trip, or a fuel cost inconsistent with distance travelled.

These records were identified through a systematic consistency-check process and corrected using defensible estimation methods, including fuel-consumption benchmarks for ICE and published battery-swap pricing for Electric. Records were corrected rather than removed, preserving sample size while accounting for known survey error.

## Insights Summary

### Key Metrics

To evaluate rider economics, the analysis focused on the following metrics:

* **Daily Profit:** Average net earnings per rider per day, after energy/fuel and maintenance costs.
* **Profit per Kilometre:** Unit-level economics, isolating efficiency from how much a rider chose to drive.
* **Cost Structure:** Revenue, energy cost, and maintenance cost per kilometre, compared side by side.
* **Utilisation:** Average distance driven per day, used as a proxy for how intensively each motorcycle is being used.

### Daily Profit

* ICE (Control) riders average **KES 996/day** in profit, versus **KES 837/day** for Electric riders—a gap of **KES 159/day**.
* Electric's profit distribution is tighter at the low end, with a minimum of **KES 50** versus **-KES 8,800** for ICE. This suggests more consistent, lower-risk earnings even though the average trails ICE.

### Unit Economics: Cost per Kilometre

* Electric's energy cost per kilometre (**KES 3.65**) is **40% lower** than ICE's fuel cost per kilometre (**KES 6.11**).
* Electric's maintenance cost per kilometre (**KES 0.32**) is **81% lower** than ICE's (**KES 1.72**).
* Despite Electric's lower revenue per kilometre (**KES 15.16 vs. KES 19.50**), profit per kilometre is nearly matched: **KES 11.18 for Electric vs. KES 11.68 for ICE**, a gap of only **KES 0.50/km**.
* This indicates that the daily profit gap is **not primarily a cost-efficiency problem**. Electric's lower operating costs have already absorbed almost all of its revenue disadvantage at the per-kilometre level.

### Utilisation

* Electric riders covered **75 km/day** on average, compared with **85 km/day** for ICE (Control)—a **12% shortfall**.
* Given that profit per kilometre is nearly identical between groups, this utilisation gap is the primary explanation for the remaining daily profit difference, rather than a structural disadvantage in the vehicle's economics.

### Profit Margin

* Electric riders retain **73.8%** of revenue as profit, compared with **59.9%** for ICE (Control).
* This difference is a direct result of Electric's lower operating cost base.

## Recommendations

* **Prioritise utilisation over cost reduction.** Since Electric's unit economics already rival ICE's, further subsidising energy or maintenance costs is likely to yield limited additional benefit. The higher-leverage intervention is increasing electric riders' daily distance toward the **85 km/day** benchmark set by ICE riders.

* **Investigate the utilisation gap directly.** Determine whether Electric's lower daily distance stems from range or charging/swap-station constraints, route assignment, or a rider learning curve. Each cause implies a different operational response, from infrastructure investment to route optimisation or onboarding support.

* **Use profit-per-kilometre, not daily profit, as the primary fleet-comparison metric.** Daily profit is sensitive to how much a rider chooses or is able to drive. Profit-per-kilometre isolates the vehicle's underlying economics and is therefore a fairer basis for an electrification business case.

* **Treat findings as directional, not conclusive.** Only **9 electric motorcycles** were tracked against **100+ ICE motorcycles**. A larger and longer-running electric cohort is needed before these findings can inform a large-scale fleet decision.

* **Expect the investment case to strengthen with utilisation.** Given the near-parity in unit economics, improvements in electric riders' daily distance should translate into closing the remaining daily profit gap and, consequently, shortening the payback period on the vehicle's upfront premium.

## Dashboard

The interactive dashboard is available in [Power BI](https://app.powerbi.com/groups/me/reports/b1f33b6b-4aab-4632-84c2-28179bfcfe60/e998a456027756bbd04d?experience=power-bi).

The dashboard allows users to:

* Filter results by motorcycle type.
* Explore an interactive payback calculator.
* Compare daily profit.
* Analyse unit economics.
* Examine utilisation.
* Explore profit distributions across rider groups.
