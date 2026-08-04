# Browserless (browserless)

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

Browserless is a cloud browser-automation platform that runs managed Chromium, Chrome, Edge, Firefox, and WebKit browsers for Puppeteer, Playwright, and Selenium clients, plus a GraphQL-based stealth automation layer (BrowserQL) and a family of REST APIs for screenshots, PDFs, content scraping, function execution, performance audits, smart scraping, search, mapping, and full-site crawling. A built-in MCP server exposes browser tooling to Claude, Cursor, VS Code, and other agentic clients. The company also maintains a popular open-source Docker image of the same name (13k+ GitHub stars), residential proxies, CAPTCHA solving, session profiles, recordings, and hybrid live-URL workflows. Target customers are AI startups, agent developers, web scrapers, RPA teams, QA / monitoring teams, and enterprises running production browser automation at scale, with free, prototyping, starter, scale, and enterprise plans (including self-hosted licensing).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/browserless/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/browserless/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Headless Browser
- Browser Infrastructure
- Web Automation
- AI Agents
- Web Scraping
- BrowserQL
- Puppeteer
- Playwright
- Selenium
- CDP
- Stealth
- CAPTCHA Solving
- Residential Proxy
- PDF Generation
- Screenshots
- Smart Scrape
- Crawl
- Search
- MCP
- Session Recording
- Hybrid Automation

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Browserless Cloud API

The Browserless Cloud API is a multi-surface browser platform combining (1) WebSocket BaaS endpoints compatible with Puppeteer, Playwright, and Selenium across Chromium, Chrome, Edge, Firefox, and WebKit; (2) a GraphQL automation layer called BrowserQL for stealth scraping with built-in CAPTCHA solving and residential proxies; and (3) a REST API family for screenshots, PDFs, content, scrape, function execution, performance audits, smart-scrape, search, map, crawl, unblock, and session management. All surfaces share a single API token and a regional production-{sfo,lon,ams} host pattern.

- **Human URL:** [https://docs.browserless.io](https://docs.browserless.io)
- **Base URL:** `https://production-sfo.browserless.io`

#### Tags

- BaaS
- BrowserQL
- REST
- Screenshots
- PDF
- Scrape
- Smart Scrape
- Search
- Crawl
- Map
- Unblock
- Function
- Performance
- Session
- Profile
- Proxy
- CAPTCHA
- Stealth
- MCP

#### Properties

- [Documentation](https://docs.browserless.io)
- [API Reference](https://docs.browserless.io/open-api)
- [Getting Started](https://docs.browserless.io/overview/quick-start)
- [Sign Up](https://account.browserless.io/signup)
- [SDK](https://github.com/puppeteer/puppeteer)
- [SDK](https://github.com/microsoft/playwright)
- [SDK](https://github.com/SeleniumHQ/selenium)
- [GitHub Repository](https://github.com/browserless/browserless)
- [GitHub Repository](https://github.com/browserless/browserless-mcp)
- [GitHub Repository](https://github.com/browserless/claude-plugin)
- [GitHub Repository](https://github.com/browserless/gemini-extension)
- [GitHub Repository](https://github.com/browserless/n8n-nodes-browserless-api)
- [GitHub Repository](https://github.com/browserless/dify-plugin)
- [GitHub Repository](https://github.com/browserless/cursor-mcp-plugin)
- [GitHub Repository](https://github.com/browserless/browserless-langchain)
- [GitHub Repository](https://github.com/browserless/browserless-llamaindex)
- [GitHub Repository](https://github.com/browserless/browserless-agno)
- [GitHub Repository](https://github.com/browserless/bolt-diy-browserless-mcp-starter)
- [OpenAPI](openapi/browserless-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/browserless.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/browserless.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/browserless-session-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/browserless-session-structure.json)
- [JSON-LD](json-ld/browserless-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Examples](examples/browserless-screenshot-example.json)
- [Plans](plans/browserless-plans-pricing.yml)
- [Rate Limits](rate-limits/browserless-rate-limits.yml)
- [Fin Ops](finops/browserless-finops.yml)
- [Capabilities](capabilities/rest-apis.yaml)
- [Capabilities](capabilities/browserql.yaml)
- [Capabilities](capabilities/sessions.yaml)
- [Capabilities](capabilities/profiles.yaml)
- [Vocabulary](vocabulary/browserless-vocabulary.yml)
- [Rules](rules/browserless-rules.yml)
- [Changelog](https://www.browserless.io/changelog)
- [Status Page](https://status.browserless.io)
- [Pricing](https://www.browserless.io/pricing)
- [Enterprise](https://www.browserless.io/enterprise)
- [M C P](https://mcp.browserless.io/mcp)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://www.browserless.io)
- [Documentation](https://docs.browserless.io)
- [API Reference](https://docs.browserless.io/open-api)
- [Blog](https://www.browserless.io/blog)
- [GitHub Organization](https://github.com/browserless)
- [Pricing](https://www.browserless.io/pricing)
- [Enterprise](https://www.browserless.io/enterprise)
- [Changelog](https://www.browserless.io/changelog)
- [Status Page](https://status.browserless.io)
- [Sign Up](https://account.browserless.io/signup)
- [Sign In](https://account.browserless.io)
- [Terms of Service](https://www.browserless.io/terms)
- [Privacy Policy](https://www.browserless.io/privacy)
- [L L Ms Txt](https://docs.browserless.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
