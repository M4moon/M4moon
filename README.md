# Hi, I'm Mamoon 👋

I build performance metrics people can act on, and I'm working toward a career, and a PhD, in **sports analytics**.

- 🎮 **Game Producer** at Game District, using player analytics (engagement, retention, progression) to balance games and decide what each release changes
- 🏥 Previously **Business Analyst** at CureMD (US health-tech): Python and SQL pipelines for ~70 CMS quality measures, Power BI performance dashboards, and CDC/WHO growth-percentile benchmarks
- 🎓 **BE Computer Engineering, NUST** (2020–2024). Final year project: IoT sensors and machine learning for predictive maintenance of bridge structures, ranked 4th in the batch

## Research interests

The questions I keep coming back to, and would like to pursue at PhD level:

1. **Crediting individuals for team outcomes.** How much of a club's results can be attributed to one player, and how sure can we be? See [pl-transfer-impact](https://github.com/M4moon/pl-transfer-impact).
2. **Forecasting player development from pre-career data.** When does a model actually beat a simple prior such as draft position? See [cfb-nfl-rookie-model](https://github.com/M4moon/cfb-nfl-rookie-model).
3. **Load and risk from sensor time series.** The same problem my final year project solved for bridges, applied to athlete wearables and GPS data.

## Featured projects

### ⚽ [Premier League transfer impact](https://github.com/M4moon/pl-transfer-impact)
Which £17m+ signings actually made their clubs better? Scores 223 Premier League signings (2016–2023) by **points above replacement**, football's version of baseball's WAR, with 90% bootstrap intervals on every score and rank.
- Team model: club points per game vs. minutes-weighted player quality across 180 club-seasons (R² = 0.81, flagged in the README as partly circular)
- Compares each signing with the incumbent he replaced: 18 of 119 are clearly better, 45 clearly worse, 56 too close to call
- Plain-English write-up: [RESULTS.md](https://github.com/M4moon/pl-transfer-impact/blob/main/RESULTS.md)

`Python` `pandas` `bootstrap` `regression` `FPL / Transfermarkt open data`

### 🏈 [College-to-NFL rookie model](https://github.com/M4moon/cfb-nfl-rookie-model)
Can draft-day information predict which NFL rookies produce and who wins Rookie of the Year? EPA leaderboards for FBS college (2021–2025) and NFL rookies (2022–2026), plus an XGBoost + neural-net ensemble scored with leave-one-class-out backtests.
- Features include college production, combine athleticism, vacated opportunity and scheme fit between college and NFL offenses
- Honest result: so far the model does not beat ranking rookies by draft slot, and the write-up says so
- Plain-English write-up: [RESULTS.md](https://github.com/M4moon/cfb-nfl-rookie-model/blob/main/RESULTS.md)

`Python` `XGBoost` `scikit-learn` `EPA` `nflverse / cfbfastR open data`

## Toolkit

**Analysis:** Python (pandas, NumPy, SciPy), SQL, statistics, regression, time-series analysis, machine learning
**Reporting:** Power BI, dashboards and KPI design, plain-English write-ups
**Product:** requirements and user stories, UAT, working between clinicians, developers and designers

## Get in touch

Open to analyst roles in sports, gaming and product, and to PhD opportunities in sports analytics and applied statistics.

📫 mmamoonkhan.business@gmail.com
