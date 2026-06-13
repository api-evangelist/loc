# Library of Congress (loc)

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
