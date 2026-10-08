# Open Tiiny updates

This repository distributes authentic Open Tiiny release objects. The application source is maintained separately.

The approved Linux x64 stable update directory is `https://ramarivera.github.io/open-tiiny-updates/stable/linux/x64/`.

Release objects are built and signed outside GitHub Actions. The publication workflow downloads an explicitly selected immutable release and deploys its AppImage, signed manifest and SDK metadata through GitHub Pages. The workflow has no private signing key.

The immutable [Linux x64 0.0.1 release](https://github.com/ramarivera/open-tiiny-updates/releases/tag/linux-x64-0.0.1) provides the initial AppImage and Debian package. The immutable [Linux x64 0.0.2 release](https://github.com/ramarivera/open-tiiny-updates/releases/tag/linux-x64-0.0.2) provides the AppImage, signed manifest and SDK metadata deployed to the stable update directory.

Open Tiiny is an unofficial project and is not affiliated with Tiiny AI.
