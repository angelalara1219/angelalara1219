# Hi, I'm Angela 👋
 
I work in BSA/AML and financial crimes compliance, and I build small tools that take the busywork out of it.
 
I've spent 15+ years in this field across Chase, PayPal, MUFG Union Bank, Northern Trust, and most recently Bitcoin Depot, a crypto money services business operating in the US, Canada, and Australia. I started there as a senior analyst on a two-person team and grew into Compliance Manager, leading a 6–8 person EDD team. Along the way I owned the EDD and sanctions programs, built our customer risk scoring model, and served as interim ERM lead for just over a year.
 
## What I build
 
Most of my technical work starts with one question: *why are we still doing this by hand?*
 
- **Case deduplication at scale:** A process gap left us with just over 9,000 duplicate and related cases, about a year's worth. I built a Google Apps Script tool, refined with Gemini AI, that flagged duplicates and combined related cases by customer attributes. We QA'd a 10% sample of its output before relying on it, and the backlog was fully cleared.
- **Alert threshold analysis:** Used SQL and Power BI to test where an alert rule should sit. The result was a $12K / 14-day threshold that captured 92.48% of confirmed fraud cases.
- **Customer risk scoring:** Built the risk scoring model for EDD customers across three countries.
- **Screening and onboarding setup:** Configured identity verification in Acuant and Onfido, tuned sanctions screening per jurisdiction in GBG, and helped launch Plaid for EDD.
- **Everyday tooling:** Case triage tools, a multi-country SAR/STR/SMR filing tracker with automated date-stamping, Google Sheets dashboards for scam refunds, and monitoring of our Travel Rule automation for accuracy.

My rule for automation in compliance: let it clear the noise, check its work, and keep people on the judgment calls.
 
## Projects
 
**Monitoring and investigations**

- **[ctr-gto-monitor](https://github.com/angelalara1219/ctr-gto-monitor):** a daily CTR check for a cash-based MSB. It flags single and aggregated cash over $10K, transactions in FinCEN's Southwest Border GTO ZIP codes, and possible structuring under either threshold. A weekly watcher checks the Federal Register for new or reissued GTOs and opens a review ticket instead of changing the ZIP list on its own.
- **[aml-case-dedup](https://github.com/angelalara1219/aml-case-dedup):** a Python rebuild of my case deduplication logic. It normalizes customer data, links customers who share a phone, email, wallet, or name and date of birth, and flags repeat alerts for analyst review.

**Regulatory change tracking**

- **[fincen-advisory-guidance-tracker](https://github.com/angelalara1219/fincen-advisory-guidance-tracker):** a weekly log of FinCEN alerts, advisories, and notices, with the SAR key term for each one pulled into one table, so no one has to dig through page 9 of a PDF.
- **[state-mt-licensing-tracker](https://github.com/angelalara1219/state-mt-licensing-tracker):** a weekly log of state money transmitter licensing changes from NMLS and CSBS, plus a 50-state view of Money Transmission Modernization Act adoption.

The monitoring tools run on **synthetic data**, and the trackers use only public FinCEN, CSBS, and NMLS sources. Nothing comes from a former employer, and no real customer data is ever used.
 
## Tools
 
**Data & automation:** SQL · Python · Google Apps Script · Power BI · Excel / Power Query · Google Sheets · Gemini AI

**Compliance platforms:** Actimize · ComplyAdvantage · Elliptic · GBG · LexisNexis · Acuant · Onfido · Persona · Plaid · FinCEN BSA E-Filing · NMLS

**Workflow:** Jira · Confluence
 
## Credentials
 
- Certified Anti-Money Laundering Specialist (CAMS)
- Elliptic Certified Specialist Investigator
- Member, ACAMS Phoenix Chapter

## Let's connect
 
[LinkedIn](https://www.linkedin.com/in/angela-lara-cams-197b6251/) · angelalara88@gmail.com
 
