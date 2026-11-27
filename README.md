# Awesome-Media-Automation-Home-Server-Management

## Top Media Automation & Home Server Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Automated Media Acquisition, Library Organization & Request Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Media Automation & Home Server Management**. These tools automate the entire lifecycle of a personal media library—from monitoring for new releases, searching indexers, sending downloads to clients, renaming and organizing files, fetching subtitles, to handling user requests—typically built around the *Arr ecosystem.

**Examples** include Sonarr, Radarr, Lidarr, Readarr, Prowlarr, Bazarr, Overseerr, Ombi, Tautulli, Jackett, and holyarrs/holyarrs (the category leaders and notable projects).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting media automation pipelines, transparent request management, and privacy-respecting library orchestration—ideal for homelab enthusiasts, cord-cutters, and developers building fully automated media servers without cloud dependencies.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Overseerr](https://overseerr.dev/)**  
  Media request and discovery portal for Plex users, integrating with Sonarr and Radarr to allow household members to request movies and TV shows, with approval workflows [citation:2][citation:6].

- **[Ombi](https://ombi.io/)**  
  Self-hosted web application for managing Plex, Emby, and Jellyfin requests, with support for movies, TV shows, music, and books, plus notification integrations [citation:2].

- **[Tautulli](https://tautulli.com/)**  
  Monitoring and tracking tool for Plex Media Server (formerly PlexPy), providing analytics, watch history, and automated newsletters [citation:8].

- **[Jackett](https://github.com/Jackett/Jackett)**  
  Proxy server that translates queries from media managers (Sonarr, Radarr, etc.) into tracker-specific HTTP queries, serving as an indexer aggregator [citation:8].

## Open-Source GitHub Projects

- **[Sonarr](https://github.com/Sonarr/Sonarr)**  
  Smart PVR for TV shows that monitors RSS feeds for new episodes, grabs releases via Usenet or BitTorrent, and organizes files with proper naming—the cornerstone of the *Arr ecosystem [citation:1][citation:12].

- **[Radarr](https://github.com/Radarr/Radarr)**  
  Movie collection manager for Usenet and BitTorrent users, acting as an independent fork of Sonarr to automate movie downloading, upgrading, and organization [citation:1][citation:10].

- **[Lidarr](https://github.com/Lidarr/Lidarr)**  
  Music collection manager for Usenet and BitTorrent users, monitoring artists for new albums and automating music library organization [citation:1][citation:12].

- **[Readarr](https://github.com/Readarr/Readarr)**  
  Book and audiobook collection manager for Usenet and BitTorrent users, automating ebook acquisition and library organization [citation:1][citation:12].

- **[Prowlarr](https://github.com/Prowlarr/Prowlarr)**  
  Indexer manager/proxy that integrates with Sonarr, Radarr, Lidarr, and Readarr, centralizing indexer configuration and automatically syncing indexers to connected applications [citation:1][citation:12].

- **[Bazarr](https://github.com/morpheus65535/bazarr)**  
  Companion application for Sonarr and Radarr that manages and downloads subtitles based on configured languages and preferences [citation:1][citation:12].

- **[Seerr (formerly Jellyseerr/Overseerr)](https://github.com/seerr-team/seerr)**  
  Open-source media request and discovery manager for Jellyfin, Plex, and Emby, integrating with Sonarr and Radarr to handle user requests with granular permissions [citation:6][citation:11].

- **[HolyArrs](https://github.com/HolyArrs/HolyArrs)**  
  All-in-one self-hosted media automation app that consolidates the functionality of Sonarr, Radarr, Lidarr, Prowlarr, Bazarr, and Seerr into a single lightweight container (~16 MB), with import support from existing *Arr setups [citation:4][citation:9].

- **[Huntarr](https://github.com/Huntarr/Huntarr)**  
  Companion tool that scans existing *Arr libraries (Radarr, Sonarr, Lidarr) to find missing media or outdated releases and triggers upgrades [citation:1].

### Additional Strong Open-Source Options

- **[Medusa](https://github.com/pymedusa/Medusa)** — Automatic video library manager for TV shows, an alternative to Sonarr with a focus on failed download handling [citation:10].
- **[Headphones](https://github.com/rembo10/headphones)** — Automated music downloader for NZB and Torrent, supporting SABnzbd, NZBget, Transmission, and other clients [citation:10].
- **[Whisparr](https://github.com/Whisparr/Whisparr)** — Sonarr fork for adult content management, following the same automation patterns as the main *Arr suite [citation:1].
- **[Unpackerr](https://github.com/Unpackerr/unpackerr)** — Companion tool that extracts archives from completed downloads for the *Arr ecosystem.
- **[Cross-seed](https://github.com/Crossseed/cross-seed)** — Tool to cross-seed torrents across multiple trackers, useful for maintaining ratio in automated setups.

**Frameworks for building custom systems**: Combine **Prowlarr** for centralized indexer management, **Sonarr/Radarr/Lidarr/Readarr** for media-specific automation, **Bazarr** for subtitles, **Seerr** for user request handling, and **qBittorrent** or **SABnzbd** as download clients. Use **HolyArrs** as a lightweight consolidated alternative if a single-container solution is preferred. Deploy with **Docker Compose** for reproducible infrastructure.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Media automation tools must comply with local copyright laws; users are responsible for ensuring they have the right to download and store content.
- Self-hosted open-source solutions require proper network security configuration, especially when exposing request portals or management interfaces to the internet.
- Some tools listed may interact with indexers or trackers that require their own terms of service; respect platform policies and content creators' rights.

---

**Made for homelab enthusiasts, self-hosters, cord-cutters, and developers building automated, privacy-respecting media infrastructure.**  
Let's make media automation and home server management more open, interoperable, and user-controlled.
