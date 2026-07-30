# Lemonaide

Lemonaide is a Bangkok-headquartered B2B used-car and insurtech platform operating across Southeast Asia, selling software and operated services to used-car dealerships and insurers with the stated mission of reducing asymmetric information in the automotive market.

**Products:** Dealer Management System, Dealer CRM System, Digital Escrow, after-sales BPO, Warranty TPA, Digital Roadside Service, Vehicle Inspection, Audit Assessment.

**Website:** https://lemonaide.co.th (lemonaidegroup.com redirects here)

**Backed by:** 500 Global

## API surface

As of the 2026-07-19 enrichment pass, Lemonaide publishes **no public API**, developer portal, API documentation, OpenAPI/AsyncAPI specification, SDK, CLI, MCP server, sandbox, changelog, or status page. The `/.well-known/` discovery surface and `/llms.txt` are absent — the host is a WordPress site that soft-404s (HTTP 200 plus the homepage body) on every unknown path, so status codes alone are misleading here. See `well-known/lemonaide-well-known.yml`.

Note: `lemonaide.ai` is an unrelated company and is not covered by this profile.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Conformance | `conformance/lemonaide-conformance.yml` | searched |
| Well-Known probe | `well-known/lemonaide-well-known.yml` | probed |
| Domain security | `security/lemonaide-domain-security.yml` | probed |
| llms.txt | `llms/lemonaide-llms.txt` | generated |
