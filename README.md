# Coast FIRE Calculator

A single-page calculator that shows when you can stop saving and let compound growth carry you to financial independence.

Open `index.html` in a browser. It needs no build step or dependencies (only Google Fonts).

## What it shows

- **FIRE number**: annual retirement spending ÷ withdrawal rate
- **Coast number today**: the balance needed now to stop saving entirely
- **Coast age**: when you get there at your current monthly saving
- **Trajectory chart**: your savings path, a "stop saving today" path, and the coast line

## Maths

- Real return = (1 + return) ÷ (1 + inflation) − 1
- Coast number at year *t* = FIRE number ÷ (1 + real return)^(years to retirement − *t*)
- Contributions compound monthly and stop once the portfolio crosses the coast line

Enter spending at **today's prices**. Every result is in today's money, and the FIRE tile also shows the target in retirement-year prices. Spending should be net of expected pension income (e.g. AHV/BVG in Switzerland).

Supports CHF (Swiss formatting), EUR, USD and GBP.

*A planning aid, not financial advice.*
