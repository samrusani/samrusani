# Sami Rusani
 
AI Strategy & Research | Frontier Technology Investor | Fund Manager
 
Founder of [900 Labs](https://900labs.ai), an AI research and acceleration institute. General Partner at Type3 Capital, Rusani Ventures, and Beyond the Bounds, with 100+ investments across frontier technology.
 
Currently completing an MSc in Finance and Investment Management while building AI infrastructure and applied research tools.
 
Based in Europe.
 
---
 
## Open Source Contributions

Recent merged work across Rust, TypeScript, Python, desktop agents, MCP tooling, CI, and reliability.

- **Prefect and Pydantic AI Harness** — [supported Azure Container Instance guidance](https://github.com/PrefectHQ/prefect/pull/22830) and [FIFO-safe filesystem writes](https://github.com/pydantic/pydantic-ai-harness/pull/613).
- **Hermes Agent** — [MoA preset controls](https://github.com/NousResearch/hermes-agent/pull/70283), [OAuth recovery](https://github.com/NousResearch/hermes-agent/pull/61951), and [updater permission handling](https://github.com/NousResearch/hermes-agent/pull/58754).
- **OpenClaw** — [Control UI tool expansion](https://github.com/openclaw/openclaw/pull/74398), [cron session persistence](https://github.com/openclaw/openclaw/pull/65203), and [Bedrock attribution handling](https://github.com/openclaw/openclaw/pull/92991).
- **OpenHuman** — [Claude CLI Windows reliability](https://github.com/tinyhumansai/openhuman/pull/5103), [MCP registry error handling](https://github.com/tinyhumansai/openhuman/pull/4716), and [approval-route race fixes](https://github.com/tinyhumansai/openhuman/pull/4786).
- **Tari** — [dependency security updates](https://github.com/tari-project/tari/pull/7918), [Cucumber/JUnit dependency maintenance](https://github.com/tari-project/tari/pull/7915), and [desktop/node recovery fixes](https://github.com/tari-project/universe/pull/3327).
- **MiroFish** — [long-document ontology sampling](https://github.com/666ghj/MiroFish/pull/584) and [ARM64 Docker build support](https://github.com/666ghj/MiroFish/pull/731).
- **Paperclip and Scrapling** — [safe issue-list truncation metadata](https://github.com/paperclipai/paperclip/pull/4771), [safe Office attachment MIME handling](https://github.com/paperclipai/paperclip/pull/8562), and [custom Chromium paths for MCP browser tools](https://github.com/D4Vinci/Scrapling/pull/360).

<details>
<summary><strong>Verified 2026 contribution record</strong></summary>

### Hermes Agent

- [#59743 / #70283](https://github.com/NousResearch/hermes-agent/pull/70283) — Added persisted enable/disable controls for Desktop MoA presets.
- [#60048 / #61951](https://github.com/NousResearch/hermes-agent/pull/61951) — Recovered provider runtime auth from shared OAuth state.
- [#47884 / #58754](https://github.com/NousResearch/hermes-agent/pull/58754) — Prevented updater failure when `/Applications` is unwritable.

### OpenClaw

- [#74398](https://github.com/openclaw/openclaw/pull/74398) — Fixed verbose-full Control UI tool expansion.
- [#65203](https://github.com/openclaw/openclaw/pull/65203) — Fixed cron isolated-run session persistence and stale transcripts.
- [#92991](https://github.com/openclaw/openclaw/pull/92991) — Fixed missing attribution-base URL handling.

### OpenHuman

- [#5103](https://github.com/tinyhumansai/openhuman/pull/5103) — Moved large Claude prompts out of Windows argv and improved launch-failure diagnostics.
- [#4786](https://github.com/tinyhumansai/openhuman/pull/4786) — Fixed approval cleanup races across chat and in-call routes.
- [#4716](https://github.com/tinyhumansai/openhuman/pull/4716) — Added localized MCP registry failures with API and UI regressions.
- [#4309](https://github.com/tinyhumansai/openhuman/pull/4309) — Added a documented CEF GPU-disable startup override for Windows.
- [#4232](https://github.com/tinyhumansai/openhuman/pull/4232) — Fixed cold-start chat file hydration from the artifact ledger.
- [#3746](https://github.com/tinyhumansai/openhuman/pull/3746) — Hardened deferred auth validation across transient `/auth/me` failures.
- [#3678](https://github.com/tinyhumansai/openhuman/pull/3678) — Added numeric-grounding rules and regression coverage for agent prompts.

### Prefect

- [#22830](https://github.com/PrefectHQ/prefect/pull/22830) — Updated Azure Container Instance documentation to the supported work-pool and worker workflow.

### Pydantic AI Harness

- [#613](https://github.com/pydantic/pydantic-ai-harness/pull/613) — Prevented filesystem writes from blocking on FIFO targets, with POSIX regression coverage and safety documentation.

### Paperclip

- [#4771](https://github.com/paperclipai/paperclip/pull/4771) — Added issue-list truncation metadata so API clients can safely detect preview descriptions.
- [#9105](https://github.com/paperclipai/paperclip/pull/9105) — Clarified execution-policy decision rationale across API errors, tests, and agent-facing documentation.
- [#8562](https://github.com/paperclipai/paperclip/pull/8562) — Added safe Office MIME inference and upload coverage.

### Tari

- [tari #7918](https://github.com/tari-project/tari/pull/7918) — Removed a RustSec advisory with a narrow lockfile update.
- [tari #7915](https://github.com/tari-project/tari/pull/7915) — Updated the Cucumber/JUnit dependency path to released crates.
- [tari #7905](https://github.com/tari-project/tari/pull/7905) — Reduced base-node listening-state log noise with timed peer summaries.
- [tari #7904](https://github.com/tari-project/tari/pull/7904) — Corrected Minotari Docker Compose persistent-volume documentation.
- [tari #7792](https://github.com/tari-project/tari/pull/7792) — Added standalone offline signer Cucumber coverage with deterministic test-keystore support.
- [universe #3327](https://github.com/tari-project/universe/pull/3327) — Fixed recoverable node startup retries.
- [universe #3307](https://github.com/tari-project/universe/pull/3307) — Fixed Windows elevated auto-start disable handling.
- [universe #3191](https://github.com/tari-project/universe/pull/3191) — Fixed the first-send missing-file failure.
- [tari #7790](https://github.com/tari-project/tari/pull/7790) and [#7791](https://github.com/tari-project/tari/pull/7791) — Updated vulnerable Diesel and rustls-webpki dependencies.

### Other projects

- [Governance #672](https://github.com/CarlMartinDahl/Governance/pull/672) — Prepared the repository for public collaboration by removing private references, anonymizing contract documentation, and adding contribution guidance.
- [MiroFish #584](https://github.com/666ghj/MiroFish/pull/584) — Sampled long ontology input across the document instead of truncating from the front.
- [MiroFish #588 / #731](https://github.com/666ghj/MiroFish/pull/731) — Added safe ARM64 Docker image builds.
- [Scrapling #360](https://github.com/D4Vinci/Scrapling/pull/360) — Added custom Chromium executable support for MCP browser tools.
- [Scrapling #358](https://github.com/D4Vinci/Scrapling/pull/358) — Review contribution: caught a duplicate-request checkpoint edge case before merge.
- [Scrapling #255](https://github.com/D4Vinci/Scrapling/pull/255) — Review contribution: prompted regression coverage for fingerprint kwargs and headers.
- [Dify #35004](https://github.com/langgenius/dify/pull/35004) — Fixed a Visual Editor tab-switch failure caused by JSON Schema URL construction.
- **OpenVPN** — [documented `--preresolve`](https://github.com/OpenVPN/openvpn/commit/032c13365d2f1d18fdfd4b87c2bc9042e0855d65) and clarified [`--float` UDP behavior](https://github.com/OpenVPN/openvpn/commit/fb863b6daa4f5a2033b937b60f9e93241546666d).
- **Hermes Agent** — Added outbound Matrix mention payloads in [#8464 / #16821](https://github.com/NousResearch/hermes-agent/pull/16821).

</details>
    
---
 
## Get in Touch
 
- **X:** [@samrusani](https://x.com/samrusani)  
- **LinkedIn:** [samirusani](https://www.linkedin.com/in/samirusani/)  
- **Web:** [samirusani.com](https://www.samirusani.com)
