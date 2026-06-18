# Dotfiles for Ashwin

A collection of custom assets and configuration files used with [Nuvio](https://github.com/NuvioMedia/NuvioMobile) — a streaming app that pairs with Debrid services (similar to Stremio) to deliver direct HTTP streams.

---

## Nuvio Collections

- **[Streaming](/streaming/)** — Cover art for streaming service collections (Netflix, HBO Max, Disney+, Hulu, Prime Video, Apple TV, Paramount+, Peacock, Discovery+, Crunchyroll). Includes static `/covers` artwork and animated `/focus` WEBPs that play when an item is focused.

- **[Studios](/studios/)** — Cover images for studio-based collections (A24, Marvel, Warner Bros., Disney, etc.), mapped to their respective TMDB company IDs.

- **[Awards](/awards/)** — Cover images for award ceremony collections (Oscars, Golden Globes, BAFTA, and more), backed by Trakt list catalog sources.

- **[Decades](/decades/)** — Poster cover images for decade-based collections (1960s–2020s).

- **[Nuvio](/nuvio/)** — Ready-to-import Nuvio configs:
  - `my-collections.json` — collections config covering Streaming, Studios, Awards, and Decades.
  - `AshwinBadges.json` — stream tag/badge config with 112 pattern-matched badges across 11 groups (Special Tags, Media Source, Resolution, Quality, IMAX, Visual, Audio, Channels, Encoder, Streaming, Language). Each badge matches release titles by regex and renders a styled, image-backed tag on streams.
