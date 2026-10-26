<div align="center">

<img src="assets/finarez/logo.svg" alt="Finarez logo" width="96" height="96">

# Finarez

**Your money, clear and in order.** Personal finance for Colombia and México, in Spanish.

[finarez.app](https://finarez.app) · [Features](#features) · [Credits](#credits) · [License](#license)

![License: proprietary](https://img.shields.io/badge/license-proprietary-152c5b)
![TypeScript 6](https://img.shields.io/badge/TypeScript-6-3178c6?logo=typescript&logoColor=white)
![Node 24](https://img.shields.io/badge/Node-24-5fa04e?logo=nodedotjs&logoColor=white)
![React 19](https://img.shields.io/badge/React-19-61dafb?logo=react&logoColor=black)
![Hono 4](https://img.shields.io/badge/Hono-4-e36002?logo=hono&logoColor=white)
![PostgreSQL 18](https://img.shields.io/badge/PostgreSQL-18-4169e1?logo=postgresql&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-f38020?logo=cloudflare&logoColor=white)
![Platform: web and PWA](https://img.shields.io/badge/platform-web%20%7C%20PWA-9abeff)

</div>

Finarez keeps accounts, income and expenses, transfers, budgets, savings goals, debts and net worth in one place, with exact money in every currency it supports (COP, MXN, USD, EUR). It is a public, multi-user web app: each person's data is isolated in the database itself, not only in the code. It is live at [finarez.app](https://finarez.app) and still in development.

<p align="center">
  <img src="assets/finarez/desktop-dashboard.png" alt="Home dashboard: available balance, accounts, the month's income and expenses, budgets and upcoming payments" width="100%">
</p>

<table>
  <tr>
    <td width="50%"><img src="assets/finarez/desktop-reports.png" alt="Reports: income, expenses and savings for the last 12 months, with a monthly chart"></td>
    <td width="50%"><img src="assets/finarez/desktop-net-worth.png" alt="Net worth: what you own and what you owe at the close of each month"></td>
  </tr>
  <tr>
    <td><img src="assets/finarez/desktop-savings.png" alt="Savings goals with progress and the monthly amount needed to arrive on time"></td>
    <td><img src="assets/finarez/desktop-dashboard-dark.png" alt="The home dashboard in the dark theme"></td>
  </tr>
</table>

<p align="center">
  <img src="assets/finarez/phone-dashboard.png" alt="Home dashboard on a phone" width="30%">
  &nbsp;
  <img src="assets/finarez/phone-new-transaction.png" alt="Recording an expense on a phone" width="30%">
  &nbsp;
  <img src="assets/finarez/phone-savings.png" alt="Savings goals on a phone" width="30%">
</p>

<sub>Screenshots of the local app with a synthetic demo year (no real person's data).</sub>

## Features

- **Accounts and movements:** bank accounts, cash, wallets, investments and credit cards; income, expenses and transfers, including between currencies with the day's exchange rate. A movement can be split across several categories and tagged; the description is optional, and a movement that looks already recorded asks before saving.
- **Reconciliation:** check an account against a bank statement's closing balance, with an explicit adjustment for any difference, and undo it.
- **Home dashboard:** what is available today, net worth, the month's income and expenses, budgets and upcoming payments.
- **Budgets** per category and period, and **savings goals** that earmark money in real accounts, record the interest they earn and say how much to set aside each month.
- **Debts:** loans and credit cards, each payment split into interest and principal, and a payoff planner.
- **Recurring movements** and a **payment calendar** of what is coming: debt payments, card cut-offs, recurring items and budgets near their limit.
- **Bank statement import** from CSV, XLSX and XLSM, with a review step before anything is saved.
- **Reports** and **net worth** over time, with CSV export; Patrimonio shows liquidity (months of spending covered), what you own by type and how much changed in value.
- **Investments (Premium):** holdings in investment accounts (stocks and ETFs, funds, fixed income, crypto), buys, typed prices, FIFO sales with realized and unrealized gains kept apart, and dividends.
- **Annual tax summaries** for Colombia (DIAN) and México (SAT, with each personal deduction's own cap and the general one), as Premium: reviewed figures for an accountant, not a tax return.
- **Your data:** a full export as CSV files in a ZIP, and account deletion with the password.
- **Sign-in** with email verification and optional two-step verification (authenticator app and backup codes).
- **Country of residence at sign-up** with the legal texts and consent of that country (Colombia open; México after its legal review).
- Light and dark themes, installable as an app on phones, Spanish first.

## Credits

Built on [Hono](https://hono.dev), [React](https://react.dev), [React Router](https://reactrouter.com), [Vite](https://vite.dev), [Drizzle ORM](https://orm.drizzle.team), [node-postgres](https://node-postgres.com), [Better Auth](https://better-auth.com), [Zod](https://zod.dev), [i18next](https://www.i18next.com), [Lucide](https://lucide.dev) icons, the [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) typeface, [Biome](https://biomejs.dev), [Vitest](https://vitest.dev), [Playwright](https://playwright.dev) and [dependency-cruiser](https://github.com/sverweij/dependency-cruiser). Hosted on [Cloudflare Workers](https://workers.cloudflare.com) with [Neon](https://neon.tech) PostgreSQL; email by [Resend](https://resend.com); backups encrypted with [age](https://age-encryption.org).

## License

Proprietary. Copyright © 2026 Finarez. All rights reserved: no part of this repository may be copied, modified or distributed without written permission.
