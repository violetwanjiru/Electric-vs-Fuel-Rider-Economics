# Should a Nairobi boda boda rider switch from petrol to electric?

**[View the live dashboard]([https://YOUR-USERNAME.github.io/Electric-vs-Fuel-Rider-Economics/](https://violetwanjiru.github.io/Electric-vs-Fuel-Rider-Economics/))**

Not yet, on daily profit. Electric riders in this study earn KES 837 a day against KES 996 for petrol riders, a gap of KES 159, and the whole gap comes from distance: electric riders drive 75 km a day against 85 km. Per kilometre the two are nearly level, at KES 11.18 for electric and KES 11.68 for petrol, so the switch pays only if a rider can cover about 89 km a day.

The data covers 120 riders in Nairobi from a 2023 study, drawn from GPS trip records and daily financial surveys. Amounts are in Kenya shillings (KES).

## What the data shows

| Area | Finding |
|---|---|
| Daily profit | Petrol KES 996, electric KES 837. The middle half of electric riders earns KES 462.50 to 1,137.50 a day (median 792.50), and petrol riders KES 500 to 1,467 (median 900). |
| Cost per kilometre | Electric spends KES 3.65 on energy against 6.11 for petrol (40% lower) and KES 0.32 on maintenance against 1.72 (81% lower). Its profit margin is 73.8% against 59.9%. |
| Revenue | Petrol riders earn KES 19.50 a kilometre against 15.16 for electric, which offsets petrol's higher costs and leaves profit per kilometre within KES 0.50. |
| Distance | Electric riders drive 75 km a day against 85 km. Daily profit rises with distance for both types at a similar pace. |

## Approach

The dashboard was first built in Power BI and rebuilt here as a static page from the same figures. Three decisions shaped the numbers:

- **Per kilometre, not per day.** Daily profit depends on how much a rider chooses to drive, so I compared fleets on profit per kilometre and then asked what distance closes the daily gap.
- **Inconsistent survey figures were corrected, not deleted.** Where a survey was inconsistent, such as zero revenue on a 90 km trip, I corrected it using fuel-consumption benchmarks and published battery-swap prices.
- **Extreme values stayed in.** A few remain in the petrol group, as low as KES -8,800 a day, so I report quartiles and medians next to averages.

The break-even distance is derived: petrol's KES 996 a day divided by electric's KES 11.18 a kilometre gives about 89 km.

## Recommendations

1. **Riders: switch to electric only if your routes let you cover about 89 km a day with a swap station on the way.** Below that, petrol still earns more today. The dashboard has a calculator to test your own daily distance.
2. **Operators: before the next fleet purchase, get swap-station and charging records for the tracked electric riders.** Electric riders drive 10 km a day less, and the cause could be battery range, swap-station access, route assignment or a learning curve. Each needs a different fix.
3. **Compare fleets on profit per kilometre, not daily profit, until the cause is known.** Daily profit mostly reflects how far a rider drives.

## What this data cannot tell you

Only 9 electric motorcycles were tracked against more than 100 petrol ones, so treat every finding as directional, including the 89 km break-even. The break-even assumes profit per kilometre holds at any distance and leaves out the upfront price premium of an electric motorcycle, which is not in this data, so it does not show whether the premium pays back.

Revenue and costs come from phone surveys and were partly corrected by estimate. The data covers Nairobi only, from a 2023 study. The dashboard is a static page showing a snapshot of the Power BI figures, not a live connection, and the daily-profit-by-distance lines are approximate readings of the original visual.
