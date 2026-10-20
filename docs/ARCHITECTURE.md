# Architecture — Dev AI Controller

## Architecture status

**Web/API repository states owner-reported development completion; production acceptance checks remain open. Android/iOS shells are separate.**

## Public high-level flow

```text
Web / Android shell / iOS shell → Authenticated server API → controlled providers and approved infrastructure
```

## Verified high-level design

The main front end is a React/Vite dashboard backed by a TypeScript server runtime, with Cloudflare Worker deployment options and data adapters. Mobile shells display or integrate the first-party web experience and do not constitute independent privileged backends.

## Technology references

- React, Vite and TypeScript
- Node/Express and Cloudflare Worker runtimes
- Cloudflare D1 and server-side service adapters
- Capacitor Android shell
- SwiftUI / WKWebView iOS shell

## Trust boundaries

1. The public showcase is a separate documentation/presentation boundary. It is not authorized to access production accounts or protected datasets.
2. Authentication, authorization, storage operations and confidential business rules, if applicable, belong to private reviewed services—not public mock UI.
3. An iframe is a nested browser context, not a substitute for server authentication or entitlement checks.
4. Device frames alter dimensions and appearance, not actual native runtime behavior.

## Unverified or intentionally omitted

- No AI provider token, GitHub credential, browser credential, infrastructure token, deployment binding, or internal route is public.
- Showcase is not an operational administration console and cannot modify external resources.
- Release and security readiness cannot be inferred from a health endpoint.

## Security/design review before going live

- [ ] Confirm any referenced architecture is approved for public disclosure.
- [ ] Use invented demo identifiers, content and accounts.
- [ ] Verify no private URL or client organization names appear in HTML, CSS, JS, screenshots or history.
- [ ] Test browser permissions and iframe CSP on the actual demo host.
- [ ] Confirm accessibility and responsive behavior separately on representative devices.
