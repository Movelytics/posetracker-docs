# PoseTracker docs

Public Mintlify documentation for the PoseTracker React Native SDKs (offline + light).

- Site config: [`docs.json`](./docs.json)
- LLM entry: [`llms.txt`](./llms.txt)
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
| `@pose-tracker/react-native-pose-estimation` | Offline / bundled MoveNet (~9.9 MB) |
| `@pose-tracker/react-native-pose-estimation-light` | Light / CDN (~206 kB) |
