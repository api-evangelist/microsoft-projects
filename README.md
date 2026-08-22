# Microsoft Project APIs (microsoft-projects)

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

A collection of APIs for Microsoft Project, enabling project management, task tracking, resource allocation, and collaboration capabilities.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-projects/refs/heads/main/apis.yml)

## Tags:

 - Collaboration, Enterprise, Microsoft, Portfolio-Management, Project-Management, Resources, Tasks

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-28

## APIs

### Microsoft Project for the Web API
REST API for managing projects, tasks, resources, and assignments in Microsoft Project for the web.

**Human URL:** [https://docs.microsoft.com/en-us/project/](https://docs.microsoft.com/en-us/project/)

**Base URL:** https://graph.microsoft.com/v1.0/

#### Tags:

 - Assignments, Collaboration, Projects, Resources, Tasks

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/graph/api/resources/project-rome-overview)
- [X-openapi](https://developer.microsoft.com/en-us/graph/docs/api-reference/v1.0/resources/project)
- [X-authentication](https://docs.microsoft.com/en-us/graph/auth/)
- [X-rate-limits](https://docs.microsoft.com/en-us/graph/throttling)

### Microsoft Project Online API
REST API for Microsoft Project Online, providing access to project data, timesheets, and enterprise project management features.

**Human URL:** [https://docs.microsoft.com/en-us/project/project-online](https://docs.microsoft.com/en-us/project/project-online)

**Base URL:** https://{tenant}.sharepoint.com/sites/pwa/_api/ProjectServer/

#### Tags:

 - Enterprise, Portfolio, Project-Online, Reporting, Timesheets

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712820(v=office.15))
- [X-openapi](https://docs.microsoft.com/en-us/openspecs/sharepoint_protocols/ms-pjsoi/)
- [X-authentication](https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/authorization-and-authentication-of-sharepoint-add-ins)
- [X-sdk](https://docs.microsoft.com/en-us/project/api/project-csom-overview)

### Microsoft Project Desktop CSOM API
Client-side object model for programmatically interacting with Microsoft Project desktop applications.

**Human URL:** [https://docs.microsoft.com/en-us/office/client-developer/project/](https://docs.microsoft.com/en-us/office/client-developer/project/)

#### Tags:

 - Add-Ins, Automation, Csom, Desktop, Vba

#### Properties

- [X-documentation](https://docs.microsoft.com/en-us/office/client-developer/project/project-programming-references)
- [X-sdk](https://docs.microsoft.com/en-us/visualstudio/vsto/office-solutions-development-overview-vsto)
- [X-samples](https://github.com/OfficeDev/Project-Samples)

## Common Properties

- [X-portal](https://developer.microsoft.com/)
- [X-pricing](https://www.microsoft.com/en-us/microsoft-365/project/compare-microsoft-project-management-software)
- [X-status](https://status.cloud.microsoft/)
- [X-blog](https://techcommunity.microsoft.com/t5/project-blog/bg-p/ProjectBlog)
- [X-terms-of-service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [X-privacy-policy](https://privacy.microsoft.com/en-us/privacystatement)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
