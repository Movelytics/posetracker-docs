# PoseTracker docs

Public Mintlify documentation for PoseTracker: **WebView / iframe embed** (quick test) and **npm SDKs** (React Native offline/light + web) for production.

- Site: [https://docs.posetracker.com](https://docs.posetracker.com)
- Config: [`docs.json`](./docs.json)
- LLM entry: [`llms.txt`](./llms.txt) · [`llms-full.txt`](./llms-full.txt)
- Product: [posetracker.com](https://www.posetracker.com)
- npm: [@pose-tracker](https://www.npmjs.com/org/pose-tracker)

## Local preview

Requires Node.js 20+.

```bash
npm i -g mint
mint dev
```

Open [http://localhost:3000](http://localhost:3000).

## Deploy

Connect this repository in the [Mintlify dashboard](https://app.mintlify.com/posetracker/posetracker/activity) (Settings → Git → `Movelytics/posetracker-docs`, branch `main`). Pushes to `main` trigger deploys.

## Packages covered

| Package | Role |
|---|---|
| `@pose-tracker/react-native-pose-estimation` | RN offline / bundled MoveNet (~10.0 MB) |
| `@pose-tracker/react-native-pose-estimation-light` | RN light / CDN (~212 kB) |
| `@pose-tracker/pose-estimation-web` | Browser vanilla |
| `@pose-tracker/pose-estimation-web-react` | Browser React |
| WebView embed | `https://app.posetracker.com/pose_tracker/tracking` |

## GitBook → Mintlify (banners later)

GitBook is no longer the canonical docs. When you add a redirect banner on each GitBook page, point here:

| GitBook topic | Mintlify |
|---|---|
| Choose integration approach | https://docs.posetracker.com/choose-integration |
| Quick start (camera / webcam) | https://docs.posetracker.com/webview/quickstart |
| Query parameters (tracking) | https://docs.posetracker.com/webview/query-params |
| Tracking / WebView messages | https://docs.posetracker.com/webview/messages |
| Upload tracking | https://docs.posetracker.com/webview/upload |
| Reference movement | https://docs.posetracker.com/webview/reference-movement |
| Platform tutorials (HTML, RN, iOS, Android, Flutter) | https://docs.posetracker.com/webview/embed |
| SDK / Expo / React Native | https://docs.posetracker.com/quickstart |
| Web / JavaScript / React SDK | https://docs.posetracker.com/web-sdks |
| Exercises | https://docs.posetracker.com/reference/exercises |
| Engine / appearance | https://docs.posetracker.com/webview/query-params |

Pixel tracking stays GitBook-only for now (out of scope on Mintlify).
