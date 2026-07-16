# [Multisig Maintenance & Wind-Down: Moonbeam, Moonriver, and Moonbase July 2026.](https://forum.moonbeam.network/t/multisig-maintenance-wind-down-moonbeam-moonriver-and-moonbase-july-2026/2512)

# [](#p-8119-proposal-xx-status-submitted-multisig-maintenance-wind-down-moonbeam-moonriver-and-moonbase-july-2026-1)[Proposal: XX] [Status: Submitted] Multisig Maintenance & Wind-Down: Moonbeam, Moonriver, and Moonbase July 2026.

Moonbeam Multisig Official Link: [https://multisig.moonbeam.network](https://multisig.moonbeam.network/)

Staging Environment: [https://staging.multisig.moonbeam.network](https://staging.multisig.moonbeam.network/)

## [](#p-8119-abstract-2)Abstract

Following Moonbeam’s July 3, 2026 announcement of GLMR’s migration to Base and the wind-down of the Moonbeam parachain, we request funding to maintain the Moonbeam Multisig (a Safe‑based fork) across Moonbeam, Moonriver, and Moonbase for a final month, **July 1–31, 2026**. Funds cover standard operations plus a user-awareness banner and dedicated support to help signers bridge GLMR and withdraw Safe funds before the service is decommissioned on July 31, 2026.

## [](#p-8119-motivation-3)Motivation

Moonbeam Multisig has been the community’s trusted custody and coordination tool for DAOs, teams, and protocols on Moonbeam networks. With the network winding down, this proposal funds one final month of stable operations plus a clear on-chain banner and dedicated support so signers can safely bridge GLMR to Base and withdraw Safe funds before the July 31, 2026 cutoff, an organized decomission rather than an abrupt shutdown.

## [](#p-8119-project-overview-and-team-experience-4)Project Overview and Team Experience

**What we run:** a production‑grade fork of Safe (frontend, Transaction Service, smart contracts, infra, and monitoring) for Moonbeam, Moonriver, and Moonbase. This final month covers standard operations and coordinated off-boarding only - no new features, upgrades, or integration work.

**Team:** Strategic Lead: Ivan · Product Owner: Eduardo · Project Manager: Anton · Team Lead: Marta · Blockchain Engineers: Nikita, Maksim, Den, Leoni · DevOps: Ilya, Leonid, Felipe · QA: Ricardo. Protofire DAO is an official Safe Wallet Partner, has deployed and maintained Safe instances across 80+ chains, and has delivered prior Moonbeam Treasury grants on time.

## [](#p-8119-rationale-5)Rationale

Prior work is documented in **[Appendix A](https://docs.google.com/spreadsheets/d/1519e-2LrZxs58I3bjkLj4CAj_WXbyIULX5mUZXhcXzA/edit?usp=sharing)** - 45 tickets delivered last semester across Features, Incidents, Updates, and Support. For this final month, the value to the ecosystem is protecting users during the transition: a clear on-chain banner and dedicated support materially reduce the risk of stranded or lost funds as GLMR migrates to Base and the Moonbeam Safe instance is retired.

## [](#p-8119-overall-cost-6)Overall Cost

**Total requested (July 2026, 1 month):** **$4,200.00** (paid in **GLMR/MOVR** using 30‑day TWAP).

**Expected Cost structure:** ~**17% Infra** / **83% Team & Ops**.

> 
• Predicted Infra: **~$700.00**

• Team & Ops: **$3,500.00**

• Total (July 2026): **$4,200.00**

No separate off-boarding fee is requested, banner deployment and support coverage during the bridge window are delivered within this month’s standard Team & Ops scope.

[](#p-8119-use-of-treasury-funds-detailed-explanation-of-use-of-treasury-funds-7)**Use of Treasury Funds** - detailed explanation of use of Treasury Funds

- **Infrastructure & Monitoring (≈15%, ~$625):** AWS (ECS/Fargate, RDS, ALB/WAF, CloudWatch, ElastiCache, S3, ECR, Route 53, Lambda), Sentry error tracking, alerting - kept running through July 31, 2026.

- **Safe Support‑as‑a‑Service (≈85%, ~$3,500):** Incident response and resolution, user support (including dedicated assistance bridging GLMR to Base and migrating Safe funds), deployment of the wind-down banner, QA, and a final report to the Moonbeam Treasury.

**Timeline:** July 1-31, 2026, banner live early in the window, support through July 31, final report shortly after.

[](#p-8119-specifications-8)**Specifications**
Safe Global Licenses describe the third-party software included in our Moonbeam Multisig solution: [Safe{Wallet} - Licenses](https://app.safe.global/licenses) (Web section applicable).

- **Smart Contracts:** Safe core contracts remain deployed/verified on Moonbeam, Moonriver, Moonbase at the current upstream **1.4.x** line. No further upgrades planned given the network’s scheduled wind-down.

- **Frontend:** React/TypeScript app across the three networks; this month’s only frontend change is the wind-down/user-awareness banner.

- **Support:** Existing channels and the public support form ([safe-support.protofire.io](https://safe-support.protofire.io/)), with dedicated support for Safe fund withdrawal.

[](#p-8119-steps-to-implement-9)**Steps to Implement**

- Deploy the user-awareness banner on the Moonbeam Safe UI (Moonbeam, Moonriver, Moonbase instances) communicating the GLMR→Base migration and the July 31, 2026 Safe discontinuation. *(Tracked in ClickUp GSD-13317.)*

- Maintain standard support channels through July 31, 2026 to assist signers bridging GLMR and withdrawing Safe funds.

No further feature, upgrade, or integration work is in scope for this final month.

---

### Reply by _yrn

Hey [@Friedhelm](/u/friedhelm)

With our transition to stablecoin payouts now active, your payout of USD 4,200.00 will be sent as 4,200.00 xcUSDC to your previously provided address on Moonbeam.

The proposal has been submitted on-chain and is awaiting approval from two additional Treasury Council members, which is expected to happen very soon. I will then close the proposal right away and claim the payout for you.

This will mark the final payout. Many, many thanks for your contributions — much appreciated!

Yaron

---
*Generated by Payoutor*
*Proposal ID: 71*
*Beneficiary: 0x4DA9a7f9e2381C0D663116Ed8dE297BAd1DB951c*
*Reward: 4200.00 USDC*
*Submitted by: Yaron*
