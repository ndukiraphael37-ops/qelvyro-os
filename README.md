# QELVYRO OS — Independent Foundation v0.3

This is a portable static prototype, intended as a first independent codebase milestone.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Use the navigation to explore Overview, Command Centre, Module Registry, Projects, Assets, and Settings & Data.

It can also be hosted as a static website. No build tools or package installation are required.

## Included
- Responsive phone/laptop dashboard
- Local command interpretation and simulated job records
- QELVYRO module/capability registry
- Local project and asset metadata
- JSON export/import
- Local browser persistence

## Explicit limitations
- This is not a deployed cloud service.
- No real AI image/video generation or provider APIs are connected.
- Local records remain in the current browser/device unless exported.
- No authentication, multi-user access, server database, cloud file storage, or server-side secret management.
- Commands create plans and simulated job records only.

## Next engineering milestone
Audit the existing QELVYRO artifacts, then add a secure backend and connect one real provider behind a server-side interface. Preserve the Master Control & Orchestrator concept and avoid duplicating existing specialist modules.

Never place API keys in `index.html` or client-side JavaScript.
