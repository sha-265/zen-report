# ZEN Report 📊

A lightweight, browser-based pricing calculator for estimating the cost of ZEN.com Individual plans based on the published pricing document.

This single-page tool compares annual costs across ZEN's Good, Better, Best, and Zen plans using your expected transaction volumes, service usage, and pricing assumptions.

## ✨ What this tool does

- Compares estimated costs across ZEN plans
- Models funding, top-up, and transfer fees
- Includes currency exchange, cash withdrawal, and ATM assumptions
- Estimates optional cashback and Reward Zone credits
- Lets you adjust annual amounts, transaction counts, and variable rate assumptions
- Shows a plan-by-plan comparison and detailed cost breakdown

## 🧮 Included in the calculator

- Funding and top-up methods
- Transfers and local payment fees
- Currency exchange assumptions
- Cash and ATM costs
- Card-related charges and plan benefits
- Account maintenance and exceptional-case scenarios
- Optional cashback and Reward Zone estimates

## 🚀 Quick start

1. [Download the source ZIP](https://github.com/sha-265/zen-report/archive/refs/heads/main.zip).
2. Extract the ZIP file, keeping the project folders together so the `css/` and `js/` files remain alongside `zen_pricing_calculator.html`.
3. Open `zen_pricing_calculator.html` in a modern web browser to run the calculator. No build step or dependencies are required.
4. Enter your expected values and transaction counts, adjust any assumptions, and review the plan comparison and cost breakdown.

## 📝 Notes

- The calculator is based on the published ZEN Individual pricing PDF. Check the current official document for the latest fees and terms.
- Some charges depend on country, provider, or in-app quotes, so the calculator uses editable assumptions where appropriate.
- The calculator runs client-side in your browser; your inputs are not uploaded to a server.

## ✅ TODO

- [ ] Add an option to upload a ZEN account statement and automatically calculate fees for all plans. This option is not currently available because ZEN statements do not include transaction types, which are needed to determine the applicable fees.

## 📌 Source and licensing

- Official ZEN pricing source: [ZEN Individual Customer pricing PDF](https://www.zen.com/files/pricing/new_individual_pricing.pdf)
- Project license: GNU General Public License v3.0

## 💡 Use case

Estimate potential costs for ZEN Individual plans before choosing a subscription or compare plans based on your expected usage.
