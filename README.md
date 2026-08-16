# AI Build Case Studies

Anonymized case studies of AI systems I designed, built, shipped, and operate. Each write-up covers the problem, the design decisions, the boundaries drawn around the model, and the honest status of the system.

Built by **Patrick Joseph Panuncillon**, Director for AI Strategy and Growth.

**Start here: [Authorship, provenance, and verification](authorship-and-verification.html)** sets out what this repository claims, what it expressly does not claim, the build ledger, four tiers of independent verification, and the fixed disclosure standard every page is written to.

---

## The builds

A six-system production AI stack for a multi-trade, multi-market field-service business, plus the reliability layer underneath it and the search and lifecycle programmes beside it. Sole architect and builder on every one.

| System | Status | What it is |
|---|---|---|
| [AI Reply Assistant](ai-sms-sales-assistant.html) | Live, in daily production | Retrieval-grounded reply drafting inside the team's existing messaging tool, with a routing and caching layer, a nightly learning loop, and a human sending every reply. |
| [Reply Training Console](ai-reply-training-console.html) | Live | A safe training environment that captures a distinct voice per department without touching production. |
| [Call-Time Dispatch Assistant](ai-call-dispatch-assistant.html) | Live, in tuning | A booking panel that fills itself during the call, matching a qualified technician and offering an arrival window from live road distances. |
| [Dispatch Understudy](ai-dispatch-understudy.html) | Live, capturing | A narrow, opt-in capture that turns expert scheduling judgment into reviewable rules. Scheduling actions only, customer data masked, stays on company systems. |
| [Production Reliability Layer](production-reliability-layer.html) | Live, under all of the above | Twenty-eight unattended workflows where health is proven by fresh dated output, an independent watchdog runs twice daily, and silence raises an alarm. |
| [Search, Review, and Lifecycle](ai-search-reputation-lifecycle.html) | Live, multi-location | Answer-engine visibility, AI-drafted review responses behind a required human approval gate, and CRM lifecycle sequences. |
| [Campaign Automation](ai-campaign-automation.html) | In build | Self-serve campaigns from a brand-locked template behind a required human approval gate and a single scheduling path. |
| [Invoice Automation](ai-invoice-automation.html) | In build, in diagnosis | Deterministic drafting from a versioned rules registry behind a fail-closed validation gate, where the model never touches a total, a tax decision, or an account. |

Status labels are used consistently. **Live** means running in production and in daily use. **In tuning** means live and being scored against real behaviour. **In build** means implemented but not yet in production. **Scoped** means specified and not built. Nothing in build is presented as shipped.

---

## Authorship, not ownership

This repository is a record of **authorship**. It states which systems I personally designed, built, shipped, and operate, timestamped by the commit history of this repository.

It is **not** a claim of ownership. Systems built in the course of an employment or client engagement belong to that employer or client. Intellectual property in every system described here rests with the organisation that commissioned it. Nothing in this repository transfers, licenses, or offers any part of it, and nothing here is published on behalf of, or with the endorsement of, any employer or client.

See [NOTICE.md](NOTICE.md) for the full statement.

---

## Disclosure standard

Every page is written to one fixed standard. The following are withheld without exception:

- The name of the employer or client, and any detail sufficient to identify them
- Source code, in whole or in part
- Prompts, prompt templates, and system instructions
- Credentials, keys, tokens, endpoints, hostnames, and internal identifiers
- Schemas, data models, and internal record structures
- Customer data of any kind, in any form, including anonymised or composited
- Named third-party vendors in the client's operational stack
- Exact commercial figures, contract terms, and pricing
- Screenshots or recordings of live systems
- Any material subject to a confidentiality obligation

Figures that appear are rounded, banded, or expressed as ranges, and only where the band itself carries no confidential information. Third-party vendors are described by category rather than by name. Every diagram is drawn in CSS from public description, so there is nothing in this repository that could have leaked.

---

## Notes

- Each page is a single self-contained HTML file. Inline CSS, system fonts, no external requests, no tracking, no analytics. Open any of them in a browser, online or off.
- If anything here is inaccurate, or a rights holder considers any part of it to exceed the disclosure standard above, contact me and it will be corrected or removed promptly.

**Patrick Joseph Panuncillon** · Davao City, Philippines
[consultwithpatrick@gmail.com](mailto:consultwithpatrick@gmail.com) · [LinkedIn](https://www.linkedin.com/in/patrickjosephpanuncillon)
