# Financial Freedom Planner

A single-page web app that calculates your debt-to-income (DTI) ratio, recommends a budget-friendly extra monthly payment, and projects how fast you can pay off every debt using the avalanche or snowball method.

## Features

- **Debt-to-income:** back-end DTI (all debt payments ÷ gross income) and housing ratio, graded against common lender guidelines (36% healthy, 43% typical mortgage limit).
- **Recommended extra payment:** based on take-home pay minus essentials and required payments, with Steady (35%), Recommended (60%) and Aggressive (85%) presets plus a custom slider.
- **Payoff strategies:** avalanche (highest rate first) vs. snowball (smallest balance first), with a side-by-side comparison of debt-free date and total interest.
- **Snowball rollover:** freed-up payments roll into the next debt. Optionally pays consumer debt before the mortgage.
- **Dashboards:** stacked balance projection vs. minimums only, this month's payment per debt, payoff order and dates, interest saved.
- **Progress tracking:** log balances monthly and chart real progress against the plan.
- **Warnings:** flags payments that don't cover interest and budgets that run negative.

## Run it

No build step and no dependencies. Open `index.html` in a browser.

### Publish with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your app will be live at `https://<your-username>.github.io/<repo-name>/`.

## Data and privacy

All data stays in your browser's local storage. Nothing is sent to a server. Clearing site data, or opening the app in a different browser or device, starts fresh.

## How the math works

- Interest accrues monthly at APR ÷ 12. Card issuers usually compound daily, so real interest can run slightly higher.
- Minimum payments are held at today's amount as balances fall.
- Mortgage taxes and insurance count toward DTI and your budget but not toward principal.
- Projections stop at 50 years.

## Disclaimer

For planning and education only. Not personalized financial advice.
