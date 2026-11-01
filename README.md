# Frayt (فراطة)

**A digital coin-change wallet concept for Jordan's cash economy.**
Entrepreneurship project: problem research, business model, and an interactive prototype.

**Prototype:** [Frayt — فراطة](https://frayt.netlify.app/) (demo OTP: `1234`)

**Project status:** Academic concept and interactive prototype. Frayt is not a production application and does not process real money. The CBJ e-wallet licence, payment-system integrations, POS integration, and native iOS/Android apps described in the report are plans, not implemented features.

## Overview
When people in Jordan pay with cash, they often receive small coin change (e.g. 0.05 or 0.10 JOD) that is lost, ignored, or left behind. Merchants, in turn, regularly run out of coins. Frayt proposes converting that change into digital value at the point of purchase.

This project was completed for the **Entrepreneurship Bootcamp (Section 3, Spring Semester 2026)** by Group Al-Ashira. It covers sector analysis (FinTech), PEST and SWOT analysis, user research, personas, value proposition, a prototype with a testing cycle, market sizing, competitor analysis, marketing, and financial projections.

## The Problem
From the team's survey (60 responses: 43 consumers, 4 merchants, 3 finance/fintech professionals, 10 other):

- 69.8% of consumers said they lose or forget their coin change "often" or "almost every time".
- 39.5% had been in a situation where a merchant could not give the right change.
- Consumers estimated losing about 2.29 JOD per month on average.
- Merchants (n=4) reported spending 1–6 hours per week handling coins.

The research also showed the frustration is mostly about inconvenience (coins are heavy, noisy, and useless digitally) rather than the monetary value itself.

## The Proposed Solution
1. The customer pays cash and is owed coin change.
2. The cashier enters the total and the amount paid; the app calculates the change and shows a **single-use QR code**.
3. The customer scans the code and the exact change is credited to their Frayt wallet.
4. The balance can be saved, used to pay bills, and redeemed for rewards. The report also plans transfers, withdrawals, and donations.

Frayt is free for consumers. The planned revenue comes from merchants (subscription, ~1% transaction fee), float income (~3% per year on held balances), and partnerships/promotions.

## Prototype
An interactive **mobile web app** covering both sides of the transaction. It simulates the experience; it does not move real money.

**Customer side**
- Wallet home screen with balance, reward points, and recent transactions
- Scan-to-collect change via merchant QR code, with a confirmation animation
- Savings jar that automatically receives a portion of collected change
- Reward points per transaction (redeemable for items such as vouchers or donations)
- Pay with Frayt: 12 billers in the prototype (e.g. JEPCO, IDECO, Miyahuna, Yarmouk Water, Zain, Orange, Umniah), with saved billers
- Bilingual interface (Arabic / English)

**Merchant side**
- Enter transaction total and amount paid; change is calculated automatically
- Unique, single-use QR code generated per transaction
- Daily counter of QR codes scanned and total change


### Planned, not implemented
Real payment processing, CBJ e-wallet licence, eFAWATEERcom and JoPACC open-finance integration, POS integration, iOS/Android apps, wallet transfers and cash withdrawal, and the proposed ride-hailing (e.g. Uber) integration.

## Testing & Refinement
Testing used a think-aloud session with 4 consumers (ages 20–24) and walkthroughs with 2 merchants (a café owner and a grocery cashier). This was a very small sample, so the findings are directional.

**What was observed**
- 3 of 4 consumers completed their first scan without help; one mistook the QR icon for a generic scanner.
- One consumer was unsure where a small amount went when the savings jar took its share.
- 3 of 4 consumers asked whether Frayt is regulated and safe.
- Paying part of a bill from small balances got the strongest positive reaction.
- Merchants generated a QR in about 10–30 seconds. Both got stuck when a customer didn't have Frayt.

**Refinements made**
- The bare QR icon was replaced with a labelled "Scan to receive change" action.
- The post-scan screen now shows the split between spendable balance, savings jar, and reward points, with no auto-dismiss.
- A tappable trust indicator on the home screen opens a short FAQ (regulation, savings split, single-use QR).
- A skip button and a one-line cashier script were added for customers without Frayt.

## Key Research Findings (consumer survey, n=43)
- 86% rated the idea of digital change 4 or 5 out of 5.
- 74.4% said they would try Frayt (4 or 5 out of 5).
- 65.1% would be more likely to use it if regulated by the Central Bank of Jordan.
- 69.8% rated "free for consumers" as important (4 or 5 out of 5).
- The top concern (48.8%) was that not enough merchants would use it.

## Business Model & Financial Projections
These are **projections based on the team's assumptions**, not results.

| Estimate | Annual value |
|---|---|
| TAM: coin change unused by cash-using adults in Jordan | ~145.6M JOD |
| SAM: wallet owners Frayt can reach | ~71.2M JOD |
| SOM: 20% of SAM | ~14.2M JOD |

- **First-year budget:** 123,100 JOD, funded by 25,000 JOD from the founders and 100,000 JOD of seed investment.
- **Break-even:** about 112 active merchants (fixed costs 46,700 JOD per year; ~540 JOD revenue and ~120 JOD variable cost per merchant per year).
- **Projected net income:** about −19,600 JOD (Year 1), +39,600 JOD (Year 2), +123,700 JOD (Year 3).


## Limitations
- The prototype is a simulation; no licensed payment infrastructure or real transactions are involved.
- Survey and testing samples are small (merchants n=4 in the survey, n=2 in testing).
- Market size and financial figures depend on stated assumptions.

## Team
Group Al-Ashira: Mohammed Al-haj, Mohammad Aldeghemat, Osamah Alsaghir, Salaheddin Alreemawi

## Project Information
- **Project Type:** Academic Project
- **Course:** Entrepreneurship Bootcamp
- **Semester:** Spring 2026

## License
© 2026 Group Al-Ashira. All rights reserved.
