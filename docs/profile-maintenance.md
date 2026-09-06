# Profile Maintenance

This repository powers the GitHub profile README. The entry point is `README.md`; no application build or website deployment is required.

## Presentation

- Keep all profile copy in English for an international audience.
- Use GitHub-compatible Markdown and HTML, including the centered introduction and theme-aware `picture` banner.
- Maintain the light/dark `profile-*.svg` hero and `footer-*.svg` assets together. Main content must remain readable without images.
- Use the aurora palette: blue, cyan, and violet over light titanium or deep navy surfaces. Preserve the animated typing introduction in `assets/typing.svg`; static identity text remains available without images.
- Do not include a featured-project section, personal repository recommendations, or project names promoting personal repositories.
- List Go, Node.js, MySQL, Redis, and Kubernetes as part of the full-stack toolkit, not as technologies being explored.
- Publish only the requested email address, `minntaki@foxmail.com`, with a `mailto:` link.
- WakaTime content and its scheduled update workflow have been removed.

## Content Sources

The profile was revised on September 6, 2026. The following sources support the capability descriptions; they are maintenance references, not profile recommendations. Repository documentation does not establish production validation.

| Content | Source and limits |
| :--- | :--- |
| Original frontend stack and personal links | Previous README, commit `185b679`; no inferred proficiency or years of experience |
| AI editing, diff review, collaborative editing | Public documentation for `tiptap-ai-yjs-demo`; demonstrated application features, not a claim of production scale |
| MCP, CLI, plugins, memory, and context recall | Public documentation for `I-Evolve`; limited to supported integrations and local retrieval |
| Multi-agent workflows, provider abstraction, data adapters, asynchronous services | Public documentation for `etf-stock-agent`, based on an extraction and extension of TradingAgents; no claim of originating the underlying framework |
| Bilibili role, employment dates, and responsibilities | User-supplied career materials; not independently verified |
| Monorepo, Rollup, Rust / WebAssembly, and SSR testing | User-supplied skills and project materials |
| Go, Node.js, MySQL, Redis, and Kubernetes | Explicitly supplied by the user as full-stack skills |

The memory-system documentation mixes planned and implemented vector-retrieval capabilities. The profile therefore does not claim a completed production RAG system, dense retrieval backend, or reranking pipeline. No unsupported training, fine-tuning, team-size, performance, or business-impact claims were added.

The employment summary retains the company, public job title, dates, and general technical responsibilities. It omits phone numbers, internal levels, internal system names, performance ratings, business metrics, patent details, and security implementation details. Personal AI work is not presented as an employer project outcome.

## External Links

During the September 6, 2026 HTTPS checks, the technical notes returned HTTP 200. The blog domain `yihuiblog.top` returned a certificate hostname mismatch; the former community domain failed during TLS negotiation. At the user's request, the blog link remains and the community link was removed. A connection failure does not establish that a site has permanently closed.

## Preview and Validation

Local light and dark previews approximate GitHub styling. Keep them outside tracked deliverables. After editing, regenerate both from the current README, check mobile wrapping and image loading, and run `git diff --check`.

Changes remain local until explicitly committed and pushed. The preview is not a deployed GitHub profile.

The user clarified the current role as **bilibili · Senior Software Engineer** and requested the Juejin profile link alongside the restored animated introduction.

## Visual System

The profile uses self-contained SVG artwork with slow orbital rotation, aurora lighting, and traveling footer highlights. Essential copy stays in native Markdown. All local animations, including the typing introduction, honor `prefers-reduced-motion`. The typing effect was recreated locally after the external image loaded inconsistently in the preview.

The personal `github-profile-studio` skill was created and applied to this redesign. Its asset helper generates the theme pairs; artwork in this repository can also be edited directly without installing the skill. Temporary preview files and personal skill configuration are not part of this repository.
