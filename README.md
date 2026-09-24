# One-Way Manifest: Ten things NASA left behind

An interactive 3D website for NASA Space Apps Challenge 2026, challenge **"Abandoned but not Forgotten: Storytelling about NASA's Discarded Equipment on the Moon and Mars."** Written for ages 12 to 16.

**Live site:** https://tgalitzine.github.io/One-Way-Manifest/

## What it is

- **Ten chapters**, each with a 3D scene: Surveyor 3, the Apollo Lunar Surface Experiments Package and retroreflectors, the Lunar Roving Vehicle, Opportunity, InSight, Pioneer 10, Voyager 1, the James Webb Space Telescope, the Nancy Grace Roman Space Telescope and New Horizons.
- **An atlas of 115 human-made objects** on the Moon (96) and Mars (19). Moon entries follow NASA NSSDCA's "Table of Anthropogenic Impacts and Spacecraft on the Moon" (last updated 13 Aug 2025).
- A **"Why not bring it home?"** sidebar in every chapter separates what NASA says from what NASA does not say.

The whole site is one self-contained file (`index.html`). It makes no network calls; the fonts, 3D models and photos are embedded.

## Sources and credits

- Facts come from NASA pages, listed at the end of each chapter and atlas card. The few non-NASA sources are labeled as such on the page.
- Every chapter claim and every atlas card was fact-checked in September 2026 against the sources listed on the page. Where NASA pages disagree, or NASA marks a fact as uncertain (for example, an impact it presumes but never observed), the page says so.
- NASA 3D models and NASA photos are credited where they appear. Photos are resized for the web and not altered.
- Third-party software and fonts: see [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md).
- This project is not affiliated with or endorsed by NASA.

## AI disclosure

This project was built with help from Claude (Anthropic) for research, fact-checking, writing, code and 3D reconstructions. Spacecraft without an official NASA model are shown as illustrative reconstructions, labeled "AI-assisted" on screen. NASA photographs are not AI-generated or altered.

## License

Original code, writing and reconstructions: [MIT License](LICENSE), Copyright (c) 2026 Theodore Galitzine. Third-party material keeps its own terms (see `THIRD_PARTY_NOTICES.md`).
