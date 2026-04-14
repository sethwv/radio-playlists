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
| **ca** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/5a64e1d0557cc60e1f9aec04f358a60ba03c1e62) |
| **ca-bc** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-bc/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/c621c5dd5a7f712c9e90a1b96f202957344320b4) |
| [ca-bc-vancouver.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-bc-vancouver.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-bc-vancouver/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/f9524e794a9a7719b081f3e65d838ffa09086ae5) |
| **ca-on** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/547ca571ac46f1da07cea7d46d49ee4d4fbddce2) |
| [ca-on-barrie.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-on-barrie.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on-barrie/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/65fef55d8fb1d21ec12cff4f2a4228fe72809caa) |
| [ca-on-collingwood.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-on-collingwood.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on-collingwood/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/e66d5f4233fa2d901532efb5a4a426d09b363d96) |
| [ca-on-kitchener.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-on-kitchener.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on-kitchener/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/f257b2614be3c79194a497ea18b524f025b935d0) |
| [ca-on-toronto.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-on-toronto.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-on-toronto/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/1075821adceefdfd601a9597178f8058166c34ea) |
| [ca-sportsnet.csv](https://github.com/sethwv/radio-playlists/blob/main/ca-sportsnet.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/ca-sportsnet/playlist.m3u8 | [2026-02-27 18:59 UTC](https://github.com/sethwv/radio-playlists/commit/532fa0dad531b24e5e4bb91a842f3985c8160730) |
| **us** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/2966e4e47e38737cb7b3207608e0acf9381e9e2e) |
| **us-ca** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-ca/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/227e070939c46512cce1fa7f36e7c0057928d974) |
| [us-ca-sanfancisco.csv](https://github.com/sethwv/radio-playlists/blob/main/us-ca-sanfancisco.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-ca-sanfancisco/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/dee1687746404b0d0d5c771f5ba9128fd49729fb) |
| **us-mo** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-mo/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/1f08558d0314412ce49d043660c758ff1c5998dc) |
| [us-mo-stlouis.csv](https://github.com/sethwv/radio-playlists/blob/main/us-mo-stlouis.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-mo-stlouis/playlist.m3u8 | [2026-04-14 16:53 UTC](https://github.com/sethwv/radio-playlists/commit/cb44c7019f7df00175e2567e00c52e8f24039ac1) |
| **us-ny** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-ny/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/9dc83270267ed4805019ec2cf16ec6099761f987) |
| [us-ny-newyork.csv](https://github.com/sethwv/radio-playlists/blob/main/us-ny-newyork.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/us-ny-newyork/playlist.m3u8 | [2026-04-14 17:00 UTC](https://github.com/sethwv/radio-playlists/commit/1d8f27db8b8e15e615ac4232a3d6d74e8304dc51) |
| **xx** | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/xx/playlist.m3u8 | [2026-04-14 17:40 UTC](https://github.com/sethwv/radio-playlists/commit/6fc9d7f31b800c52dfa94225b719b826155d6092) |
| [xx-temp.csv](https://github.com/sethwv/radio-playlists/blob/main/xx-temp.csv) | https://raw.githubusercontent.com/sethwv/radio-playlists/refs/heads/xx-temp/playlist.m3u8 | [2026-04-14 17:40 UTC](https://github.com/sethwv/radio-playlists/commit/cfe0b8e1195a829551c271d9ed581b59931a3b2e) |
