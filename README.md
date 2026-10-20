# Dev AI Controller — public portfolio showcase

## Technical documentation (current audit)

**Audit date:** 20 October 2026 · **Release classification:** not a verified complete production application.

**Current GitHub state:** Documentation only; newly authored controller UI and authentication Worker remain outside this repo.

**Source/stack evidence:** Reference implementation uses React/Vite/TypeScript with Node/Worker services, D1 design and separate mobile wrappers; production acceptance remains open.

**Cloudflare state:** The Pages project hosts an earlier documentation deployment. A site-specific Turnstile widget and a shared `AUTH_DB` D1 binding have been provisioned, but a working application deployment and admin sign-in have not been verified. Secret values must never be committed to this public repository.

**Engineering documentation:**

- **[Complete architecture, folder tree, languages, API contracts and backend connections](docs/TECHNICAL_REFERENCE.md)**
- **[Features, actual implementation status and acceptance requirements](docs/FEATURE_AND_RELEASE_MATRIX.md)**
- **[Authentication, Turnstile, security controls, deployment and operations runbook](docs/SECURITY_AND_OPERATIONS.md)**
- [Source verification and NDA boundaries](docs/SOURCE_VERIFICATION.md)
- [Existing platform/device support notes](docs/DEVICE_PREVIEW.md)

All projects use the portfolio credit **[Developed and Designed by Jelvan®](https://portfolio.jelvan.pro)** for independently authored public work. This does not transfer ownership of third-party/client deliverables.

---


**AI-assisted developer operations console**  
**Curated by Jelvan R. · Public documentation, not the original source repository.**

> [!IMPORTANT]
> **Independent public portfolio adaptation — confidentiality and attribution**
>
> This repository is a **revised, selectively documented portfolio presentation** independently prepared and maintained by **Jelvan R.** Certain past projects or engagements may be subject to confidentiality, nondisclosure, contractual, intellectual-property, or client-security obligations. To respect those obligations, this public presentation may anonymize, simplify, recreate, omit, or update parts of the original work. **It is not an exact copy, complete implementation, production configuration, or authoritative description of any client system.**
>
> This showcase is **not an official publication of, sponsored by, endorsed by, or affiliated with any current or former client, employer, company, or other development organization**. References to third-party products, technologies, or historical project terminology are for identification only. This notice does **not** claim exclusive ownership of client deliverables, third-party components, trademarks, or intellectual property.
>
> **No confidential source code, credentials, client data, internal hostnames, or production access are provided.** Features and deployment claims must be read with the project-specific verification notes below.


## Overview

A developer operations dashboard bringing together project context, AI-assisted workflows, and review-focused cloud tasks. Public materials describe boundaries, not privileged tools or operator access.

## Current evidence and status

**Web/API repository states owner-reported development completion; production acceptance checks remain open. Android/iOS shells are separate.**

This repository is **documentation-only**: it does not include an application build, genuine account access, production dependencies or a deployment artifact.

### What the source documentation supports

- jelvan-operava/Dev-ai-Controller has React/Vite frontend and server/runtime code, tests, docs, and Wrangler configuration.
- Source README reports frontend/backend completion by project owner, but explicitly reserves end-to-end release validation.
- Android repository is a Capacitor web dashboard shell.
- iOS repository describes SwiftUI/WKWebView integration; release signing and acceptance not independently verified.
- HrJel/Dev-ai-Controller.v2 is described as xCODE, a related but distinct refocusing; do not imply it is the same production release.

### Technology context

- React, Vite and TypeScript
- Node/Express and Cloudflare Worker runtimes
- Cloudflare D1 and server-side service adapters
- Capacitor Android shell
- SwiftUI / WKWebView iOS shell

### Capabilities described or proposed

- Developer dashboard and workflow navigation
- Review-driven coding and deployment procedures
- Server-mediated access to operational integrations
- Cross-device companion shells documented separately

> **Accuracy rule:** Any item identified as illustrative, proposed, unverified, or source-documented must not be marketed as a live, completed feature.

## Architecture at a glance

```text
Web / Android shell / iOS shell → Authenticated server API → controlled providers and approved infrastructure
```

For component boundaries, implementation caveats and verification: [Architecture](docs/ARCHITECTURE.md) and [Implementation Notes](docs/IMPLEMENTATION.md).

## Device previews

The portfolio can offer macOS, Desktop Web, iOS and Android **presentation modes**. That does not imply a native build exists on every platform.

| Viewer mode | Evidence-backed display type |
| --- | --- |
| macos | browser-viewport |
| web | web-reference |
| ios | swiftui-webview-source-unverified-release |
| android | capacitor-shell-source |

Read the [device preview policy](docs/DEVICE_PREVIEW.md) before enabling live framing. Public demo assets are intentionally absent until permission and sanitization checks are passed.

## Known limitations

- No AI provider token, GitHub credential, browser credential, infrastructure token, deployment binding, or internal route is public.
- Showcase is not an operational administration console and cannot modify external resources.
- Release and security readiness cannot be inferred from a health endpoint.

## Repository contents

```text
README.md                       Project overview and verification status
DISCLAIMER.md                   Public-view / NDA and attribution notice
SECURITY.md                     Safe disclosure and content-handling policy
CONTRIBUTING.md                 Public contribution boundaries
portfolio.json                  Sanitized metadata for portfolio integration
docs/ARCHITECTURE.md            Architecture and boundaries
docs/IMPLEMENTATION.md          Evidence, components and non-goals
docs/DEVICE_PREVIEW.md          Frame behavior and security policy
docs/DEPLOYMENT.md              Safe showcase publication workflow
docs/TESTING.md                 QA and release gate checklist
docs/SOURCE_VERIFICATION.md     Evidence status without private repo details
docs/CHANGELOG.md               Public documentation changelog
assets/README.md                Sanitized images/screenshot instructions
```

## Start here

1. Review [the disclaimer](DISCLAIMER.md) and [implementation notes](docs/IMPLEMENTATION.md).
2. Replace placeholder screenshots only with approved, anonymized visuals.
3. Confirm platform support, and enable approved public demo links only after independent testing.
4. Publish as a distinct public repository; **never mirror, fork or reveal original private projects**.
5. Add the public showcase URL to the Projects section of [portfolio.jelvan.pro](https://portfolio.jelvan.pro) without making production URLs visible in the viewer.

## Licensing and use

This repository provides public-facing explanatory materials only. **Public visibility is not an open-source license or a grant of rights to confidential or third-party works.** Written permission and applicable rights are needed before reuse. No rights in third-party products, names, interfaces, libraries, or client materials are asserted.

## Contact

For portfolio discussion, use the contact route on [portfolio.jelvan.pro](https://portfolio.jelvan.pro). Do not post confidential information in public issues.
