# Awesome-Customer-Service-Support-Platform

# Awesome-Customer-Service-Support-Platform

**Top Customer Service Support Platform (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Shared Inboxes, Ticketing, SLAs, AI Resolution & Self-Hosted Helpdesk Infrastructure*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Service & Support Platforms**. These tools enable teams to manage conversations across email, chat, and social channels, resolve tickets against SLAs, and scale support with AI—from fully managed enterprise suites with outcome-based AI pricing to self-hosted helpdesks that give organizations complete ownership of their support data.



**Examples** include Zendesk Support, Freshdesk, HubSpot Service Hub, Salesforce Service Cloud, Intercom, Zoho Desk, Help Scout, Gladly, Kustomer, and ServiceNow CSM (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted ticketing, shared inboxes, and open support infrastructure. **Critical note**: The open-source helpdesk landscape is mature—**Frappe Helpdesk** offers unlimited agents with SLAs on the Frappe stack , **OTOBO** continues the OTRS ITSM lineage , and **Request Tracker** provides granular per-queue permissions . No open-source project matches Zendesk's omnichannel polish or Gladly's retail-focused CX depth, but for core ticketing and SLAs, the open-source options are production-proven.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Zendesk Support](https://www.zendesk.com/)**

  **Enterprise support suite** with omnichannel ticketing and AI agents. **Pricing**: **Support Team $19/agent/month** (entry); **Suite Team $55/agent/month** (adds messaging, help center, AI); **Suite Professional $115/agent/month**; **Advanced AI add-on $50/agent/month** stacks on top . **Free tier**: **No free plan**; **14-day trial** on Suite Professional . **Best for**: teams wanting the most mature omnichannel support with optional AI—**trade-off**: add-ons stack quickly; Suite Team + Advanced AI reaches **$105/agent/month** .



- **[Freshdesk](https://www.freshworks.com/freshdesk/)**

  **Support ticketing** with Freddy AI and multi-channel inbox. **Pricing**: **Growth $19/agent/month** (annual); **Pro $49/agent/month**; **Enterprise quote-only**. **Free tier**: **No free plan on current pricing page**—the free tier shrank from unlimited agents (2022) to 10 (2023–24) to 2 (2025) and **disappeared by October 2026**; only a six-month offer for 1–2 agents existed in early 2026 . **Best for**: mid-market teams wanting comparable features to Zendesk at lower cost—**trade-off**: no viable free tier; 14-day trial on Enterprise only .



- **[HubSpot Service Hub](https://www.hubspot.com/)**

  **Support within HubSpot CRM** with tickets, knowledge base, and surveys. **Pricing**: **Free plan up to 2 users**; **Starter $20/seat/month**; **Professional $100/seat/month**; **Enterprise quote-only**. **Free tier**: Yes, 2 users on combined Free plan . **Best for**: HubSpot CRM users wanting support tied to customer records—**trade-off**: value depends on existing HubSpot investment; don't buy CRM just for Service Hub .



- **[Salesforce Service Cloud](https://www.salesforce.com/)**

  **Enterprise service platform** with case management and AI (Einstein). **Pricing**: Quote-only; per-user licensing. **Free tier**: None. **Best for**: large enterprises already on Salesforce needing deep CRM integration.



- **[Intercom](https://www.intercom.com/)**

  **AI-first support platform** with Fin AI Agent. **Pricing**: **Essential from $0.99/seat/month** (annual) plus **Fin at $0.99 per outcome**; **Advanced $85/seat/month**; **Expert $132/seat/month**; Copilot add-on **$29/agent/month**; Pro add-on **$100/month** . **Free tier**: No permanent free tier; trial available. **Best for**: teams wanting AI resolution priced per outcome—**trade-off**: seat + per-outcome costs stack; minimum monthly commitment on Fin.



- **[Zoho Desk](https://www.zoho.com/desk/)**

  **Support ticketing** within Zoho ecosystem. **Pricing**: **Express $9/user/month** (annual, 5-user cap); **Standard $20/user/month**; **Professional $35/user/month**; **Enterprise $50/user/month** . **Free tier**: **Free plan up to 5 agents** on Standard tier. **Best for**: SMBs wanting affordable ticketing with a genuine free tier—**trade-off**: Express capped at 5 users; advanced AI requires Enterprise.



- **[Help Scout](https://www.helpscout.com/)**

  **Email-first shared inbox** with optional AI. **Pricing**: **Free up to 5 users**; **Standard $25/user/month** (annual); **Plus $45/user/month**; **Pro $75/user/month**; **AI Answers $0.75/resolution** after 3-month free trial . **Free tier**: Yes, up to 5 users. **Best for**: teams wanting simple, email-centric support with a usable free tier—**trade-off**: AI resolution metered separately; no complex workflow builder.



- **[Gladly](https://www.gladly.com/)**

  **Retail-focused customer service platform** with lifelong conversation history. **Pricing**: **Enterprise-only starting at $100K+/year**; **Hero from $180/agent/month** (min 10 users); **Superhero $210/agent/month** (min 45 users); **Sidekick AI $0.60/resolution** . **Free tier**: None. **Best for**: large retail and DTC brands wanting unified customer history—**trade-off**: enterprise procurement; excludes SMBs.



- **[Kustomer](https://www.kustomer.com/)**

  **CX platform** with AI and omnichannel messaging. **Pricing**: Quote-only; annual contracts. Software Advice lists starting at **$89/month** but official pricing requires sales engagement . **Free tier**: None. **Best for**: mid-market to enterprise teams wanting unified customer data—**trade-off**: quote-only; no self-serve.



- **[ServiceNow CSM](https://www.servicenow.com/)**

  **Enterprise customer service management** on the ServiceNow platform. **Pricing**: **Per fulfiller seat** (people who work cases); illustrative **~$100/fulfiller/month** = **$720K/year for 600 seats**; **Now Assist AI** at **~$75/user/month** for generative tier . **Free tier**: None. **Best for**: large enterprises already on ServiceNow wanting CSM integrated with ITSM—**trade-off**: complex licensing; portal deflection can reduce seat needs.



## Open-Source GitHub Projects



- **[Frappe Helpdesk](https://github.com/frappe/helpdesk)**

  **Open-source ticketing and customer support app** (AGPL-3.0) — **the most practical open-source helpdesk for teams already on Frappe/ERPNext**, with **3.4k stars** and active releases (v1.31.0 October 2026) . **Features**: **Tickets, SLAs, and customer portal** with **no per-agent fees**; SLAs with business hours and auto-assignment by priority/type/team/workload; **unlimited agents**; sign-in via Google, Microsoft, or custom OIDC through Frappe; **customer sync with ERPNext** and call logging via Twilio/Exotel . **Tech stack**: Python (Frappe Framework), Vue.js, MariaDB/Redis. **Deploy**: Self-hosted (Frappe bench) or **Frappe Cloud at $5/month** . **Trade-off**: **No live chat or WhatsApp channel**; self-hosting requires the full Frappe stack (MariaDB, Redis, bench) . **Best for**: ERPNext/Frappe teams wanting support tickets integrated with their ERP—especially those wanting unlimited agents without seat fees.



- **[OTOBO](https://github.com/RotherOSS/otobo)**

  **Open-source ticketing and IT service management** (GPL-3.0) — **the maintained fork of OTRS**, continuing the codebase with free ITSM packages . **Features**: **ITSM add-on packages free to download**; OpenID Connect, LDAP, and RADIUS sign-in in free code; runs on MariaDB, MySQL, PostgreSQL, or Oracle; **customer self-service portal included** . **Tech stack**: Perl, Apache/Nginx. **Deploy**: Self-hosted. **Trade-off**: **Production servers need 8 GB RAM minimum (16 GB recommended)**; vendor support starts at **€3,900/year**; no audit log beyond ticket/settings history . **Best for**: IT and service teams wanting an OTRS-style service desk without license fees—especially those needing ITSM features.



- **[Request Tracker (RT)](https://github.com/bestpractical/rt)**

  **Open-source ticket tracker** (GPL-2.0) — **the veteran for granular per-queue permissions**, maintained by Best Practical, with **1.2k stars** and v6.0.3 (May 2026) . **Features**: **Rights per queue, group, and role**; **asset tracking built in**; **REST 2 API** in core; **RT 6 lets admins rearrange ticket page layouts** . **Tech stack**: Perl, MySQL/PostgreSQL/Oracle/SQLite. **Deploy**: Self-hosted (Perl source install). **Trade-off**: **No official Docker image for production**; **SSO needs a web server module** (no built-in SAML/OIDC); cloud RT needs 5+ users on annual plan . **Best for**: IT and operations teams needing detailed per-queue rights and full change history—especially those comfortable with Perl.



### Additional Strong Open-Source Options



- **UVdesk** — PHP/Symfony helpdesk (OSL-3.0) with **unlimited agents, teams, and mailboxes** in free edition; email tickets + customer portal + knowledge base . **Note**: **No SSO for agents, no audit log**; **no new release since v1.1.8 (September 2025)** . **Best for**: small teams on PHP hosting needing email ticketing and self-service portal.

- **Libredesk** — Open-source support inbox in Go (single binary) for email and live chat . **Note**: **New and worth watching**—verify maturity before production. **Best for**: teams wanting a lightweight Go-based helpdesk.



**Frameworks for building custom systems**: Choose **Frappe Helpdesk** for unlimited agents on Frappe/ERPNext, **OTOBO** for ITSM lineage, and **Request Tracker** for granular permissions—each serves a distinct operational profile. **None of these match Zendesk's omnichannel polish or Gladly's retail CX depth**, but for core ticketing and SLAs, the open-source options cover most needs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Customer service platforms handling support conversations must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for customer data.

- **The "omnichannel suite" vs. "email-first inbox" vs. "enterprise CX platform" vs. "ITSM" distinction is critical.** **Zendesk, Freshdesk, HubSpot Service Hub, Salesforce Service Cloud, Intercom, Zoho Desk, and Help Scout** are **support platforms**—they manage tickets and conversations across channels. **Gladly and Kustomer** are **CX platforms**—they unify customer history with AI orchestration. **ServiceNow CSM** is **enterprise CSM**—it integrates with ITSM and platform workflows. **Frappe Helpdesk, OTOBO, and Request Tracker** are **self-hosted helpdesks**—you own the infrastructure. **Choose based on whether you need omnichannel, email-first simplicity, enterprise CX, or ITSM integration.**

- **Freshdesk's free tier is gone.** The free plan shrank from unlimited agents (2022) to 10 (2023–24) to 2 (2025) and **disappeared from the pricing page by October 2026**—only a six-month offer for 1–2 agents existed in early 2026 . **Do not plan a free Freshdesk deployment.**

- **Help Scout and Zoho Desk are the only platforms with genuine free tiers.** Help Scout: **free up to 5 users** . Zoho Desk: **free up to 5 agents** on Standard . **HubSpot Service Hub is free up to 2 users** . **For small teams, these are the pragmatic starting points.**

- **Gladly is enterprise-only with $100K+ commitments.** Hero starts at **$180/agent/month with a 10-user minimum**; Superhero at **$210/agent/month with 45-user minimum** . **Do not evaluate for SMBs.**

- **ServiceNow CSM licensing is per fulfiller, not per user.** Only people who work cases consume seats; portal and Virtual Agent deflections reduce licensing needs . **Model your fulfiller count carefully—this is where costs are won or lost.**

- **Frappe Helpdesk is the best open-source option for unlimited agents.** No per-agent fees, SLAs with business hours, ERPNext sync, and **$5/month Frappe Cloud hosting** . **The trade-off**: no live chat or WhatsApp; requires the Frappe stack for self-hosting.

- **OTOBO needs 8 GB RAM minimum**—plan infrastructure accordingly. **Request Tracker has no official Docker image** and SSO requires web server modules .

- **Pricing opacity varies.** Zendesk, Freshdesk, HubSpot, Intercom, Zoho Desk, and Help Scout publish tiered pricing. Gladly requires enterprise engagement. Kustomer and ServiceNow require sales contact. **Validate with direct vendor conversations against your agent count and channel mix.**

- Self-hosted open-source solutions require proper infrastructure (Frappe stack for Helpdesk, 8 GB+ RAM for OTOBO), security hardening, and ongoing maintenance. **Support data includes customer PII and conversation history**—ensure your deployment meets your organization's privacy and compliance requirements before migrating production support.



---



**Made for support leads, IT teams, and organizations building transparent customer service solutions.**

Let's make Customer Service & Support Platforms more open, data-driven, and resolution-friendly.
