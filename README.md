# Sei Docs

Official documentation for [Sei Network](https://www.sei.io) — the first parallelized EVM blockchain. Hosted at [docs.sei.io](https://docs.sei.io).

This site is built on [Mintlify](https://mintlify.com).

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

From the repo root (where `docs.json` lives):

```bash
mint dev
```

Open [http://localhost:3000](http://localhost:3000) to view.

## Checking links

```bash
mint broken-links
```

## Content layout

| Path          | What lives there                                                                 |
| ------------- | -------------------------------------------------------------------------------- |
| `learn/`      | Protocol fundamentals, architecture, governance, Sei Giga, resources             |
| `evm/`        | EVM smart contracts, precompiles, frontends, bridges, oracles, sei-js           |
| `cosmos-sdk/` | Cosmos-SDK (deprecated per SIP-3 — kept for historical reference)               |
| `node/`       | Running validator, RPC, statesync, and archive nodes                             |
| `assets/`     | Images, brand assets, OG banners                                                 |
| `logo/`       | Site logo variants                                                               |
| `docs.json`   | Site configuration: navigation, theme, redirects, footer, SEO                    |

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) and [AGENTS.md](AGENTS.md) for style and content guidelines.

## Publishing

Changes pushed to `main` are deployed to production automatically via the Mintlify GitHub app.
