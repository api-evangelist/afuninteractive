# AFUN Interactive

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

AFUN Interactive (에이펀인터렉티브) is a Seoul-based real-time 3D content production studio founded in
2017 that builds digital humans, virtual celebrities and high-quality real-time 3D media. Its four
stated service lines are Digital Celebrity Management, Digital Human, Ganimation (a real-time
animation/game hybrid genre that won at the 2018 Venice International Film Festival), and High
Quality Realtime 3D Contents. Through its subsidiary VV Entertainment it produces and manages the
virtual K-pop artist APOKI.

## Why this profile is thin

**No API surface — no developer program.** AFUN Interactive is a work-for-hire production and
artist-management business. Its entire public web presence is a six-page Korean corporate brochure
(About Us, Business Area, Our Works, News, Career, Contact Us) served from
`www.afun-interactive.com` behind a Cafe24 "CUPID" AES-cookie bot challenge. The challenge was
solved for this profile and every page was read: there is no developer, docs, API or downloads
section anywhere on the site. Contract discovery (2026-09-12) additionally found no OpenAPI,
Swagger, GraphQL, AsyncAPI, MCP manifest, A2A agent card, `llms.txt`, `apis.json` or any
`/.well-known/` document on any host the company operates; no GitHub organization under any
AFUN / APOKI / VV name; and no first-party package on npm, PyPI, crates.io or RubyGems.

Note on soft-404s: behind the bot challenge the origin answers HTTP **200** with an HTML body
titled "404 Not found Error" for every unknown path. A control path
(`/zzz-control-does-not-exist-98765`) returned a byte-for-byte identical body, which is how each
200 in `well-known/afuninteractive-well-known.yml` is recorded as an absence rather than a document.

## Links

- Website — https://www.afun-interactive.com/
- Business Area — https://www.afun-interactive.com/business/sub01.html
- Our Works — https://www.afun-interactive.com/works/sub01.html
- News — https://www.afun-interactive.com/news/sub01.html
- APOKI (virtual artist, via VV Entertainment) — https://apoki.ai/
- VV Entertainment (subsidiary) — https://vv-ent.com/
- Secondary-market listing — https://equityzen.com/company/afuninteractive
