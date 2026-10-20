# QA and acceptance checklist — Dev AI Controller

## Application-specific validation

- [ ] Check navigation and non-privileged demo interaction.
- [ ] Verify API calls are disabled or fixture-backed in demo builds.
- [ ] Verify server authorization for all privileged operations in private test infrastructure.
- [ ] Distinguish CI/build success from deployment readiness for mobile clients.

## Generic public-release validation

- [ ] README disclaimer includes independent Jelvan R. presentation, NDA/confidentiality limitations and no company endorsement.
- [ ] Status explicitly identifies what is source-documented, tested, unverified or proposed.
- [ ] No real environment values or operational endpoints in Markdown or JSON.
- [ ] GitHub secret scanning / code scanning enabled when available.
- [ ] Device selector does not infer native client availability from a mobile viewport.
- [ ] Public screenshots and media have consent and contain synthetic data.
- [ ] Accessibility checks for focus, color contrast and text resizing.
- [ ] Portfolio integration uses safe fallback if iframe refuses embedding.
- [ ] Browser response CSP and Fetch Metadata behavior tested if using Cloudflare frames.

## Acceptance result

**Not executed for real applications.** This checklist is an implementation plan, not a pass certificate.
