# MH Retirement Planner v1.0 prototype

## Run
Open `index.html` in a modern browser. An internet connection is required to load Chart.js from its CDN.

## Included in this first prototype
- Simple two-column dashboard: configuration on the left, projection and results on the right.
- EPF automatic contribution estimate or manual combined monthly contribution.
- Combined PRS balance and monthly/annual contribution inputs.
- EPF and PRS accumulation projections.
- Retirement drawdown projection with inflation-adjusted monthly withdrawals.
- Bright blue EPF, sunny yellow PRS and coral retirement utilisation bars.
- Capital Intact and Capital Liquidation indicative estimates.

## Important limitations
This is a visual and calculation prototype, not a production-ready financial planning tool.
- EPF is currently modelled as one combined balance. Account 1/2/3 balances, official contribution tables by salary/age/member category, contribution allocation, and official dividend calculation conventions are not yet implemented.
- PRS is modelled as one combined balance; fees, fund-specific returns and withdrawal rules are not modelled.
- Retirement drawdown uses a simplified blended monthly return.
- No tax, fees, volatility, sequence-of-returns risk, other income, or statutory withdrawal eligibility is modelled.
- Assumptions are editable and returns are not guaranteed.

The next development step should be to validate and improve the calculation engine before production use.
