# gAIa Docs

Documentation for [gAIa](https://gaia.gus.earth) — talk to forests, understand the trees.

This site is built with [Mintlify](https://mintlify.com). Live product: [ai.gus.earth](https://ai.gus.earth).

## Development

Install the Mintlify CLI:

```bash
npm i -g mint
```

From the repo root (where `docs.json` lives):

```bash
mint dev
```

Preview at [http://localhost:3000](http://localhost:3000).

## Publishing

Connect the GitHub app in the [Mintlify dashboard](https://dashboard.mintlify.com/settings/organization/github-app). Pushes to the default branch deploy automatically.

## Troubleshooting

- Dev server issues: run `mint update`
- 404 pages: confirm you are in the folder that contains `docs.json`
