# Oxylabs (oxylabs)

Oxylabs is a Lithuanian (Vilnius-based) web intelligence platform providing premium proxy networks
(Residential, Datacenter, Mobile, ISP, Dedicated), web data acquisition APIs (Web Scraper API, SERP
Scraper API, E-Commerce Scraper API, Real Estate Scraper API, Web Unblocker, Headless Browser),
AI-native scraping tools (AI Studio — AI Scraper, AI Crawler, AI Map, Browser Agent, AI Search), an
official MCP server, and ready-to-deliver datasets. The platform serves large-scale public web data
extraction for e-commerce intelligence, brand protection, market research, SEO/SERP monitoring,
cybersecurity, and AI/LLM training pipelines.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/oxylabs/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Kind:** contract
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

AI Web Scraping, Bot Mitigation Bypass, CAPTCHA Solving, Data Extraction, Datacenter Proxies, Datasets,
E-Commerce Data, Headless Browser, ISP Proxies, Mobile Proxies, Proxies, Residential Proxies, SERP,
Scraper API, Scraping, Web Data, Web Intelligence, Web Unblocker

## Timestamps

- **Created:** 2026-03-29
- **Modified:** 2026-05-25

## APIs

### Oxylabs Web Scraper API
General-purpose web scraping API with two delivery modes — Realtime (synchronous) against
`realtime.oxylabs.io` and Push-Pull (asynchronous job submission with polling or callback) against
`data.oxylabs.io`. Supports JavaScript rendering, geo-targeting, locale, custom headers, parsing
instructions, browser instructions, and pluggable parsers.

- **Human URL:** https://developers.oxylabs.io/scraping-solutions/web-scraper-api
- **Base URL:** `https://realtime.oxylabs.io/v1`
- **OpenAPI:** [openapi/oxylabs-openapi.yml](openapi/oxylabs-openapi.yml)
- **Naftiko capability:** [capabilities/oxylabs.yaml](capabilities/oxylabs.yaml)

### Oxylabs SERP Scraper API
Search-engine results scraping for Google (Search, Ads, Images, Lens, Maps, Suggest, Shopping, Travel,
Trends, AI Overviews, AI Mode), Bing, Baidu, Yandex, DuckDuckGo, Naver, and others.

- **Docs:** https://developers.oxylabs.io/api-targets/search-engines

### Oxylabs E-Commerce Scraper API
Pre-built scraping targets for Amazon, Walmart, eBay, Etsy, Target, Best Buy, AliExpress, 1688, Shein,
Lazada, Trip, Trivago, MercadoLivre, Falabella, Rakuten and many more.

- **Docs:** https://developers.oxylabs.io/scraping-solutions/web-scraper-api/targets

### Oxylabs Web Unblocker
AI-driven proxy that handles rotation, fingerprinting, JavaScript rendering, and CAPTCHA solving
automatically through a single HTTPS endpoint.

- **Docs:** https://developers.oxylabs.io/products/web-unblocker
- **Base URL:** `https://unblock.oxylabs.io:60000`

### Oxylabs Headless Browser
Cloud-hosted headless browser exposed via Chrome DevTools Protocol, Playwright, Puppeteer, and
Selenium.

- **Docs:** https://developers.oxylabs.io/products/headless-browser

### Oxylabs Residential Proxies
Rotating residential IP pool (195M+ IPs across 195 countries) with country, city, state, ASN,
coordinates, and ZIP/postal-code targeting.

- **Docs:** https://developers.oxylabs.io/proxies/residential-proxies
- **Base URL:** `https://pr.oxylabs.io:7777`

### Oxylabs Residential Public API
Sub-user management and usage-statistics API for residential proxy customers.

- **Docs:** https://developers.oxylabs.io/products/proxies/residential-proxies/public-api
- **Base URL:** `https://residential-api.oxylabs.io/v2`
- **OpenAPI:** [openapi/oxylabs-openapi.yml](openapi/oxylabs-openapi.yml)

### Oxylabs Datacenter Proxies
Shared, dedicated, and self-service datacenter proxies, including a free trial datacenter pool.

- **Docs:** https://developers.oxylabs.io/proxies/datacenter-proxies

### Oxylabs Mobile Proxies
5G / 4G / 3G / LTE rotating mobile IPs with carrier (ASN) and geo targeting.

- **Docs:** https://developers.oxylabs.io/products/proxies/mobile-proxies

### Oxylabs ISP Proxies
Static residential proxies combining residential IP legitimacy with datacenter performance; includes
Dedicated ISP Enterprise tier.

- **Docs:** https://developers.oxylabs.io/proxies/isp-proxies

### Oxylabs Dashboard API
Account-management API for usage statistics, filters, billing data, and team / sub-account
management.

- **Docs:** https://developers.oxylabs.io/dashboard/dashboard-api
- **Base URL:** `https://api.oxylabs.io`
- **OpenAPI:** [openapi/oxylabs-openapi.yml](openapi/oxylabs-openapi.yml)

### Oxylabs AI Studio
AI Scraper, AI Crawler, AI Map, Browser Agent, and AI Search — natural-language driven structured
web-data acquisition. Official TypeScript and Python SDKs.

- **Docs:** https://developers.oxylabs.io/get-started/quick-start-ai-studio

### Oxylabs MCP Server
Official Model Context Protocol server exposing Oxylabs Web Scraper API, AI Studio, and proxy
capabilities to Claude Code, Claude Desktop, Cursor, and any MCP-compatible AI client.

- **Repo:** https://github.com/oxylabs/oxylabs-mcp

### Oxylabs Datasets
Ready-to-deliver datasets for e-commerce, job posting, product reviews, company intelligence,
community-and-code, and real-estate. Custom dataset service on request.

- **Docs:** https://oxylabs.io/products/datasets

## Generated Artifacts

| Type | Path |
|------|------|
| OpenAPI | [openapi/oxylabs-openapi.yml](openapi/oxylabs-openapi.yml) |
| Naftiko capability | [capabilities/oxylabs.yaml](capabilities/oxylabs.yaml) |
| Plans (API Commons) | [plans/oxylabs-plans-pricing.yml](plans/oxylabs-plans-pricing.yml) |
| Rate Limits (API Commons) | [rate-limits/oxylabs-rate-limits.yml](rate-limits/oxylabs-rate-limits.yml) |
| FinOps | [finops/oxylabs-finops.yml](finops/oxylabs-finops.yml) |

## Common Properties

- **Portal / Website:** https://oxylabs.io/
- **Developer Documentation:** https://developers.oxylabs.io/
- **API Targets Catalog:** https://developers.oxylabs.io/api-targets
- **Products Overview:** https://oxylabs.io/products
- **Integrations Catalog:** https://oxylabs.io/integrations
- **Quick Start (Proxies):** https://developers.oxylabs.io/get-started/quick-start-proxies
- **Sign Up:** https://dashboard.oxylabs.io/en/registration
- **Dashboard:** https://dashboard.oxylabs.io/
- **Status / Uptime:** https://uptime.oxylabs.io/
- **Changelog:** https://developers.oxylabs.io/changelog
- **Release Notes:** https://oxylabs.io/developers/release-notes
- **RSS:** https://developers.oxylabs.io/rss.xml
- **llms.txt:** https://oxylabs.io/llms.txt
- **Help Center:** https://developers.oxylabs.io/help-center
- **Pricing:** https://oxylabs.io/pricing
- **Blog:** https://oxylabs.io/blog
- **Experts / Training:** https://experts.oxylabs.io/lessons
- **GitHub:** https://github.com/oxylabs
- **LinkedIn:** https://www.linkedin.com/company/oxylabs-io
- **Twitter:** https://twitter.com/oxylabs

## SDKs, Tools, and Integrations

- Python SDK (Web Scraper API) — https://github.com/oxylabs/oxylabs-sdk-python
- Go SDK (Web Scraper API) — https://github.com/oxylabs/oxylabs-sdk-go
- AI Studio Python SDK — https://github.com/oxylabs/oxylabs-ai-studio-py
- AI Studio JavaScript / TypeScript SDK — https://github.com/oxylabs/oxylabs-ai-studio-js
- AI Studio Openclaw plugin — https://github.com/oxylabs/oxylabs-ai-studio-openclaw
- AI Browser Agent (Python) — https://github.com/oxylabs/browser-agent-py
- AI Crawler (Python) — https://github.com/oxylabs/ai-crawler-py
- AI Map (Python) — https://github.com/oxylabs/ai-map-py
- AI Search (Python) — https://github.com/oxylabs/AI-Search-py
- AI Scraper (Python) — https://github.com/oxylabs/ai-scraper-py
- OxyMouse (mouse-movement algorithms) — https://github.com/oxylabs/OxyMouse
- OxyParser — https://github.com/oxylabs/OxyParser
- Oxylabs MCP server — https://github.com/oxylabs/oxylabs-mcp
- Official Agent Skills — https://github.com/oxylabs/agent-skills
- Oxy Proxy Chrome Extension — https://github.com/oxylabs/proxy-chrome-extension
- Web Scraper API Scheduler — https://github.com/oxylabs/Oxylabs-Web-Scraper-API-Scheduler
- Proxy integrations (Selenium, Playwright, Puppeteer, aiohttp) — https://github.com/oxylabs/proxy-integrations

## Maintainers

- **FN:** Kin Lane
- **Email:** kin@apievangelist.com
- **X:** apievangelist
- **URL:** https://apievangelist.com
