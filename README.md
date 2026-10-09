# Awesome-SMB-Marketing-Automation

## Top SMB Marketing Automation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Email Campaigns, Lead Scoring & Self-Hosted Marketing Automation*

**Last updated: October 2026**



This repository tracks notable **commercial SMB marketing automation platforms** and **open-source projects** that help small and medium businesses run email campaigns, nurture leads, and automate customer journeys without enterprise pricing.



**Examples** include Mailchimp, ActiveCampaign, Brevo, HubSpot Starter, Constant Contact, Moosend, AWeber, GetResponse, Drip, and MailerLite (the category leaders).



**Open-source emphasis**: SMB marketing automation is a strong open-source domain. **Mautic** leads as the world's largest open-source marketing automation platform with 40,000+ companies, 10.5k GitHub stars, and 13 years of development . **Listmonk** delivers high-performance newsletter management as a single Go binary . **Notifuse** brings a modern MJML visual editor with A/B testing and transactional API . **Senddock** offers API-first email marketing built with Go and Vue . **Keila** provides GDPR-friendly newsletter tooling with EU hosting . **Reloop** delivers an open-source Resend alternative with inbound email and workflows . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Mailchimp](https://mailchimp.com/)**

  **The most recognized SMB email marketing platform** — email campaigns, automation, audience management, and basic CRM. **Free tier for up to 500 contacts**; paid scales per subscriber. **Best for beginners wanting simplicity**.



- **[ActiveCampaign](https://www.activecampaign.com/)**

  **The automation leader for SMBs** — powerful email automation, CRM, lead scoring, and 850+ automation recipes. **Pricing from $79/month**. **Best for businesses needing sophisticated automation**.



- **[Brevo](https://www.brevo.com/)** (formerly Sendinblue)

  **All-in-one marketing platform** — email, SMS, chat, and CRM with generous free tier. **Free for 300 emails/day**. **Best for budget-conscious SMBs wanting omnichannel**.



- **[HubSpot Starter](https://www.hubspot.com/)**

  **HubSpot's entry-level marketing hub** — email marketing, forms, landing pages, and CRM. **From $15/month**. **Best for businesses wanting to grow into the HubSpot ecosystem**.



- **[Constant Contact](https://www.constantcontact.com/)**

  **Email marketing for small businesses** — campaigns, automation, and event management. **Best for local businesses and nonprofits**.



- **[Moosend](https://moosend.com/)**

  **Affordable email marketing and automation** — from $9/month. **Best for startups and small teams**.



- **[AWeber](https://www.aweber.com/)**

  **Veteran email marketing platform** — reliable deliverability and automation. **Best for bloggers and small businesses**.



- **[GetResponse](https://www.getresponse.com/)**

  **All-in-one marketing platform** — email, landing pages, webinars, and automation. **Best for teams wanting webinar capabilities**.



- **[Drip](https://www.drip.com/)**

  **E-commerce-focused marketing automation** — email, SMS, and personalization for online stores. **Best for e-commerce SMBs**.



- **[MailerLite](https://www.mailerlite.com/)**

  **Simple, affordable email marketing** — free for up to 1,000 subscribers. **Best for small businesses wanting modern UX**.



## Open-Source GitHub Projects



### Full Marketing Automation Platforms



- **[Mautic](https://github.com/mautic/mautic)**

  **The world's largest open-source marketing automation platform**, GPL licensed with **10,532 GitHub stars, 3,453 forks, and 13 years of development** . **Used by 40,000+ companies including Deutsche Bahn and Lehner Versand AG** (nearly 2 million contacts, up to a million emails daily) . **Features**: drag-and-drop campaign builder, email and landing page creation, contact management with lead scoring, segments, forms, and REST API . **Full data sovereignty** — self-host on your infrastructure with no per-contact fees . **Requirements**: cron worker is critical — without it campaigns never fire . **Best for comprehensive open-source marketing automation**.



- **[Notifuse](https://github.com/Notifuse/notifuse)**

  **Open-source, self-hosted newsletter, email marketing and transactional email platform**, AGPL-3.0 licensed with **2,100+ GitHub stars** . **Visual MJML editor** with drag-and-drop and real-time preview. **Visual flow builder** for multi-step automations with delay, email, branch, filter, A/B test, and webhook nodes . **Multi-provider support**: Amazon SES, Mailgun, Postmark, Mailjet, SparkPost, SendGrid, and SMTP. **Built-in cookieless web analytics** (Staminads) with channel attribution and goals . **Cloud from $16/month** or self-hosted free. **Best for modern email marketing with automations**.



### Newsletter & Campaign Platforms



- **[Listmonk](https://github.com/knadh/listmonk)**

  **High-performance newsletter and mailing list manager**, AGPL-3.0 licensed with **23,200+ GitHub stars** . **Single Go binary** with Vue UI — minimal dependencies, only PostgreSQL required. **Send millions of emails from your own SMTP** with no per-subscriber pricing . **Subscriber management, campaign analytics, and segmentation**. **The de facto open-source Mailchimp alternative** for newsletters. **Best for high-volume newsletters and mailing lists**.



- **[Keila](https://github.com/pentacent/keila)**

  **Open-source newsletter tool with EU hosting**, AGPL-3.0 licensed with **2,200+ GitHub stars** . **Visual editor and MJML support** . **Self-hosted or EU cloud from $8-32/month** . **GDPR-friendly with data residency control**. **Per-sender SMTP configuration** and API access . **Best for privacy-focused teams and EU-based businesses**.



- **[Senddock](https://github.com/arkhe-systems/senddock)**

  **Open-source email marketing platform, self-hostable and API-first**, built with Go and Vue . **Visual editor (GrapesJS) and code editor (CodeMirror)**. **Campaigns with scheduling and segmentation**. **Transactional API** for programmatic sending. **Deliverability essentials**: open tracking, click tracking, RFC 8058 one-click unsubscribe, suppressions, and bounces. **Pro tier** adds SPF/DKIM/DMARC health dashboard and report builder . **Best for developers wanting API-first email marketing**.



- **[Reloop](https://github.com/reloop-labs/reloop)**

  **Open-source transactional email API and self-hostable Resend alternative**, Apache-2.0 licensed with additional use restrictions . **Same capabilities as SendGrid, Mailchimp, Resend, and Loops** but fully self-hostable. **Transactional email, campaigns, inbound email parsing, visual template editor, real-time analytics, webhooks, contacts/lists, and workflows**. **One-command VPS install** . **Best for developers wanting full email infrastructure control**.



### Additional Strong Open-Source Options



- **phpList** — Open-source email marketing manager with subscriber management, segmentation, and bounce handling. AGPL-3.0 licensed with 870 GitHub stars .

- **FluentCRM** — Self-hosted email marketing automation plugin for WordPress. Manage leads, email campaigns, and automated sequencing without leaving WordPress .

- **Mailtrain** — Self-hosted newsletter application (slowing development) .

- **n8n** — Visual workflow automation with 400+ integrations for lead capture and email sequences. Self-hosted free .

- **PostHog** — Product analytics with session replay and A/B testing for growth experiments .



**Frameworks for building custom SMB marketing automation solutions**: Combine **Mautic** for comprehensive marketing automation with lead scoring, campaigns, and landing pages . Use **Listmonk** for high-volume newsletter delivery from your own SMTP . Deploy **Notifuse** for modern email marketing with visual automations and multi-provider support . Choose **Senddock** for API-first email marketing with developer-friendly tooling . Integrate **Keila** for GDPR-compliant newsletters with EU hosting . Use **Reloop** for transactional email infrastructure . Note that true enterprise marketing automation with managed infrastructure, AI-powered optimization, and vendor-supported SLAs (ActiveCampaign, HubSpot) remains primarily commercial territory; open-source stacks provide strong campaign, automation, and newsletter foundations that require integration for complete SMB marketing operations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Marketing automation platforms handle sensitive customer data and communication preferences. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA, CAN-SPAM).

- **Email deliverability requires IP reputation management** — self-hosted platforms must warm up IPs, configure SPF/DKIM/DMARC, and monitor blacklists. Commercial platforms provide managed deliverability.

- **Cron configuration is critical for Mautic** — without the cron worker, campaigns never fire and segments never update. This is the most common self-hosted Mautic failure .

- **License considerations**: Mautic uses GPL, Notifuse uses AGPL-3.0, Listmonk uses AGPL-3.0, Keila uses AGPL-3.0, and Reloop uses Apache-2.0 with use restrictions. Verify licensing against your use case before committing.

- The open-source ecosystem provides strong campaign, automation, and newsletter foundations, but **managed infrastructure, AI-powered optimization, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for SMB owners, marketing teams, and organizations seeking marketing automation sovereignty.**

Let's make SMB marketing automation more open, transparent, and accessible.
