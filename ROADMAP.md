# Roadmap

This roadmap is public-facing and intentionally focused on product direction, not internal implementation details.

## Current MVP

- Chrome Extension MV3.
- Search by `artículo` number.
- Keyword search across embedded legal texts.
- Previous / Next navigation for multiple keyword results.
- Embedded references for `Código Civil`, `Código de Comercio`, and `Código General del Proceso`.
- Quick links to official public sources.
- User-managed custom links stored locally.

## Near-Term Improvements

- Highlight keyword matches inside `artículo` text.
- Improve relevance ranking for keyword search.
- Add favorite `artículos`.
- Add copy/export actions for selected `artículos`.
- Improve the expanded window layout.
- Add screenshot-based documentation for the public repository.

## Data Quality

- Keep official-source URLs reviewed.
- Add documented checks for extraction scripts.
- Track source update dates for each legal dataset.
- Review generated legal text before release builds.

## Performance

- Monitor bundle size as more legal datasets are embedded.
- Explore lazy-loading legal datasets if the extension grows.
- Keep search fast without adding unnecessary runtime dependencies.

## Product Validation

- Collect feedback from attorneys, law students, and legal operations users.
- Publish issues for usability improvements.
- Validate whether the offline-first model is a strong differentiator for legal workflows.

## Longer-Term Ideas

- Saved searches.
- Cross-reference navigation between `artículos`.
- Notes per `artículo`.
- Team distribution for small legal firms.
- Optional paid tier only if it does not compromise privacy-first positioning.
