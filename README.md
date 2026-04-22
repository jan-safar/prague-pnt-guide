# Prague: A Walking Guide to the Capital of Satellite Navigation 🛰️

A thematic walking guide to Prague for the **Positioning, Navigation and Timing (PNT)** community – tracing the city's extraordinary scientific heritage from the 1410 Astronomical Clock to the EU Agency for the Space Programme (EUSPA), which manages Galileo from its Prague headquarters.

Originally prepared for attendees of the **RTCM SC 104** (Differential GNSS) and **RTCM SC 134** (Integrity Monitoring for High Precision GNSS) meetings in Prague, **19–21 May 2026**.

📖 [Read the guide](guide.md) | 🗺️ [View the interactive map](https://jan-safar.github.io/prague-pnt-guide/)

## What's in this guide

Prague is where the foundational science of satellite navigation was forged:

- **Jost Bürgi** and **Erasmus Habermel** (late 1500s) – precision clockmakers and instrument makers at Rudolf II's court, whose sextants and astrolabes enabled the observations that followed
- **Tycho Brahe** (1599–1601) – his planetary observations, made in Prague, gave Kepler the data for orbital mechanics
- **Johannes Kepler** (1600–1612) – derived the first two laws of planetary motion here; the Keplerian elements in every GNSS ephemeris are named for this work
- **Christian Doppler** (1842) – announced the Doppler effect to six people at the Royal Bohemian Society of Sciences in Prague; every GNSS receiver uses this principle
- **Ernst Mach** (1867–1895) – 28 years challenging Newtonian absolutes, shaping Einstein's thinking
- **Albert Einstein** (1911–1912) – worked on the equivalence principle and gravitational light deflection in Prague; without general relativity, GNSS clocks would drift ~38 μs/day
- **Hedy Lamarr** (1933) — starred in the film *Ecstasy* shot at Prague's Barrandov Studios; later co-invented spread-spectrum signal transmission, the principle behind GPS' CDMA signal structure
 
The guide also covers Prague's **Astronomical Clock** (1410), the **Prague Meridian**, the **Klementinum observatory**, **EUSPA** and more – all with a focus on their connections to PNT.

## Files

| File | Description |
|------|-------------|
| [`guide.md`](guide.md) | The full walking guide – itinerary, history, practical info |
| [`places.geojson`](places.geojson) | All sites as GeoJSON data (also renders as a basic map on GitHub) |
| [`index.html`](index.html) | [Interactive map](https://jan-safar.github.io/prague-pnt-guide/) with colour-coded markers and links to the guide |
| [`sources.md`](sources.md) | Sources and references used in the guide |

## Interactive map

**[View the interactive map](https://jan-safar.github.io/prague-pnt-guide/)** – colour-coded markers for each site, with popups showing the PNT theme, practical details, and a direct link to the full entry in the guide.

You can also link directly to a specific site on the map by adding its ID to the URL, e.g. [`#orloj`](https://jan-safar.github.io/prague-pnt-guide/#orloj) for the Astronomical Clock. The map zooms to the marker and opens its popup.

The map reads from `places.geojson`, so contributors only need to edit the GeoJSON file – the map updates automatically.

## Contributing

Corrections, additions and translations are welcome! See [`CONTRIBUTING.md`](CONTRIBUTING.md) for guidelines. This guide was researched with care, but some details (opening hours, plaque locations, addresses) benefit from on-the-ground verification.

Areas where contributions would be especially valuable:

- **Fact-checking** addresses, plaque inscriptions and opening hours
- **Photographs** of the sites (with appropriate licensing)
- **Translations** into Czech, German, French or other languages
- **Additional PNT-relevant sites** in or near Prague
- **Improved walking directions** between stops
- **More decent places to eat and drink** along the route

## Licence

This work is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE).

You are free to share and adapt this material for any purpose, including commercially, as long as you give appropriate credit.
