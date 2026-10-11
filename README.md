# Open Tiiny updates

This repository distributes authentic Open Tiiny release objects. The application source is maintained separately.

The approved stable update directories are
`https://ramarivera.github.io/open-tiiny-updates/stable/linux/x64/` and
`https://ramarivera.github.io/open-tiiny-updates/stable/darwin/arm64/`.

Release objects are built and signed outside GitHub Actions. Each publication
downloads explicitly selected immutable Linux and macOS releases and deploys
both feeds together. Linux carries its AppImage, signed manifest and SDK
metadata. macOS carries its Developer ID-signed and notarized ZIP and DMG,
signed manifest and SDK metadata. The workflow has no private signing key.

The `release_tag` input selects Linux. The `macos_release_tag` input selects
macOS and defaults to `macos-arm64-0.0.40`, so an existing Linux publication
command retains the macOS feed. Choose both tags explicitly when changing
either platform. Publishing one platform never deploys an incomplete site
that removes the other platform.

The immutable [Linux x64 0.0.1 release](https://github.com/ramarivera/open-tiiny-updates/releases/tag/linux-x64-0.0.1) provides the initial AppImage and Debian package. The immutable [Linux x64 0.0.2 release](https://github.com/ramarivera/open-tiiny-updates/releases/tag/linux-x64-0.0.2) provides the AppImage, signed manifest and SDK metadata deployed to the stable update directory.

Open Tiiny is an unofficial project and is not affiliated with Tiiny AI.
