# Headroom downloads

Official installer downloads and release notes for Headroom, a native macOS utility that lets you choose when the menu bar hides.

## Download

[Download Headroom 0.4.0 for Apple Silicon](https://github.com/Oluwaseunus/headroom-downloads/releases/download/v0.4.0/Headroom.dmg)

Requires macOS 15 or later. Open the disk image and drag Headroom into Applications.

This is a Developer ID signed preview and is not notarized. See the [release notes](https://github.com/Oluwaseunus/headroom-downloads/releases/tag/v0.4.0) for compatibility and permission details. Each release includes a SHA-256 checksum.

This repository distributes installers and release notes only.

## Download counts

GitHub records downloads per installer asset. To inspect counts with the GitHub CLI:

```sh
gh api --paginate repos/Oluwaseunus/headroom-downloads/releases --jq '.[] | .tag_name as $version | .assets[] | select(.name | endswith(".dmg")) | [$version, .name, .download_count] | @tsv'
```

Counts include repeat downloads and verification downloads; they do not represent unique users or confirmed installations.

## Contact

[businesswithseun@gmail.com](mailto:businesswithseun@gmail.com)
