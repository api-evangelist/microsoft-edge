# Microsoft Edge (microsoft-edge)

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

APIs and resources for Microsoft Edge browser development and integration, including the Edge Add-ons API for extension management, DevTools Protocol for browser debugging and automation, Extensions API for building browser extensions, and Web Platform APIs for progressive web app development.

**URL:** [Visit APIs.json URL](https://www.microsoft.com/edge)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Browser, Chromium, Developer Tools, Edge, Extensions, Microsoft, Progressive Web Apps, Web Development, WebView

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Microsoft Edge Add-ons API
REST API for managing Microsoft Edge browser extensions through the Partner Center. Enables programmatic publishing, updating, and managing Edge extensions in the Microsoft Edge Add-ons store, supporting the full extension lifecycle from upload to publication.

**Human URL:** [https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api)

#### Tags:

 - Add-Ons, Browser Extensions, Extension Publishing, Package Management, Partner Center

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api)
- [Getting Started](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api#before-you-begin)
- [API Reference](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/addons-api-reference)
- [Authentication](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/publish/api/using-addons-api#registering-the-client-application-in-azure-active-directory)
- [OpenAPI](openapi/microsoft-edge-addons-api.yaml)
- [JSON Schema - Product](json-schema/addons-api-product-schema.json)
- [JSON Schema - Submission](json-schema/addons-api-submission-schema.json)
- [JSON Schema - Product List](json-schema/addons-api-product-list-schema.json)
- [JSON Schema - Package Upload Result](json-schema/addons-api-package-upload-result-schema.json)
- [JSON-LD Context](json-ld/microsoft-edge-addons-api-context.jsonld)

### Microsoft Edge DevTools Protocol HTTP API
HTTP endpoints for the Microsoft Edge DevTools Protocol, based on the Chromium DevTools Protocol. These endpoints allow programmatic discovery and management of debuggable browser targets including pages, service workers, and extensions.

**Human URL:** [https://learn.microsoft.com/en-us/microsoft-edge/devtools-protocol-chromium/](https://learn.microsoft.com/en-us/microsoft-edge/devtools-protocol-chromium/)

#### Tags:

 - Automation, Browser Debugging, DevTools, Remote Debugging, Testing

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-edge/devtools-protocol-chromium/)
- [API Reference](https://chromedevtools.github.io/devtools-protocol/)
- [Getting Started](https://learn.microsoft.com/en-us/microsoft-edge/devtools-protocol-chromium/)
- [OpenAPI](openapi/microsoft-edge-devtools-api.yaml)
- [JSON Schema - Target](json-schema/devtools-api-target-schema.json)
- [JSON Schema - Browser Version](json-schema/devtools-api-browser-version-schema.json)
- [JSON Schema - Protocol Schema](json-schema/devtools-api-protocol-schema-schema.json)
- [JSON-LD Context](json-ld/microsoft-edge-devtools-api-context.jsonld)

### Microsoft Edge Extensions API
Build browser extensions for Microsoft Edge using the Chromium-based extensions platform. Supports the WebExtensions API standard for cross-browser compatibility.

**Human URL:** [https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/)

#### Tags:

 - Add-Ons, Browser Extensions, Chromium Extensions, Web Extensions

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/)
- [Getting Started](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/)
- [API Reference](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/developer-guide/api-support)
- [Tutorials](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/part1-simple-extension)

### Microsoft Edge Web Platform APIs
Modern web APIs and standards supported in Microsoft Edge, including Progressive Web App capabilities, Web Components, and emerging web platform features.

**Human URL:** [https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/](https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/)

#### Tags:

 - Progressive Web Apps, PWA, Web Platform, Web Standards

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/)
- [Getting Started](https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/how-to/)
- [Release Notes](https://learn.microsoft.com/en-us/microsoft-edge/progressive-web-apps-chromium/whats-new/)

## Common Properties

- [Documentation](https://learn.microsoft.com/en-us/microsoft-edge/)
- [Developer Portal](https://developer.microsoft.com/microsoft-edge/)
- [Blog](https://blogs.windows.com/msedgedev/)
- [GitHub Organization](https://github.com/MicrosoftEdge)
- [WebView2 Samples](https://github.com/MicrosoftEdge/WebView2Samples)
- [Support](https://learn.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/)
- [Release Notes](https://learn.microsoft.com/en-us/microsoft-edge/web-platform/release-notes/)
- [Change Log](https://learn.microsoft.com/en-us/deployedge/microsoft-edge-relnote-stable-channel)
- [Status Page](https://developer.microsoft.com/en-us/microsoft-edge/status/)
- [X](https://twitter.com/MSEdgeDev)
- [Terms of Service](https://www.microsoft.com/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/privacystatement)
- [SDK - WebView2 NuGet](https://www.nuget.org/packages/Microsoft.Web.WebView2)
- [Sign Up](https://partner.microsoft.com/dashboard/microsoftedge/)
- [Marketplace](https://microsoftedge.microsoft.com/addons/)

## Features

| Name | Description |
|------|-------------|
| Extension Publishing API | Programmatically publish, update, and manage browser extensions in the Edge Add-ons store via REST API. |
| Remote Debugging Protocol | Debug and inspect web pages, service workers, and extensions using the Chrome DevTools Protocol over WebSocket. |
| WebView2 Embedding | Embed Microsoft Edge rendering engine in native desktop applications using the WebView2 SDK. |
| Progressive Web App Support | Build installable PWAs with offline capability, push notifications, and system integration. |
| Cross-Browser Extension Compatibility | Build extensions using the Chromium WebExtensions API standard for cross-browser portability. |
| Browser Automation | Automate browser tasks including page navigation, target management, and performance profiling. |
| Extension Sideloading | Load and test unpacked extensions locally during development without publishing to the store. |
| Manifest V3 Support | Build extensions using the latest Manifest V3 specification with service workers and declarative APIs. |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Extension Deployment | Use the Add-ons API to automate CI/CD pipelines for publishing and updating browser extensions. |
| Browser Testing and QA | Leverage DevTools Protocol for automated browser testing, performance auditing, and regression detection. |
| Custom Browser Controls | Embed Edge rendering in desktop applications for custom browser experiences using WebView2. |
| Enterprise Content Filtering | Build enterprise extensions for content filtering, security policy enforcement, and compliance monitoring. |
| Web Scraping and Data Extraction | Use DevTools Protocol to programmatically navigate pages and extract structured data. |
| Accessibility Testing | Automate accessibility audits using DevTools Protocol to inspect DOM, ARIA attributes, and contrast ratios. |
| Performance Monitoring | Collect real-time performance metrics, network traces, and JavaScript profiling data via DevTools Protocol. |
| Progressive Web App Distribution | Build and distribute PWAs through the Microsoft Store with native-like installation and system integration. |

## Integrations

| Name | Description |
|------|-------------|
| Azure Active Directory | Authenticate to the Edge Add-ons API using Azure AD OAuth 2.0 client credentials flow. |
| Microsoft Partner Center | Manage extension listings, submissions, and analytics through the Partner Center dashboard. |
| Visual Studio Code | Debug Edge browser content directly from VS Code using the Edge DevTools extension. |
| Selenium WebDriver | Automate Microsoft Edge browser for testing using Selenium with the Edge WebDriver. |
| Playwright | Cross-browser automation framework with first-class support for Microsoft Edge testing. |
| Puppeteer | Control headless Microsoft Edge instances programmatically using the Puppeteer Node.js library. |
| GitHub Actions | Automate extension publishing and browser testing in CI/CD workflows using GitHub Actions. |
| Windows App SDK | Integrate WebView2 into Windows desktop applications built with WinUI 3 and the Windows App SDK. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Microsoft Edge Add-ons API](openapi/microsoft-edge-addons-api.yaml)
- [Microsoft Edge DevTools Protocol HTTP API](openapi/microsoft-edge-devtools-api.yaml)

### JSON Schema

- [Add-ons API - Product](json-schema/addons-api-product-schema.json)
- [Add-ons API - Submission](json-schema/addons-api-submission-schema.json)
- [Add-ons API - Product List](json-schema/addons-api-product-list-schema.json)
- [Add-ons API - Package Upload Result](json-schema/addons-api-package-upload-result-schema.json)
- [DevTools API - Target](json-schema/devtools-api-target-schema.json)
- [DevTools API - Browser Version](json-schema/devtools-api-browser-version-schema.json)
- [DevTools API - Protocol Schema](json-schema/devtools-api-protocol-schema-schema.json)

### JSON Structure

- [Add-ons API - Product](json-structure/addons-api-product-structure.json)
- [Add-ons API - Submission](json-structure/addons-api-submission-structure.json)
- [Add-ons API - Product List](json-structure/addons-api-product-list-structure.json)
- [Add-ons API - Package Upload Result](json-structure/addons-api-package-upload-result-structure.json)
- [DevTools API - Target](json-structure/devtools-api-target-structure.json)
- [DevTools API - Browser Version](json-structure/devtools-api-browser-version-structure.json)
- [DevTools API - Protocol Schema](json-structure/devtools-api-protocol-schema-structure.json)

### JSON-LD

- [Microsoft Edge DevTools API Context](json-ld/microsoft-edge-devtools-api-context.jsonld)
- [Microsoft Edge Add-ons API Context](json-ld/microsoft-edge-addons-api-context.jsonld)

### Examples

- [Add-ons API - Product](examples/addons-api-product-example.json)
- [Add-ons API - Product List](examples/addons-api-product-list-example.json)
- [Add-ons API - Submission](examples/addons-api-submission-example.json)
- [Add-ons API - Package Upload Result](examples/addons-api-package-upload-result-example.json)
- [DevTools API - Target](examples/devtools-api-target-example.json)
- [DevTools API - Browser Version](examples/devtools-api-browser-version-example.json)
- [DevTools API - Protocol Schema](examples/devtools-api-protocol-schema-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [DevTools API](capabilities/shared/devtools-api.yaml) -- 6 operations for browser target discovery and management
- [Add-ons API](capabilities/shared/addons-api.yaml) -- 6 operations for extension lifecycle management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Browser Development](capabilities/browser-development.yaml) | DevTools API + Add-ons API | 12 | Extension Developer, Web Developer, QA Engineer |

## Vocabulary

- [Microsoft Edge Vocabulary](vocabulary/microsoft-edge-vocabulary.yaml) -- Unified taxonomy mapping 6 resources, 7 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Microsoft Edge Spectral Rules](rules/microsoft-edge-spectral-rules.yml) -- 25 rules across 10 categories enforcing Microsoft Edge API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
