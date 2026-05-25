# Browserless (browserless)

Browserless is a cloud browser-automation platform that runs managed Chromium, Chrome, Edge, Firefox, and WebKit browsers for Puppeteer, Playwright, and Selenium clients, plus a GraphQL-based stealth automation layer (BrowserQL) and a family of REST APIs for screenshots, PDFs, content scraping, function execution, performance audits, smart scraping, search, mapping, and full-site crawling. A built-in MCP server exposes browser tooling to Claude, Cursor, VS Code, and other agentic clients. The company also maintains the popular open-source `browserless/browserless` Docker image (Apache-2.0, 13k+ GitHub stars).

**URL:** [Browserless apis.yml](https://raw.githubusercontent.com/api-evangelist/browserless/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

AI Agents, Browser Infrastructure, BrowserQL, CAPTCHA Solving, CDP, Crawl, Headless Browser, Hybrid Automation, MCP, PDF Generation, Playwright, Puppeteer, Residential Proxy, Screenshots, Search, Selenium, Session Recording, Smart Scrape, Stealth, Web Automation, Web Scraping

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Browserless Cloud API

The Browserless Cloud API combines (1) WebSocket BaaS endpoints compatible with Puppeteer, Playwright, and Selenium across Chromium, Chrome, Edge, Firefox, and WebKit; (2) the GraphQL BrowserQL layer for stealth scraping with built-in CAPTCHA solving and residential proxies; and (3) a REST API family for screenshots, PDFs, content, scrape, function execution, performance audits, smart-scrape, search, map, crawl, unblock, and session management. All surfaces share a single API token and the `production-{sfo,lon,ams}.browserless.io` regional host pattern.

- **Human URL:** https://docs.browserless.io
- **Base URL:** https://production-sfo.browserless.io

#### Tags

BaaS, BrowserQL, CAPTCHA, Crawl, Function, Map, MCP, PDF, Performance, Profile, Proxy, REST, Scrape, Screenshots, Search, Session, Smart Scrape, Stealth, Unblock

#### Properties

- [Documentation](https://docs.browserless.io)
- [API Reference](https://docs.browserless.io/open-api)
- [Getting Started](https://docs.browserless.io/overview/quick-start)
- [Sign Up](https://account.browserless.io/signup)
- [Open-Source Image](https://github.com/browserless/browserless)
- [Official MCP Server](https://github.com/browserless/browserless-mcp) — `https://mcp.browserless.io/mcp`
- [Claude Plugin](https://github.com/browserless/claude-plugin)
- [Gemini CLI Extension](https://github.com/browserless/gemini-extension)
- [n8n Community Node](https://github.com/browserless/n8n-nodes-browserless-api)
- [Dify Plugin](https://github.com/browserless/dify-plugin)
- [Cursor MCP Plugin](https://github.com/browserless/cursor-mcp-plugin)
- [LangChain Examples](https://github.com/browserless/browserless-langchain)
- [LlamaIndex Examples](https://github.com/browserless/browserless-llamaindex)
- [Agno Examples](https://github.com/browserless/browserless-agno)
- [bolt.diy Starter](https://github.com/browserless/bolt-diy-browserless-mcp-starter)
- [OpenAPI](openapi/browserless-openapi.yml)
- [JSON Schema](json-schema/browserless-session-schema.json)
- [JSON Structure](json-structure/browserless-session-structure.json)
- [JSON-LD](json-ld/browserless-context.jsonld)
- [Examples](examples/browserless-screenshot-example.json)
- [Plans](plans/browserless-plans-pricing.yml)
- [Rate Limits](rate-limits/browserless-rate-limits.yml)
- [FinOps](finops/browserless-finops.yml)
- [Naftiko Capabilities — REST APIs](capabilities/rest-apis.yaml)
- [Naftiko Capabilities — BrowserQL](capabilities/browserql.yaml)
- [Naftiko Capabilities — Sessions](capabilities/sessions.yaml)
- [Naftiko Capabilities — Profiles](capabilities/profiles.yaml)
- [Vocabulary](vocabulary/browserless-vocabulary.yml)
- [Spectral Rules](rules/browserless-rules.yml)
- [Change Log](https://www.browserless.io/changelog)
- [Status Page](https://status.browserless.io)
- [Pricing](https://www.browserless.io/pricing)
- [Enterprise](https://www.browserless.io/enterprise)

#### Features

- **Browsers-as-a-Service (BaaS)** — WebSocket endpoints (`production-sfo`, `production-lon`, `production-ams`) that drop into existing Puppeteer (`connect`) and Playwright (`connectOverCDP` / `connect`) code with one URL change.
- **BrowserQL (BQL)** — GraphQL automation language with `goto`, `click`, `type`, `evaluate`, `waitForSelector`, `html`, `mapSelector`, `screenshot`, `pdf`, and `reconnect` mutations; stealth (`/stealth/bql`) and Chrome (`/chrome/bql`) routes.
- **REST API Family** — `/screenshot`, `/pdf`, `/content`, `/scrape`, `/function`, `/performance`, `/download`, `/export`, `/search`, `/smart-scrape`, `/map`, `/crawl`, and `/unblock` over `chrome`, `chromium`, and `edge` prefixes.
- **Stealth and Bot Detection** — Path-based stealth routes, WebGL fingerprinting, UA spoofing, entropy injection; supports reCAPTCHA, hCaptcha, DataDome, Lemin, MTCaptcha, and slider challenges.
- **Residential Proxies** — Built-in residential routing with country / city / sticky-session controls plus bring-your-own external proxies.
- **Session Profiles** — Reusable, encrypted browser profiles via `/profile` and `/profile/refresh` for cookies, localStorage, and authenticated-state reuse.
- **Hybrid Automation / LiveURL** — `Browserless.liveURL` CDP commands hand control of a running session to a human (or watching agent) over an embedded live URL.
- **Session Recording and Replay** — rrweb-based session replays plus WebM screen recordings.
- **Smart Scrape, Search, Map, Crawl** — AI-tuned REST endpoints that pick the cheapest extraction strategy, perform web search, build site maps, and run depth-bounded crawls.
- **Official MCP Server** — `mcp.browserless.io/mcp` exposes browser-agent, smart-scraper, custom-code, downloads, page-export, Lighthouse, and crawl tools to Claude Desktop, Cursor, VS Code, and Windsurf.
- **Open-Source Core** — `browserless/browserless` Docker image (Apache-2.0, 13k+ stars) is free for non-commercial use and underpins the cloud service.
- **Enterprise Self-Hosting** — Private cloud deployments, licensed self-hosting, GPU infrastructure, SSO, dedicated account management.

#### Use Cases

- **AI Agent Browsing** — Real-browser tool surface for Claude / GPT / open-source agents.
- **Stealth Web Scraping at Scale** — Fingerprint-randomized Chromium fleets behind residential proxies.
- **PDF and Screenshot Generation** — High-fidelity HTML-to-PDF and image rendering at scale.
- **End-to-End Testing** — Run Playwright / Puppeteer / Selenium suites in managed browsers.
- **RPA and Hybrid Human-in-the-Loop Workflows** — Combine programmatic automation with LiveURL handoff.
- **Synthetic Monitoring and Lighthouse Audits** — Schedule performance / accessibility / SEO audits across page fleets.
- **AI-Tuned Site Crawls and Knowledge Building** — Feed agents with structured site context via `/crawl`, `/map`, `/search`.

#### Integrations

Puppeteer, Playwright, Selenium, Browser Use, Stagehand, LangChain, LlamaIndex, Agno, Mastra, Vercel AI SDK, n8n, Make, Zapier, Dify, bolt.diy, Cursor, VS Code, Windsurf, Claude Desktop, Gemini CLI, [Anthropic](https://github.com/api-evangelist/anthropic), MCP.

#### Authentication

- **API Key** — A single token authenticates all surfaces. REST and BaaS pass it as `?token=YOUR_API_TOKEN` on the connection URL; BrowserQL accepts the same token in the URL or via header.

## Artifacts

### OpenAPI

- [openapi/browserless-openapi.yml](openapi/browserless-openapi.yml) — OpenAPI 3.0.0, 69 paths, sourced from `docs.browserless.io/redocusaurus/plugin-redoc-0.yaml` (Browserless 2.49.0).

### Naftiko Capabilities

- [capabilities/rest-apis.yaml](capabilities/rest-apis.yaml) — Screenshots, PDF, content, scrape, function, performance, smart-scrape, search, map, crawl, unblock.
- [capabilities/browserql.yaml](capabilities/browserql.yaml) — `/chromium/bql`, `/chrome/bql`, `/stealth/bql` GraphQL surfaces.
- [capabilities/sessions.yaml](capabilities/sessions.yaml) — Session lifecycle, active/kill, meta, CDP `/json/*` helpers.
- [capabilities/profiles.yaml](capabilities/profiles.yaml) — Profile CRUD, refresh, and `/proxy/cities` lookup.

### JSON Schema

- [json-schema/browserless-session-schema.json](json-schema/browserless-session-schema.json)
- [json-schema/browserless-screenshot-schema.json](json-schema/browserless-screenshot-schema.json)
- [json-schema/browserless-profile-schema.json](json-schema/browserless-profile-schema.json)

### JSON Structure

- [json-structure/browserless-session-structure.json](json-structure/browserless-session-structure.json)
- [json-structure/browserless-profile-structure.json](json-structure/browserless-profile-structure.json)

### JSON-LD

- [json-ld/browserless-context.jsonld](json-ld/browserless-context.jsonld)

### Examples

- [examples/browserless-screenshot-example.json](examples/browserless-screenshot-example.json)
- [examples/browserless-pdf-example.json](examples/browserless-pdf-example.json)
- [examples/browserless-scrape-example.json](examples/browserless-scrape-example.json)
- [examples/browserless-browserql-example.json](examples/browserless-browserql-example.json)
- [examples/browserless-session-example.json](examples/browserless-session-example.json)

### Vocabulary

- [vocabulary/browserless-vocabulary.yml](vocabulary/browserless-vocabulary.yml)

### Spectral Rules

- [rules/browserless-rules.yml](rules/browserless-rules.yml)

### Commercial

- [plans/browserless-plans-pricing.yml](plans/browserless-plans-pricing.yml) — API Commons Plans 0.1 (Free / Prototyping / Starter / Scale / Enterprise).
- [rate-limits/browserless-rate-limits.yml](rate-limits/browserless-rate-limits.yml) — API Commons Rate Limits 0.1 (per-tier concurrency, monthly units, max session time).
- [finops/browserless-finops.yml](finops/browserless-finops.yml) — FinOps / FOCUS 1.3 alignment (session, residential proxy, CAPTCHA, subscription domains).

## Common

- [Website](https://www.browserless.io)
- [Documentation](https://docs.browserless.io)
- [API Reference](https://docs.browserless.io/open-api)
- [Blog](https://www.browserless.io/blog)
- [GitHub Organization](https://github.com/browserless)
- [Pricing](https://www.browserless.io/pricing)
- [Enterprise](https://www.browserless.io/enterprise)
- [Change Log](https://www.browserless.io/changelog)
- [Status Page](https://status.browserless.io)
- [Sign Up](https://account.browserless.io/signup)
- [Sign In](https://account.browserless.io)
- [Terms of Service](https://www.browserless.io/terms)
- [Privacy Policy](https://www.browserless.io/privacy)
- [llms.txt](https://docs.browserless.io/llms.txt)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
