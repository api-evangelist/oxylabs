# Oxylabs (oxylabs)

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

Oxylabs is a Lithuanian (Vilnius-based) web intelligence platform providing premium proxy networks (Residential, Datacenter, Mobile, ISP, Dedicated), web data acquisition APIs (Web Scraper API, SERP Scraper API, E-Commerce Scraper API, Real Estate Scraper API, Web Unblocker, Headless Browser), AI-native scraping tools (AI Studio — AI Scraper, AI Crawler, AI Map, Browser Agent, AI Search), an official MCP server, and ready-to-deliver datasets. The platform serves large-scale public web data extraction for e-commerce intelligence, brand protection, market research, SEO/SERP monitoring, cybersecurity, and AI/LLM training pipelines.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oxylabs/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oxylabs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Web Scraping
- Bot Mitigation Bypass
- CAPTCHA Solving
- Data Extraction
- Datacenter Proxies
- Datasets
- E-Commerce Data
- Headless Browser
- ISP Proxies
- Mobile Proxies
- Proxies
- Residential Proxies
- SERP
- Scraper API
- Scraping
- Web Data
- Web Intelligence
- Web Unblocker

## Timestamps

- **Created:** 2026-03-29
- **Modified:** 2026-05-25

## APIs

### Oxylabs Web Scraper API

General-purpose web scraping API that returns rendered HTML and structured JSON from public web pages. Two delivery modes — Realtime (synchronous request/response against realtime.oxylabs.io) and Push-Pull (asynchronous job submission with polling or callback against data.oxylabs.io). Supports JavaScript rendering, geo-targeting, locale, custom headers, parsing instructions, browser instructions, and pluggable parsers for SERP, e-commerce, real-estate, and universal targets. Authentication is HTTP Basic with sub-account credentials.

- **Human URL:** [https://developers.oxylabs.io/scraping-solutions/web-scraper-api](https://developers.oxylabs.io/scraping-solutions/web-scraper-api)
- **Base URL:** `https://realtime.oxylabs.io/v1`

#### Tags

- Data Extraction
- JavaScript Rendering
- Scraper API
- Scraping
- Web Data
- Web Intelligence

#### Properties

- [Documentation](https://developers.oxylabs.io/scraping-solutions/web-scraper-api)
- [Getting Started](https://developers.oxylabs.io/get-started/quick-start-web-scraper-api)
- [Features](https://developers.oxylabs.io/scraping-solutions/web-scraper-api/features)
- [OpenAPI](openapi/oxylabs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs SERP Scraper API

Search-engine results page scraping for Google (Search, Ads, Images, Lens, Maps, Suggest, Shopping, Travel, Trends, AI Overviews, AI Mode), Bing (Search, Hotels), Baidu, Yandex, DuckDuckGo, Naver, and others. Returns structured JSON results with built-in localization (geo_location, locale, domain), pagination, and JavaScript-rendered SERP features. Same submission contract as Web Scraper API.

- **Human URL:** [https://developers.oxylabs.io/api-targets/search-engines](https://developers.oxylabs.io/api-targets/search-engines)
- **Base URL:** `https://realtime.oxylabs.io/v1`

#### Tags

- Bing
- Google
- SEO
- SERP
- Scraper API
- Search Engines

#### Properties

- [Documentation](https://developers.oxylabs.io/api-targets/search-engines)
- [Documentation](https://oxylabs.io/products/scraper-api/serp)
- [Documentation](https://developers.oxylabs.io/scraping-solutions/web-scraper-api/targets/google)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs E-Commerce Scraper API

Pre-built scraping targets for major e-commerce platforms — Amazon (search, product, reviews, questions, best sellers, offer listing, ASIN), Walmart, eBay, Etsy, Target, Best Buy, Wayfair, Kroger, Macy's, Home Depot, Lowes, Costco, Wholefoods, Newegg, Idealo, MediaMarkt, AliExpress, 1688, Shein, Lazada, Trip, Trivago, Priceline, MercadoLivre, Falabella, Rakuten and more. Returns parsed JSON for search results, product detail pages, pricing, reviews, and category pages.

- **Human URL:** [https://developers.oxylabs.io/scraping-solutions/web-scraper-api/targets](https://developers.oxylabs.io/scraping-solutions/web-scraper-api/targets)
- **Base URL:** `https://realtime.oxylabs.io/v1`

#### Tags

- Amazon
- E-Commerce
- Product Data
- Pricing Intelligence
- Scraper API
- Walmart

#### Properties

- [Documentation](https://oxylabs.io/products/scraper-api/ecommerce)
- [Documentation](https://developers.oxylabs.io/scraping-solutions/web-scraper-api/targets/amazon)
- [Documentation](https://developers.oxylabs.io/scraping-solutions/web-scraper-api/targets/north-american-e-commerce)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs Web Unblocker

AI-driven proxy solution exposed as a single HTTPS endpoint (unblock.oxylabs.io:60000) that handles proxy rotation, browser fingerprinting, JavaScript rendering, CAPTCHA solving, and bot-mitigation bypass automatically. Used as a drop-in proxy in any HTTP client; returns rendered HTML. Supports custom headers, geo-targeting, and beta browser instructions.

- **Human URL:** [https://developers.oxylabs.io/products/web-unblocker](https://developers.oxylabs.io/products/web-unblocker)
- **Base URL:** `https://unblock.oxylabs.io:60000`

#### Tags

- Anti-Bot
- Bot Mitigation Bypass
- CAPTCHA Solving
- JavaScript Rendering
- Proxy
- Web Unblocker

#### Properties

- [Documentation](https://developers.oxylabs.io/products/web-unblocker)
- [Getting Started](https://developers.oxylabs.io/get-started/quick-start-web-unblocker)
- [Documentation](https://oxylabs.io/products/web-unblocker)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs Headless Browser

Cloud-hosted headless browser service exposed via Chrome DevTools Protocol (CDP) and Selenium / Playwright / Puppeteer. Each remote browser session is geo-targetable, includes premium proxy egress, and supports script automation, screenshots, network capture, and complex interaction flows at scale.

- **Human URL:** [https://developers.oxylabs.io/products/headless-browser](https://developers.oxylabs.io/products/headless-browser)
- **Base URL:** `https://headless.oxylabs.io`

#### Tags

- Browser Automation
- CDP
- Headless Browser
- Playwright
- Puppeteer
- Selenium

#### Properties

- [Documentation](https://developers.oxylabs.io/products/headless-browser)
- [Getting Started](https://developers.oxylabs.io/get-started/quick-start-headless-browser)
- [Documentation](https://oxylabs.io/products/headless-browser)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs Residential Proxies

Rotating residential IP pool (195M+ IPs across 195 countries) for accessing geo-fenced and consumer-protected web content. HTTP/HTTPS/SOCKS5 endpoints with country, city, ASN, state, coordinates, and ZIP/postal code targeting. Supports sticky sessions, US/EU/global entry nodes, and a dedicated China entry node.

- **Human URL:** [https://developers.oxylabs.io/proxies/residential-proxies](https://developers.oxylabs.io/proxies/residential-proxies)
- **Base URL:** `https://pr.oxylabs.io:7777`

#### Tags

- Geo-Targeting
- Proxies
- Residential Proxies
- Rotating Proxies

#### Properties

- [Documentation](https://developers.oxylabs.io/proxies/residential-proxies)
- [Getting Started](https://developers.oxylabs.io/get-started/quick-start-proxies)
- [Documentation](https://oxylabs.io/products/residential-proxy-pool)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs Residential Public API

Sub-user management and usage-statistics API for residential proxy customers. Exchanges HTTP Basic credentials for a bearer token via /login, then exposes endpoints for creating, listing, updating, and deleting sub-users; querying traffic limits and statuses; and pulling per-sub-user target and client statistics.

- **Human URL:** [https://developers.oxylabs.io/products/proxies/residential-proxies/public-api](https://developers.oxylabs.io/products/proxies/residential-proxies/public-api)
- **Base URL:** `https://residential-api.oxylabs.io/v2`

#### Tags

- Proxies
- Residential Proxies
- Sub-User Management
- Usage Statistics

#### Properties

- [Documentation](https://developers.oxylabs.io/products/proxies/residential-proxies/public-api)
- [OpenAPI](openapi/oxylabs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs Datacenter Proxies

High-speed shared, dedicated, and self-service datacenter IP proxies for fast public data gathering. Includes a free trial pool of datacenter IPs. Authentication via username/password or IP whitelisting. HTTP, HTTPS, and SOCKS5 supported.

- **Human URL:** [https://developers.oxylabs.io/proxies/datacenter-proxies](https://developers.oxylabs.io/proxies/datacenter-proxies)
- **Base URL:** `https://dc.oxylabs.io:8000`

#### Tags

- Datacenter Proxies
- Dedicated Proxies
- Proxies
- Shared Proxies

#### Properties

- [Documentation](https://developers.oxylabs.io/proxies/datacenter-proxies)
- [Documentation](https://oxylabs.io/products/datacenter-proxies)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs Mobile Proxies

5G / 4G / 3G / LTE rotating mobile IP proxies sourced from real mobile carriers. Country, city, coordinates, and ASN/carrier targeting. Designed for use cases that require high-trust mobile-network egress (ad verification, app testing, mobile-only content).

- **Human URL:** [https://developers.oxylabs.io/products/proxies/mobile-proxies](https://developers.oxylabs.io/products/proxies/mobile-proxies)
- **Base URL:** `https://pr.oxylabs.io:7777`

#### Tags

- 5G
- LTE
- Mobile Proxies
- Proxies

#### Properties

- [Documentation](https://developers.oxylabs.io/products/proxies/mobile-proxies)
- [Documentation](https://oxylabs.io/products/mobile-proxies)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs ISP Proxies

Static residential (ISP) proxies that combine the legitimacy of residential IPs with the speed and stability of datacenter infrastructure. Dedicated and shared options across major geographies, with both self-service and enterprise (dedicated ISP enterprise) tiers.

- **Human URL:** [https://developers.oxylabs.io/proxies/isp-proxies](https://developers.oxylabs.io/proxies/isp-proxies)
- **Base URL:** `https://isp.oxylabs.io:8001`

#### Tags

- ISP Proxies
- Proxies
- Static Residential

#### Properties

- [Documentation](https://developers.oxylabs.io/proxies/isp-proxies)
- [Documentation](https://developers.oxylabs.io/proxies/dedicated-isp-enterprise)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs Dashboard API

Account-management API for Oxylabs customers. Exposes usage statistics, filter instances, billing data, and team / sub-account management primitives used by the Oxylabs customer dashboard. Authentication via bearer token.

- **Human URL:** [https://developers.oxylabs.io/dashboard/dashboard-api](https://developers.oxylabs.io/dashboard/dashboard-api)
- **Base URL:** `https://api.oxylabs.io`

#### Tags

- Account Management
- Dashboard
- Statistics
- Usage Reporting

#### Properties

- [Documentation](https://developers.oxylabs.io/dashboard/dashboard-api)
- [Documentation](https://developers.oxylabs.io/dashboard/teams)
- [Documentation](https://developers.oxylabs.io/dashboard/billing-information)
- [OpenAPI](openapi/oxylabs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs AI Studio

Suite of AI-native data acquisition primitives — AI Scraper (turn any URL into structured JSON or markdown from a natural-language schema), AI Crawler (URL-seed crawl + extract), AI Map (LLM-driven sitemap discovery), Browser Agent (multi-step agentic browser actions), and AI Search (natural-language query → structured web data). Exposed via REST APIs and official TypeScript and Python SDKs.

- **Human URL:** [https://oxylabs.io/products/scraper-api/ai](https://oxylabs.io/products/scraper-api/ai)
- **Base URL:** `https://api.oxylabs.io`

#### Tags

- AI Agents
- AI Scraping
- Browser Agent
- LLM
- Structured Extraction

#### Properties

- [Documentation](https://developers.oxylabs.io/get-started/quick-start-ai-studio)
- [Documentation](https://oxylabs.io/products/scraper-api/ai)
- [SDK](https://github.com/oxylabs/oxylabs-ai-studio-py)
- [SDK](https://github.com/oxylabs/oxylabs-ai-studio-js)
- [Plugin](https://github.com/oxylabs/oxylabs-ai-studio-openclaw)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs MCP Server

Official Model Context Protocol server that exposes Oxylabs Web Scraper API, AI Studio, and proxy capabilities as MCP tools to Claude Code, Claude Desktop, Cursor, and any MCP-compatible AI client. Includes universal scrape, Google search, Amazon product, and AI-Scraper tools out of the box.

- **Human URL:** [https://github.com/oxylabs/oxylabs-mcp](https://github.com/oxylabs/oxylabs-mcp)
- **Base URL:** `https://github.com/oxylabs/oxylabs-mcp`

#### Tags

- AI Agents
- Claude
- Cursor
- MCP
- Model Context Protocol

#### Properties

- [Documentation](https://github.com/oxylabs/oxylabs-mcp)
- [M C P Server](https://github.com/oxylabs/oxylabs-mcp)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Oxylabs Datasets

Pre-collected, ready-to-deliver web datasets for e-commerce (Amazon, Google Shopping, Best Buy, Walmart, eBay), job postings (Indeed, Glassdoor, LinkedIn), product reviews, company intelligence, community-and-code, and real-estate. Delivered as bulk files (JSON/CSV/Parquet) or via S3/GCS/Azure Blob; refreshed on schedule. Custom-dataset service available on request.

- **Human URL:** [https://oxylabs.io/products/datasets](https://oxylabs.io/products/datasets)
- **Base URL:** `https://oxylabs.io/products/datasets`

#### Tags

- Bulk Data
- Company Data
- Datasets
- E-Commerce Data
- Job Posting Data
- Web Data

#### Properties

- [Documentation](https://oxylabs.io/products/datasets)
- [Documentation](https://oxylabs.io/products/datasets/ecommerce)
- [Documentation](https://oxylabs.io/products/datasets/job-posting)
- [Documentation](https://oxylabs.io/products/datasets/community-and-code)
- [Postman Collection](collections/oxylabs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/oxylabs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://oxylabs.io/)
- [Website](https://oxylabs.io/)
- [Documentation](https://developers.oxylabs.io/)
- [Documentation](https://developers.oxylabs.io/api-targets)
- [Documentation](https://oxylabs.io/products)
- [Documentation](https://oxylabs.io/integrations)
- [Getting Started](https://developers.oxylabs.io/get-started/quick-start-proxies)
- [Sign Up](https://dashboard.oxylabs.io/en/registration)
- [Dashboard](https://dashboard.oxylabs.io/)
- [Status Page](https://uptime.oxylabs.io/)
- [Changelog](https://developers.oxylabs.io/changelog)
- [Changelog](https://oxylabs.io/developers/release-notes)
- [R S S](https://developers.oxylabs.io/rss.xml)
- [L L Ms Txt](https://oxylabs.io/llms.txt)
- [Help Center](https://developers.oxylabs.io/help-center)
- [Support](https://oxylabs.io/contact-us)
- [Support](https://developers.oxylabs.io/have-a-question)
- [Pricing](https://oxylabs.io/pricing)
- [Blog](https://oxylabs.io/blog)
- [Training](https://experts.oxylabs.io/lessons)
- [Training](https://oxylabs.io/resources)
- [Careers](https://career.oxylabs.io/)
- [Privacy Policy](https://oxylabs.io/legal/privacy)
- [Terms of Service](https://oxylabs.io/legal/terms-of-service)
- [Trust Center](https://oxylabs.io/legal)
- [Documentation](https://oxylabs.io/sustainability)
- [Documentation](https://oxylabs.io/core-values)
- [Press](https://oxylabs.io/press-area)
- [About Us](https://oxylabs.io/about-us)
- [LinkedIn](https://www.linkedin.com/company/oxylabs-io)
- [Twitter](https://twitter.com/oxylabs)
- [GitHub Organization](https://github.com/oxylabs)
- [Documentation](https://github.com/oxylabs/oxylabs-readme)
- [M C P Server](https://github.com/oxylabs/oxylabs-mcp)
- [Agent Skill](https://github.com/oxylabs/agent-skills)
- [SDK](https://github.com/oxylabs/oxylabs-sdk-python)
- [SDK](https://github.com/oxylabs/oxylabs-sdk-go)
- [SDK](https://github.com/oxylabs/oxylabs-ai-studio-py)
- [SDK](https://github.com/oxylabs/oxylabs-ai-studio-js)
- [Plugin](https://github.com/oxylabs/oxylabs-ai-studio-openclaw)
- [SDK](https://github.com/oxylabs/browser-agent-py)
- [SDK](https://github.com/oxylabs/ai-crawler-py)
- [SDK](https://github.com/oxylabs/ai-map-py)
- [SDK](https://github.com/oxylabs/AI-Search-py)
- [SDK](https://github.com/oxylabs/ai-scraper-py)
- [SDK](https://github.com/oxylabs/OxyMouse)
- [SDK](https://github.com/oxylabs/OxyParser)
- [Code Examples](https://github.com/oxylabs/web-unblocker)
- [Tool](https://github.com/oxylabs/Oxylabs-Web-Scraper-API-Scheduler)
- [Tool](https://github.com/oxylabs/proxy-chrome-extension)
- [Code Examples](https://github.com/oxylabs/proxy-integrations)
- [Code Examples](https://github.com/oxylabs/product-integrations)
- [Code Examples](https://github.com/oxylabs/quick-start-guide)
- [Code Examples](https://github.com/oxylabs/web-scraping-tutorials)
- [Plans](plans/oxylabs-plans-pricing.yml)
- [Rate Limits](rate-limits/oxylabs-rate-limits.yml)
- [Fin Ops](finops/oxylabs-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
