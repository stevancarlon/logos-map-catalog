# Logos Map Library development catalog

A fork of the official `logos-co/logos-modules-release-base` template, using
`logos-co/logos-modules-release-action` pinned at
`00ad4e5adb7aac75b3e3f3acc6b8d7a466294e9c`.

Source: https://github.com/stevancarlon/logos-map-library

Catalog entry point:
https://raw.githubusercontent.com/stevancarlon/logos-map-catalog/main/logos-repo.json

This is a development catalog. Source publication does not mean packages are
available: verify the release index and individual platform assets before
installing. Local Linux integration passed; macOS runtime, public testnet
registry deployment, public map coverage and independent adoption are not yet
proved. Dependency notice gaps remain explicitly documented in the sources.
Packages are unsigned, with no trusted signing identity claimed.

The single source submodule contains four independently buildable exports:
`prize_maps`, `maps_publisher`, `maps_distribution`, and `logos_maps`.
Use the individual release workflows or “Release all Map Library modules”.
Both Linux x86_64 and macOS Apple Silicon are requested. The upstream action may
publish a partial variant set after a platform failure; check both build legs
before claiming cross-platform support.
