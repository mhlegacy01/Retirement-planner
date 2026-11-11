# MH Retirement Planner v1.3.1

## UX updates
- Retirement Lifestyle section moved directly after EPF Information and before PRS Information, so the user can enter retirement income and assumptions without scrolling past PRS/Cash.
- Preserved natural keyboard Tab order through the visible configuration fields.
- Added `enterkeyhint="next"` for mobile keyboards and Enter-to-next-field behavior for keyboard users.
- PRS and Cash Investment remain optional. Blank balances/contributions are treated as RM0; blank PRS/Cash pre-retirement return assumptions are treated as 0%.
- Retirement age remains 60 by default. Other financial inputs remain blank with grey example placeholders.

## Deploy
Replace the existing root `index.html` in `mhlegacy01/Retirement-planner` with this `index.html` and commit to `main`.

This is an illustrative prototype. Validate calculation methodology, official EPF/KWSP and PRS rules, tax treatment, fees and product-specific assumptions before client use. Returns are assumptions, not guarantees.
