# Ditto Audio

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

ditto-audio is a company surfaced via the API Evangelist harvest backlog (source: mcp-registry) and added to the network as a stub for full-pipeline profiling.

**Areas:** Text-to-Speech · Voice Plugins · Audiobooks · Neural Voice · On‑device AI

## Ditto Audio on APIs.io

Everything profiled for Ditto Audio is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ditto-audio/](https://apis.io/providers/ditto-audio/)** — or go straight to one of the APIs or properties below.

### APIs (30)

- [Ditto Audio Admin/db API](https://apis.io/apis/ditto-audio/ditto-audio-admin-db-api/) — Admin — generic DB browser
- [Ditto Audio Admin/inference API](https://apis.io/apis/ditto-audio/ditto-audio-admin-inference-api/) — Admin — inspect & manage inference jobs
- [Ditto Audio Admin/models API](https://apis.io/apis/ditto-audio/ditto-audio-admin-models-api/) — Admin — manage voice models & uploads
- [Ditto Audio API Keys API](https://apis.io/apis/ditto-audio/ditto-audio-api-keys-api/) — Create, rename & revoke the bearer keys used on /v1/audio/*
- [Ditto Audio Audio API](https://apis.io/apis/ditto-audio/ditto-audio-audio-api/) — THE public inference API — streaming text→speech, the voice catalogue & the supported languages. Authenticate with an API key.
- [Ditto Audio Auth API](https://apis.io/apis/ditto-audio/ditto-audio-auth-api/) — Sign up, sign in (email + Google), email verification & password reset
- [Ditto Audio Chunks API](https://apis.io/apis/ditto-audio/ditto-audio-chunks-api/) — Content-addressed rendered-audio chunk store (the reader backend’s S3 cache)
- [Ditto Audio Docs API](https://apis.io/apis/ditto-audio/ditto-audio-docs-api/) — The machine-readable OpenAPI documents these docs are generated from
- [Ditto Audio Favorites API](https://apis.io/apis/ditto-audio/ditto-audio-favorites-api/) — The favorites API from Ditto Audio — 2 operation(s) for favorites.
- [Ditto Audio Health API](https://apis.io/apis/ditto-audio/ditto-audio-health-api/) — Service liveness probe
- [Ditto Audio Inference API](https://apis.io/apis/ditto-audio/ditto-audio-inference-api/) — The pure text+model→audio inference service — stateless, no book/persistence awareness
- [Ditto Audio license (native client) API](https://apis.io/apis/ditto-audio/ditto-audio-license-native-client-api/) — The license (native client) API from Ditto Audio — 3 operation(s) for license (native client).
- [Ditto Audio Licenses API](https://apis.io/apis/ditto-audio/ditto-audio-licenses-api/) — ditto-native desktop app — license activation & heartbeat
- [Ditto Audio Models API](https://apis.io/apis/ditto-audio/ditto-audio-models-api/) — Voice-model catalog — browse, download & upload custom voices
- [Ditto Audio OAuth API](https://apis.io/apis/ditto-audio/ditto-audio-oauth-api/) — The oauth API from Ditto Audio — 10 operation(s) for oauth.
- [Ditto Audio Pre Render API](https://apis.io/apis/ditto-audio/ditto-audio-pre-render-api/) — Distributed render offload — nodes, jobs, assignments & live presence
- [Ditto Audio Pre Render Cloud API](https://apis.io/apis/ditto-audio/ditto-audio-pre-render-cloud-api/) — The pre-render-cloud API from Ditto Audio — 6 operation(s) for pre-render-cloud.
- [Ditto Audio Products API](https://apis.io/apis/ditto-audio/ditto-audio-products-api/) — Desktop products — the Ditto app & DAW plugins as one-time purchases; unlocked by any active plan too
- [Ditto Audio Reader API](https://apis.io/apis/ditto-audio/ditto-audio-reader-api/) — Audiobooks — persist a book, render its narration in the background, stream the result
- [Ditto Audio Releases API](https://apis.io/apis/ditto-audio/ditto-audio-releases-api/) — ditto-native desktop app — update channels & release manifests
- [Ditto Audio Rtc API](https://apis.io/apis/ditto-audio/ditto-audio-rtc-api/) — WebRTC signaling & TURN credentials (distributed render offload)
- [Ditto Audio Studio API](https://apis.io/apis/ditto-audio/ditto-audio-studio-api/) — The web studio’s private per-user library of finished renders & conversions
- [Ditto Audio Subscription API](https://apis.io/apis/ditto-audio/ditto-audio-subscription-api/) — Cloud plans, checkout & billing (Stripe)
- [Ditto Audio Sync API](https://apis.io/apis/ditto-audio/ditto-audio-sync-api/) — Reader cloud sync — settings, push/pull delta
- [Ditto Audio Sync/data API](https://apis.io/apis/ditto-audio/ditto-audio-sync-data-api/) — Reader cloud sync — bookmarks, annotations, models, audio
- [Ditto Audio Sync/library API](https://apis.io/apis/ditto-audio/ditto-audio-sync-library-api/) — Reader cloud sync — books, reading progress, file backup
- [Ditto Audio Training API](https://apis.io/apis/ditto-audio/ditto-audio-training-api/) — Voice-model training / cloning jobs
- [Ditto Audio update (native client) API](https://apis.io/apis/ditto-audio/ditto-audio-update-native-client-api/) — The update (native client) API from Ditto Audio — 3 operation(s) for update (native client).
- [Ditto Audio Usage API](https://apis.io/apis/ditto-audio/ditto-audio-usage-api/) — Your own API usage & analytics — totals, time series and recent requests
- [Ditto Audio Users API](https://apis.io/apis/ditto-audio/ditto-audio-users-api/) — Account profile & management

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ditto Audio Agentic Access](https://apis.io/agentic-access/ditto-audio/ditto-audio-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CreateAudioBatchDto](https://apis.io/schemas/ditto-audio/ditto-audio-create-audio-batch-dto/)
- [CreateCustomVoiceDto](https://apis.io/schemas/ditto-audio/ditto-audio-create-custom-voice-dto/)
- [CreateVoiceModelDto](https://apis.io/schemas/ditto-audio/ditto-audio-create-voice-model-dto/)
- [SpeechBatchDto](https://apis.io/schemas/ditto-audio/ditto-audio-speech-batch-dto/)
- [SpeechDto](https://apis.io/schemas/ditto-audio/ditto-audio-speech-dto/)
- [UpdateVoiceModelDto](https://apis.io/schemas/ditto-audio/ditto-audio-update-voice-model-dto/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ditto Audio Context](https://apis.io/jsonld/ditto-audio/ditto-audio-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Ditto Audio API Rules](https://apis.io/rules/ditto-audio/ditto-audio-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ditto Audio Authentication](https://apis.io/security/ditto-audio/ditto-audio-authentication/)
- [Ditto Audio Domain Security](https://apis.io/security/ditto-audio/ditto-audio-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ditto Audio Plans Pricing](https://apis.io/plans/ditto-audio/ditto-audio-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://ditto.audio/)
- [Documentation](https://ditto.audio/docs)
- [API reference](https://ditto.audio/docs/reference)
- [Pricing](https://ditto.audio/pricing)
- [Support](https://ditto.audio/support)
- [Terms of service](https://ditto.audio/terms)
- [Privacy policy](https://ditto.audio/privacy)

## API Evangelist rating

**Kin Score 48.8** — developing · rubric 0.27.0 · scored 2026-11-05

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 50.5 |
| Contract governance | 79.1 |
| Operational transparency | 0.0 |
| Developer ergonomics | 39.8 |
| Access clarity | 60.0 |

**Agent readiness 50.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 24.5** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ditto-audio/](https://apis.io/providers/ditto-audio/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Ditto Audio: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ditto-audio/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
