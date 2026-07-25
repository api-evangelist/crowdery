# Crowdery

Crowdery was a consumer retail and e-commerce startup backed by a16z, listed on the
[a16z investment list](https://a16z.com/investment-list/). Its product inverted the
traditional retail sales model: shoppers voted on product designs from a curated set,
Crowdery assembled a personalized marketplace from each shopper's top picks, and the
highest-voted products were opened for pre-order at a discount. For brands it offered
consumer feedback loops, pre-production demographic analytics, and pre-orders intended
to de-risk manufacturing runs.

Backed by: a16z

## Status: defunct — no API surface

As of the July 2026 enrichment pass, Crowdery appears defunct and never shipped a
public API or developer program:

- `crowdery.com` (apex) serves a Doteasy hosting placeholder page; HTTPS does not respond.
- `www.crowdery.com` still delegates to `crowdery-prelaunch.herokuapp.com`, a
  decommissioned Heroku prelaunch app that returns 404.
- No developer portal, documentation, OpenAPI, GitHub organization, or `/.well-known/`
  discovery documents were found.
- The a16z portfolio source record itself flags `is_api_provider: false`.

The last substantive archived homepage is from 2013:
[web.archive.org snapshot](http://web.archive.org/web/20131220212321/http://www.crowdery.com/).

Note: the `WISDelft/crowdery-*` GitHub repositories are an unrelated TU Delft academic
crowdsourcing framework, not this company.

## Artifacts

- `security/crowdery-domain-security.yml` — live DNS/TLS probe (no HTTPS, no DNSSEC,
  no CAA, no DMARC; SPF present via Mailgun).
