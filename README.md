# radio-playlists
## Disclaimer

This repository contains only links to streams that are **freely and publicly accessible** without authentication, DRM circumvention, or any form of paywall bypass. All streams are broadcast by licensed radio stations for public reception. No audio content is hosted, reproduced, or redistributed here.

Use of these streams is subject to the terms of the respective broadcasters and applicable laws in your jurisdiction. This project is intended for personal, non-commercial use only.

## Contributing

Pull requests that add or update CSV files are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

Found a problem or have a suggestion? Open an issue:

- [Report a Broken Link](https://github.com/sethwv/radio-playlists/issues/new?template=broken-link.yml)
- [Report a Broken Logo](https://github.com/sethwv/radio-playlists/issues/new?template=broken-logo.yml)
- [Report Incorrect Info](https://github.com/sethwv/radio-playlists/issues/new?template=incorrect-info.yml)
- [Request a Station](https://github.com/sethwv/radio-playlists/issues/new?template=station-request.yml)
- [Request a Region](https://github.com/sethwv/radio-playlists/issues/new?template=region-request.yml)

## Usage

Playlists are generated from CSV source files and published to per-csv-file branches. The `main` branch contains only the source CSV files, each named `<name>.csv`. The workflow generates a `playlist.m3u8` file for each CSV and commits it to a branch named `<name>`.

### Adding or editing stations

Edit or create a `<name>.csv` file on `main`. Pushing the change triggers the workflow, which generates `playlist.m3u8` and commits it to the `<name>` branch.

CSV format:

| column | description |
|--------|-------------|
| `section` | Section header label (first row of a group only) |
| `chno` | Channel number (`tvg-chno`) |
| `title` | Display name — first word used as callsign for `tvg-id` |
| `group` | Group title (e.g. `RADIO - FM`) |
| `logo` | Logo URL (`tvg-logo`) |
| `url` | Stream URL |

## Playlists

<!-- AUTO-GENERATED: Do not edit below this line -->

| CSV | Playlist | Updated |
|-----|----------|---------|
| **ca** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/64ecbbb203645ef6e19aa86475dbec6887622f6b) |
| **ca-bc** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-bc/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/ab30dfe6e2152fd8f057de563a0c839253525077) |
| [ca-bc-vancouver.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-bc-vancouver.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-bc-vancouver/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/07cb6bdf0c4b055fa9c6a1c6f8de9a99e736982b) |
| **ca-on** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/e2c50a65eaff5547206004c162c53c3bca768708) |
| [ca-on-barrie.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-on-barrie.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on-barrie/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/4105d7f7b5108cdb0b6021fb1d991b80067de76f) |
| [ca-on-collingwood.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-on-collingwood.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on-collingwood/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/e66d5f4233fa2d901532efb5a4a426d09b363d96) |
| [ca-on-kitchener.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-on-kitchener.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on-kitchener/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/1666d8dfd2bf75051e6aebe3bbc6c3942fb042a3) |
| [ca-on-toronto.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-on-toronto.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on-toronto/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/53dbd09b667790ec90601e781e2e99bf7541372c) |
| [ca-sportsnet.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-sportsnet.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-sportsnet/playlist.m3u8 | [2026-02-27 18:59 UTC](https://github.com/sethwv/radio-playlists/commit/532fa0dad531b24e5e4bb91a842f3985c8160730) |
| **us** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/4f5203cb17dbc6037e81665ff387ba30a35d3048) |
| **us-ca** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-ca/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/7e316c927a57d2a3d522c8615fb1161ef06c59e7) |
| [us-ca-sanfancisco.csv](https://github.com/sethwv/radio-playlists/blob/main/us-ca-sanfancisco.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-ca-sanfancisco/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/058bd944b6da65b1726eec36967ec77b8a60d493) |
| **us-mo** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-mo/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/1f08558d0314412ce49d043660c758ff1c5998dc) |
| [us-mo-stlouis.csv](https://github.com/sethwv/radio-playlists/blob/main/us-mo-stlouis.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-mo-stlouis/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/cb44c7019f7df00175e2567e00c52e8f24039ac1) |
| **us-ny** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-ny/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/a69b2454e4c512a1d9f97a8d0eb730b72e83626b) |
| [us-ny-newyork.csv](https://github.com/sethwv/radio-playlists/blob/main/us-ny-newyork.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-ny-newyork/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/2d0cdebd56f7229005ae50855fb67a2d1e00c2df) |
