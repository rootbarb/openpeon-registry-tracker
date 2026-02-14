# OpenPeon Registry Tracker

### [Open the app](https://rootbarb.github.io/openpeon-registry-tracker/)

A live dashboard that tracks the status of [OpenPeon](https://openpeon.com) / CESP sound packs in the [PeonPing registry](https://github.com/PeonPing/registry) — which packs are accepted and which are pending via open PRs.

## Features

- **Accepted packs** — fetched dynamically from the registry's `index.json`
- **Pending submissions** — fetched from open pull requests on `PeonPing/registry` via the GitHub API
- Filter by trust tier (official / verified / community)
- Search by name, author, or tag
- Preview links open packs directly in [openpeon-preview](https://rootbarb.github.io/openpeon-preview/)

## Data Sources

| Data | Source |
|---|---|
| Accepted packs | `https://peonping.github.io/registry/index.json` |
| Pending PRs | GitHub API — `repos/PeonPing/registry/pulls?state=open` |

All data is fetched client-side on each page load. No backend required.

## Hosting

Static single-page app — deploy anywhere. Enable GitHub Pages on the repo to host it directly.

## License

MIT
