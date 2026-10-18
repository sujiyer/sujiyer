# Hey, I'm Sujatha 👋

I'm a product person.

I started my career in consulting at Accenture in 2011 : five years in the SAP world, sitting between clients who knew their business inside out and technical teams who knew the system inside out, being the person who had to make those two worlds actually talk to each other. It was good work and I learned a lot, but I kept feeling like I was translating without fully understanding the language on either side.

So I went back to school. My Masters in Information Systems in the US was where things properly clicked — I was now sitting in classrooms with real work experience behind me, and suddenly data, product thinking, and technology felt like they were all part of the same conversation I had been trying to have for five years. I was also fortunate enough to be introduced to fintech during that time — not as a career plan, just something I stumbled into and couldn't stop thinking about. The idea that technology could fundamentally change who gets access to financial services stuck with me in a way that hasn't really left.

From there, fintech became the path. Global Payments first, then Fidelity — doing the same bridging work at a different scale. Figuring out where the business problem actually is, figuring out what the technology can realistically do, and sitting in the middle trying to make something useful happen.

---

# Sujatha Iyer

**Senior Systems Analyst | Fintech & AI Governance | Financial Inclusion**

I build open-source frameworks that give financial institutions — particularly smaller credit unions and community banks — a practical starting point for the systems problems they all face but solve separately: how to design financial APIs that interoperate, how to govern AI that makes decisions about people's money, how to measure and address gaps in financial access.

My day job is at Fidelity Investments, where I support research platforms for teams managing $5.4 trillion in assets. The frameworks I publish here generalize what I have learned across 14 years in fintech — at Fidelity, Global Payments, and Accenture — into tools any institution can adopt.

---

## Open-Source Frameworks

### [KYC API Framework](https://github.com/sujiyer/kyc-api-framework)
Standardized API design patterns for financial onboarding and Know Your Customer verification. Built from patterns I developed at Global Payments, where the same framework reduced onboarding friction by approximately 40% and was reused across four product lines instead of being rebuilt each time.

What it covers: parallel verification, progressive verification for thin-file applicants, CFPB Section 1033 open banking integration, BSA/AML compliance requirements, community bank and credit union implementation examples.

### [Fintech AI Governance Framework](https://github.com/sujiyer/fintech-ai-governance-framework)
A portable governance framework for AI systems in financial services. Addresses the gap between regulators requiring institutions to govern their AI (CFPB, SEC, FINRA, OCC have all flagged this) and the absence of a shared, practical standard for how to do it — particularly for smaller institutions.

What it covers : pre-deployment testing protocols, model drift monitoring checkpoints, bias and fairness monitoring, explainability requirements, incident classification and response, audit trail specifications, NIST AI RMF alignment.

### [Financial Literacy Framework](https://github.com/sujiyer/financial-literacy-framework)
Plain-language financial education modules for underserved communities, designed for adoption by credit unions and community banks. Includes a Python tool that scans financial documents and produces a plain-language glossary of financial terms — because financial exclusion is partly a design problem, and design problems are solvable.

What it covers : banking basics, AI in finance (what it means for members when an algorithm makes a decision about them), credit and loans, investing basics, understanding your rights.

### [Financial Inclusion Analyzer](https://github.com/sujiyer/financial-inclusion-analyzer)
Python tool that processes FDIC National Survey of Unbanked and Underbanked Households data and produces charts and a written report. Maps the problem the other frameworks are built to address: where financial access gaps are largest, which communities are most affected, and what scale the problem operates at.

Results: three visualizations (geographic distribution, demographic breakdown, trend analysis) and a Markdown report.

### [Regulatory Change Tracker](https://github.com/sujiyer/regulatory-change-tracker)
Python tool that monitors six U.S. financial regulatory agencies — CFPB, FDIC, Federal Reserve, FinCEN, OCC, NCUA — and produces a structured digest of new rules, guidance, enforcement actions, and proposed rulemaking. Designed for compliance teams, systems analysts, and fintech developers who need to track regulatory change across a fragmented landscape without six manual subscriptions.

---

## How These Frameworks Connect

```
REGULATORY CHANGE TRACKER
  ↓ surfaces new rules and guidance
  ↓
FINTECH AI GOVERNANCE FRAMEWORK ←→ KYC API FRAMEWORK
  ↓ governs AI decisions                ↓ standardizes onboarding APIs
  ↓
FINANCIAL INCLUSION ANALYZER
  ↓ measures the gap
  ↓
FINANCIAL LITERACY FRAMEWORK
  ↓ addresses the gap at the member level
```

The KYC API Framework and AI Governance Framework are designed to work together. Every institution doing KYC verification is using some form of AI or rules engine to make decisions. The API framework standardizes how that process is designed; the governance framework standardizes how the AI inside it is tested, monitored, and kept accountable.

The Regulatory Change Tracker feeds both: when a new CFPB rule changes what Section 1033 requires, or when the OCC publishes new model risk guidance, the governance framework needs to be updated. The tracker surfaces that change before it becomes an enforcement problem.

---

## Writing

I write about the problems these frameworks address — fragmented financial onboarding, AI governance gaps, and what financial access actually looks like from the inside of the institutions that provide it.

**Medium:** [@su9scorpio](https://medium.com/@su9scorpio)

---

## Professional Background

- Senior Systems Analyst, **Fidelity Investments** (current)
- **Global Payments**
- **Accenture**

**Expertise:** API design, systems analysis, AI governance, financial inclusion, regulatory compliance (CFPB, FinCEN, NIST AI RMF, BSA/AML, ECOA)

---

## Professional Affiliations

- **IEEE Senior Member** — granted by peer nomination; held by approximately 10% of IEEE's global membership
- **ACM Professional Member**
- **ISACA Professional Member**
- **NIST Trustworthy AI in Critical Infrastructure Community of Interest**
- ** CRI CyberRisk Institute**

---

## Connect

[LinkedIn](https://linkedin.com/in/sujathaiyer) | [Medium](https://medium.com/@su9scorpio)

## The career in honest terms

- **Accenture (2011–2016)** — SAP implementations, product consulting, learning how large organisations actually work versus how they think they work
- **Masters in Information Systems** — US, went back with work experience and finally found the intersection of data, product and technology that made sense of everything before it. Got introduced to fintech here.
- **Global Payments** — fintech product management, KYC and identity verification at scale, financial inclusion work I genuinely cared about
- **Fidelity Investments** — product strategy on a $5.4 trillion AUM platform, AI governance (the first framework the platform had), figuring out what responsible AI actually means in practice rather than in a slide deck


---

## Open-Source Frameworks

### [KYC API Framework](https://github.com/sujiyer/kyc-api-framework)
Standardized API design patterns for financial onboarding and Know Your Customer verification. Built from patterns I developed at Global Payments, where the same framework reduced onboarding friction by approximately 40% and was reused across four product lines instead of being rebuilt each time.

What it covers : parallel verification, progressive verification for thin-file applicants, CFPB Section 1033 open banking integration, BSA/AML compliance requirements, community bank and credit union implementation examples.

### [Fintech AI Governance Framework](https://github.com/sujiayer/fintech-ai-governance-framework)
A portable governance framework for AI systems in financial services. Addresses the gap between regulators requiring institutions to govern their AI (CFPB, SEC, FINRA, OCC have all flagged this) and the absence of a shared, practical standard for how to do it — particularly for smaller institutions.

What it covers : pre-deployment testing protocols, model drift monitoring checkpoints, bias and fairness monitoring, explainability requirements, incident classification and response, audit trail specifications, NIST AI RMF alignment.

### [Financial Literacy Framework](https://github.com/sujiayer/financial-literacy-framework)
Plain-language financial education modules for underserved communities, designed for adoption by credit unions and community banks. Includes a Python tool that scans financial documents and produces a plain-language glossary of financial terms — because financial exclusion is partly a design problem, and design problems are solvable.

What it covers : banking basics, AI in finance (what it means for members when an algorithm makes a decision about them), credit and loans, investing basics, understanding your rights.

### [Financial Inclusion Analyzer](https://github.com/sujiayer/financial-inclusion-analyzer)
Python tool that processes FDIC National Survey of Unbanked and Underbanked Households data and produces charts and a written report. Maps the problem the other frameworks are built to address: where financial access gaps are largest, which communities are most affected, and what scale the problem operates at.

Results : three visualizations (geographic distribution, demographic breakdown, trend analysis) and a Markdown report.

### [Regulatory Change Tracker](https://github.com/sujiayer/regulatory-change-tracker)
Python tool that monitors six U.S. financial regulatory agencies — CFPB, FDIC, Federal Reserve, FinCEN, OCC, NCUA — and produces a structured digest of new rules, guidance, enforcement actions, and proposed rulemaking. Designed for compliance teams, systems analysts, and fintech developers who need to track regulatory change across a fragmented landscape without six manual subscriptions.

---

## How These Frameworks Connect

```
REGULATORY CHANGE TRACKER
  ↓ surfaces new rules and guidance
  ↓
FINTECH AI GOVERNANCE FRAMEWORK ←→ KYC API FRAMEWORK
  ↓ governs AI decisions                ↓ standardizes onboarding APIs
  ↓
FINANCIAL INCLUSION ANALYZER
  ↓ measures the gap
  ↓
FINANCIAL LITERACY FRAMEWORK
  ↓ addresses the gap at the member level
```

The KYC API Framework and AI Governance Framework are designed to work together. Every institution doing KYC verification is using some form of AI or rules engine to make decisions. The API framework standardizes how that process is designed; the governance framework standardizes how the AI inside it is tested, monitored, and kept accountable.

The Regulatory Change Tracker feeds both: when a new CFPB rule changes what Section 1033 requires, or when the OCC publishes new model risk guidance, the governance framework needs to be updated. The tracker surfaces that change before it becomes an enforcement problem.

---

## A bit more about me

I write occasionally about fintech, product strategy, and AI governance — three pieces published, more in progress.

Based in Boston USA . Originally from Mumbai India. 
Why good product management is mostly just listening carefully and then being stubborn about what you heard. Lets connect on that and more !!!

Certified SAFe APM, PSPO I, PSM I, AWS Cloud Practitioner.

---

📫 [LinkedIn](https://www.linkedin.com/in/sujatha-iyer/) 
