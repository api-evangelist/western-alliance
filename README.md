# Western Alliance Bank (western-alliance)

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

Western Alliance Bancorporation (NYSE: WAL) is a Phoenix, Arizona based super-regional bank holding company with roughly $80 billion in assets, operating through its principal subsidiary Western Alliance Bank — an Arizona state-chartered commercial bank and member FDIC. It is a commercial- and business-banking focused institution that runs regional divisions including Alliance Bank of Arizona, Bank of Nevada, Bridge Bank, and Torrey Pines Bank.

Western Alliance operates a real first-party developer portal, the **WAB API Developer Portal** ("Developer Hub") at [developer.westernalliancebank.com](https://developer.westernalliancebank.com/s/), exposing commercial Treasury Management open-banking APIs. Access is partner/customer-gated: API specifications are downloaded from the Developer Hub only with WAB-issued credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/western-alliance/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/western-alliance/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- United States
- Treasury Management
- Open Banking
- Payments
- Commercial Banking

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Western Alliance Bank API (Treasury Management)

Western Alliance Bank's commercial open-banking API lets approved business clients interact directly with WAB systems to access balance and transaction information, retrieve check images, initiate funds transfers, and place stop payments. It is documented publicly as an open-banking capability; the API specifications and endpoints themselves are gated behind the WAB Developer Hub and issued credentials. Authentication uses OAuth2 client credentials (Client ID and Client Secret), a Client Certificate (mTLS), and access tokens across separate UAT and Production environments.

- **Human URL:** [https://developer.westernalliancebank.com/s/](https://developer.westernalliancebank.com/s/)

#### Tags

- Treasury Management
- Open Banking
- Payments

#### Properties

- [Documentation](https://developer.westernalliancebank.com/s/)
- [Documentation](https://www.westernalliancebancorporation.com/commercial/treasury-management)
- [Terms of Service](https://www.westernalliancebancorporation.com/sites/default/files/2025-05/api-services-terms-conditions.pdf)

## Open-Finance Posture

- **First-party developer portal:** Yes — WAB API Developer Portal / Developer Hub (Salesforce Experience Cloud), confirmed live.
- **Downloadable OpenAPI/Swagger:** No public spec — specifications are credential-gated behind the Developer Hub.
- **FDX participation / CFPB 1033:** Not documented. The published API surface is a commercial Treasury Management API, not a consumer permissioned-data-sharing API.
- **Aggregator access:** Available via payment-platform partners such as Modern Treasury.
- **Auth model:** OAuth2 client credentials + Client Certificate (mTLS) + access token.

## Common Properties

- [Website](https://www.westernalliancebancorporation.com/)
- [Developer Portal](https://developer.westernalliancebank.com/s/)
- [Documentation](https://developer.westernalliancebank.com/s/)
- [GitHub Organization](https://github.com/westernalliancebank)
- [LinkedIn](https://www.linkedin.com/company/western-alliance-bank)
- [Privacy Policy](https://www.westernalliancebancorporation.com/privacy-legal-home/privacy-policy)
- [Terms of Service](https://www.westernalliancebancorporation.com/sites/default/files/2025-05/api-services-terms-conditions.pdf)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
