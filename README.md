# Microsoft Edge (microsoft-edge)

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
