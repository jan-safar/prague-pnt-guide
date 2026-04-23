# Contributing to the Prague PNT Walking Guide

Thank you for your interest in improving this guide! Contributions from the PNT/GNSS community – and from Prague locals – are especially welcome.

## How to contribute

### Corrections and fact-checks

If you spot an error (wrong address, incorrect date, outdated opening hours, misattributed plaque inscription), please:

1. **Open an issue** describing the error and providing the correct information, ideally with a source or photo.
2. Or **submit a pull request** editing `guide.md` directly.

### Adding new sites

If you know of a PNT-relevant site in Prague not yet covered (a plaque, a building, a museum exhibit, a person with a Prague connection), please open an issue or PR with:

- The site name and exact address
- Its connection to PNT, GNSS, astronomy, geodesy, timekeeping or related fields
- Whether it's visitable inside or exterior/plaque only
- A source or reference

### Photos

Photos of the sites are very welcome. Please ensure they are either:

- Your own work, licensed under CC BY 4.0 (or more permissive), or
- Already under a compatible open licence (CC0, CC BY, CC BY-SA)

Include the photographer credit and licence in your PR.

### Translations

Translations of `guide.md` into other languages are welcome. Please name translated files as `guide.[lang].md` (e.g., `guide.cs.md` for Czech, `guide.de.md` for German).

### Map updates

To add or correct a location on the map, edit `places.geojson`. Each feature needs:

- `geometry`: point coordinates as `[longitude, latitude]`
- `properties`: `id`, `name`, `theme`, `description`, `visit_type` and `marker-color`

GitHub renders GeoJSON files as interactive maps, so you can preview your changes. The interactive map at `index.html` reads from `places.geojson`, so any updates there will automatically reflect on the map.

## Style guidelines

- Keep the tone **informative, warm, and accessible** — this is for an international technical audience, not an academic paper
- Always explain the **PNT/GNSS relevance** of each site
- Prefer **verified facts with sources** over colourful legends (but legends can be mentioned as such)
- Use **British English** spelling (the original author's preference)

## Code of conduct

Be kind, be accurate, be helpful. This is a niche community project – keep contributions constructive and collegial.

## Licence

By contributing, you agree that your contributions will be licensed under [CC BY 4.0](LICENSE), consistent with the rest of the repository.
