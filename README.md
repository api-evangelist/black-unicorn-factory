# Black Unicorn Factory

Black Unicorn Factory (BUF) is a Los Angeles based pre-IPO business accelerator that prepares companies led by founders from underrepresented communities for direct listings on national stock exchanges, positioning equity rather than debt as the route to capital. Its programs run a four-step readiness pathway — foundation and readiness assessment, compliance and corporate structure, SEC filing and disclosure, and market readiness — alongside the New Black Wall Street pre-IPO program and the Follow Me For Equity (FMFE) platform, an iOS and Android application through which individuals earn stock in participating pre-IPO companies by completing verified social engagement tasks instead of investing cash.

- Website: https://blackunicornfactory.com/
- Follow Me For Equity: https://followmeforequity.com/
- Secondary market listing: https://forgeglobal.com/black-unicorn-factory_stock/

## API surface

**Black Unicorn Factory publishes no public API.** As of 2026-08-02 a full contract-discovery
pass across every company host found no OpenAPI, Swagger, GraphQL, AsyncAPI, MCP server,
A2A agent card, developer portal, SDK, CLI, or `/.well-known/` discovery document. The only
machine-readable endpoint present is the incidental WordPress REST API root at
`https://blackunicornfactory.com/wp-json/` (HTTP 200) — CMS plumbing for the marketing
site, not a product API — so it is deliberately not catalogued as a company API.

Probe evidence is recorded in `well-known/black-unicorn-factory-well-known.yml`.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Well-known / contract discovery | `well-known/black-unicorn-factory-well-known.yml` | probed |
| Domain security | `security/black-unicorn-factory-domain-security.yml` | probed |
| llms.txt | `llms/black-unicorn-factory-llms.txt` | generated |
