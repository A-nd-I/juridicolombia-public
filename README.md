# JuridiColombia

JuridiColombia is a Chrome Extension for fast, private, offline access to core Colombian legal references. It helps users search `artículos` by number or keyword across `Código Civil`, `Código de Comercio`, and `Código General del Proceso` directly from the browser.

**Status:** Active development  
**Source code:** Private for now  
**Public repository purpose:** product documentation, roadmap, screenshots, issues, and contact

## Important Disclaimer

- JuridiColombia is a legal reference tool, not legal advice.
- Legal texts are based on public Colombian legal sources.
- Users should verify official sources before relying on any legal information.
- For legal decisions, consult a licensed attorney.

## What It Does

- Search `artículos` by exact number or keyword.
- Navigate multiple keyword matches with Previous / Next controls.
- Work offline with embedded legal datasets.
- Open official public sources from quick-access buttons.
- Save custom legal web links locally.
- Use a minimal Chrome permission model focused on `storage`.

## Included Legal References

- `Código Civil` - Ley 84 de 1873
- `Código de Comercio` - Decreto 410 de 1971
- `Código General del Proceso` - Ley 1564 de 2012

## Why It Matters

Legal professionals often lose time navigating slow public portals, switching between sources, and repeating common searches. JuridiColombia moves the most common reference workflow into the browser: fast search, offline access, official-source links, and private local storage.

## Screenshots

Add public screenshots in `screenshots/`:

- `screenshots/search-popup.png`
- `screenshots/keyword-pagination.png`
- `screenshots/custom-links.png`
- `screenshots/expanded-window.png`

## Architecture Overview

The implementation follows a clean layered structure:

```txt
src/
  domain/          entities and repository contracts
  application/     use cases
  infrastructure/  Chrome APIs, storage, embedded legal documents
  presentation/    popup view, controller, UI bindings
public/            Chrome extension HTML/CSS assets
scripts/           TXT-to-TypeScript legal data extractors
```

Important implementation choices:

- Embedded legal data for offline-first access.
- Local Chrome storage for saved user links.
- Search use case separated from UI state.
- Result pagination isolated from the main popup controller.
- Quick legal-source bindings extracted to avoid duplicated controller logic.

## Public Roadmap

See `ROADMAP.md`.

## Privacy

JuridiColombia does not require a backend server for the core extension workflow. Saved links are stored locally in the browser through Chrome Storage. See `PRIVACY.md`.

## Security

Please do not open public issues for security vulnerabilities. See `SECURITY.md` for responsible disclosure.

## Contact

See `CONTACT.md`.

## License

All rights reserved unless a license is added later. This public repository is intended for product transparency and roadmap visibility, not as an open-source release of the private source code.
