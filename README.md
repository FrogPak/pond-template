# My Pond

<!-- Replace this README with your own once the pond is running. -->

A signed Flatpak remote, built with [FrogPak](https://github.com/FrogPak/engine) and hosted on GitHub Pages.

The landing page lists every app with its install command: **https://OWNER.github.io/REPOSITORY/**

## Setting up this pond

1. Make the repository public (GitHub Pages is free only for public repositories).
2. **Settings > Pages > Source:** GitHub Actions.
3. Create a signing key and add it as the `GPG_PRIVATE_KEY` secret: [instructions](https://github.com/FrogPak/engine/blob/main/docs/setup.md#signing-key).
4. Edit `frogpak.yml`: set the title and remote name, and list your apps.
5. **Actions > Publish > Run workflow.**

The full guide is [docs/setup.md](https://github.com/FrogPak/engine/blob/main/docs/setup.md) in the engine repository.
