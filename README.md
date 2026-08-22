# The Carlyle Group (carlyle-group)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The Carlyle Group (NASDAQ: CG) is a global investment firm that deploys private capital across Global Private Equity, Global Credit, Global Investment Solutions (AlpInvest), and carveouts such as Carlyle Direct Lending. Carlyle does not publish a public developer API. Institutional LPs, co-investors, and portfolio companies interact with the firm through a set of private, authentication-gated portals: LP Connect for fund investors, Carlyle Direct Lending's portal for direct lending clients, the Carlyle Global Portfolio Solutions (resources.carlyle.com) portal, and brand experiences such as Carlyle & Co. Integrations with fund administrators, custodians, and placement agents run through bespoke secure file exchange and vendor-managed APIs.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/carlyle-group/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** company
- **Position:** Consumer
- **Access:** Partner

## Tags

- Alternative Assets
- Asset Management
- Direct Lending
- Global Credit
- Investment Firm
- Investor Portal
- Limited Partners
- Private Credit
- Private Equity
- Real Assets

## Overview

Carlyle is one of the largest alternative asset managers in the world, with hundreds of billions of assets under management across private equity, credit, and investment solutions. Because the business is institutional rather than developer-facing, Carlyle exposes its digital surfaces as gated investor and portfolio portals rather than public REST APIs. LPs and their advisors log into LP Connect for fund-level reporting and capital activity; direct lending clients use a dedicated portal for BDC and direct-lending reporting; portfolio company executives and Carlyle's operations team collaborate through the Global Portfolio Solutions Portal.

## APIs


#### Features
- LP fund reporting and capital activity
- Capital call and distribution notices
- Tax documents (K-1s, PFIC) and investor statements
- Ad-hoc diligence and side letter documents
- Email-based credential recovery

#### Use Cases
- Family office LP operations
- Pension and endowment staff reporting
- Fund-of-funds due diligence workflows
- Third-party LP administration

### Carlyle Direct Lending Investor Portal
Carlyle Direct Lending operates a dedicated investor portal for clients of Carlyle's direct lending funds and BDC vehicles. The portal supports modern web browsers and is used for reporting, distributions, and investor communications.

**Human URL:** [https://directlending.carlyle.com](https://directlending.carlyle.com)

#### Features
- BDC and direct lending fund reporting
- Distribution and capital activity notices
- Modern browser support (Chrome, Edge, Safari, Firefox, Opera)

#### Use Cases
- BDC shareholder account access
- Institutional direct lending LP reporting
- RIA/advisor portfolio oversight

### Carlyle Global Portfolio Solutions Portal
The Carlyle Global Portfolio Solutions Portal (resources.carlyle.com) is the secure workspace used by Carlyle's portfolio operations team, portfolio company executives, and advisors to share tools, templates, and operational playbooks across the portfolio.

**Human URL:** [https://resources.carlyle.com/carlyle/login](https://resources.carlyle.com/carlyle/login)

#### Features
- Portfolio operations resources and templates
- Executive community and tooling
- Secure document sharing

#### Use Cases
- Portco finance and HR standardization
- Value-creation playbook distribution
- M&A and carve-out support

## Common Properties

- [Website](https://www.carlyle.com/)
- [Investor Relations](https://ir.carlyle.com/)
- [LP Connect](https://lpconnect.carlyle.com)
- [Direct Lending Portal](https://directlending.carlyle.com)
- [Global Portfolio Solutions Portal](https://resources.carlyle.com/carlyle/login)
- [AlpInvest](https://www.carlylealpinvest.com/)
- [Login](https://www.carlyle.com/user/login)
- [About](https://www.carlyle.com/about-carlyle)
- [Careers](https://www.carlyle.com/careers)
- [Contact](https://www.carlyle.com/contact-us)
- [Privacy Policy](https://www.carlyle.com/privacy-policy)
- [Terms of Use](https://www.carlyle.com/terms-of-use)
- [LinkedIn](https://www.linkedin.com/company/the-carlyle-group)
- [X](https://x.com/OneCarlyle)

## Timestamps

- **Created:** 2026-03-23
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
