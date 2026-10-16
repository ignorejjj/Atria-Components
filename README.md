# Atria runtime components

Versioned runtime components downloaded by the Atria desktop app. This public repository distributes component archives and their corresponding source materials; Atria application development is maintained separately.

## Installation

Install Atria from the DMG provided by your test coordinator. On first launch, Atria prepares the CAD and Blender components in the background. The presentation editor is included in the lightweight app. No GitHub account, token, Python installation, or separate Blender installation is required.

Components are stored in the user's Atria component directory, outside the signed application. Compatible installations are reused after app updates. Download progress, cancellation and retry are available under Settings → Applications and components.

The initial component release targets macOS 14 or later on Apple Silicon. It is a beta distribution; clean-machine installation and signing/notarization checks are separate release evidence.

## Release assets

The application pins a named component release and validates archive sizes and SHA-256 digests before activating a new version. Releases contain the component catalog, CadQuery/Python archive, presentation editor archive, original Blender DMG, checksum sidecars, corresponding source archives, and a source manifest identifying their upstream origins.

Published component versions are not overwritten. New incompatible component sets use a new release tag.

## Third-party software

Each component retains its upstream license and copyright notices. The presentation editor includes its corresponding source archive. The release's `THIRD_PARTY_NOTICES.md`, `SOURCE_MANIFEST.json`, and source notices describe the runtime sources and build materials. This repository does not relicense third-party binaries under a single blanket license.

## Downloads

Use the [Releases page](https://github.com/ignorejjj/Atria-Components/releases) for published component sets. Atria downloads these files automatically; manual download is normally unnecessary.
