# Library of Congress (loc)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

APIs.json provider profile for the Library of Congress, the largest library in the world and the research arm of the US Congress.

## APIs

### loc.gov JSON API
Provides structured, machine-readable data about Library of Congress digital collections in JSON or YAML format. No authentication required.

- Base URL: `https://www.loc.gov`
- Format: `https://www.loc.gov/{endpoint}/?fo=json`
- Rate limit: 20 requests/minute
- Docs: https://www.loc.gov/apis/json-and-yaml/

Key endpoints: `/search/`, `/collections/`, `/collections/{name}/`, `/item/{id}/`, `/resource/{id}/`, `/{format}/`

### Congress.gov API (v3)
Machine-readable access to all legislative data: bills, amendments, members, committees, nominations, treaties, and the Congressional Record.

- Base URL: `https://api.congress.gov/v3`
- Authentication: Free API key (sign up at https://api.congress.gov/sign-up/)
- Rate limit: 5,000 requests/hour
- Response formats: JSON, XML
- Docs: https://api.congress.gov/
- GitHub: https://github.com/LibraryOfCongress/api.congress.gov

### Chronicling America API
Access to historic American newspapers digitized by the Library of Congress. No authentication required.

- Base URL: `https://chroniclingamerica.loc.gov`
- Docs: https://chroniclingamerica.loc.gov/about/api/

## Links

- Website: https://www.loc.gov
- APIs Hub: https://www.loc.gov/apis/
- GitHub: https://github.com/LibraryOfCongress
- Blog (The Signal): https://blogs.loc.gov/thesignal/
- X/Twitter: https://twitter.com/librarycongress
- LinkedIn: https://www.linkedin.com/company/library-of-congress

## Maintainer

Kin Lane — kin@apievangelist.com
