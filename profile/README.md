# EthioReview Trust Builder

**Verified reviews for Ethiopian businesses** — and open tooling so developers can embed trust on any site.

EthioReview helps organizations collect, moderate, and display authentic customer reviews. This organization publishes the **public developer surface**: docs, sample apps, SDKs, and integration guides.

## Start here

| Resource | What it is |
| -------- | ---------- |
| [Developer docs](https://docs.ethioreview.com) | API keys, sandbox, review widgets, Telegram, digital platforms |
| [docs](https://github.com/ethioreview/docs) | Mintlify source for [docs.ethioreview.com](https://docs.ethioreview.com) |
| [review-widget](https://github.com/ethioreview/review-widget) | Monorepo for `@ethioreview/review-widget-*` npm packages |
| [er-widget-sample](https://github.com/ethioreview/er-widget-sample) | Clone-and-run Vite sample using published npm widget packages |

## For developers

1. Create a **sandbox** API client in the [dashboard](https://app.ethioreview.com) (**Integrations → API keys**).
2. Register a sandbox widget (**Integrations → Review widgets**).
3. Clone the sample and paste your `pk_test_*` key:

```bash
git clone https://github.com/ethioreview/er-widget-sample.git
cd er-widget-sample
cp .env.example .env
npm install
npm run dev
```

Guides: [Quickstart](https://docs.ethioreview.com/quickstart) · [Sandbox sample app](https://docs.ethioreview.com/sandbox/sample-app) · [Widget overview](https://docs.ethioreview.com/integrations/widget/overview)

### Published packages

| Package | Use |
| ------- | --- |
| [`@ethioreview/review-widget-react`](https://www.npmjs.com/package/@ethioreview/review-widget-react) | React widget + layouts |
| [`@ethioreview/review-widget-web-vanilla`](https://www.npmjs.com/package/@ethioreview/review-widget-web-vanilla) | `<review-widget>` custom element + `widget.js` |
| [`@ethioreview/review-widget-web-iframe`](https://www.npmjs.com/package/@ethioreview/review-widget-web-iframe) | iframe embed helpers |
| [`@ethioreview/review-widget-next`](https://www.npmjs.com/package/@ethioreview/review-widget-next) | Next.js SSR + JSON-LD |
| [`@ethioreview/review-widget-react-native`](https://www.npmjs.com/package/@ethioreview/review-widget-react-native) | React Native WebView |
| [`@ethioreview/review-widget-core`](https://www.npmjs.com/package/@ethioreview/review-widget-core) | Shared `WidgetApiClient` |

Latest release: **0.1.1** on npm.

## Product links

- Website: [ethioreview.com](https://ethioreview.com)
- Business dashboard: [app.ethioreview.com](https://app.ethioreview.com)
- Docs: [docs.ethioreview.com](https://docs.ethioreview.com)

## Community

Discussions are enabled on our public repos:

| Board | Use for |
| ----- | ------- |
| [docs Discussions](https://github.com/ethioreview/docs/discussions) | API keys, widgets, sandbox, docs feedback |
| [er-widget-sample Discussions](https://github.com/ethioreview/er-widget-sample/discussions) | Sample app setup and local embed help |

Start here: [Welcome (docs)](https://github.com/ethioreview/docs/discussions/1) · [Welcome (sample)](https://github.com/ethioreview/er-widget-sample/discussions/1)

## Mission

Build trust infrastructure for Ethiopian markets — transparent ratings, fair moderation, and developer-friendly embeds for websites, marketplaces, and Telegram.
