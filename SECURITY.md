# Security

<!-- Turn on private reporting: Settings > Security > Private vulnerability reporting. -->

## Reporting a problem

If an app in this Pond is malicious, or has a security problem, please report it privately from this repository's **Security** tab, under **Report a vulnerability**. Don't open a public issue; that warns anyone exploiting the problem before the maintainers can act.

Problems in the Pond itself, such as its signing key or publishing workflow, go through the same place.

Include the app ID, the version or release, and what you found.

## What the maintainers can do

- **Remove the app.** It disappears from the Pond at the next publish. A Pond only publishes each app's latest release, so it can't hold an app at an older, safe version; if the latest release is the problem, the whole app comes out until a fixed release ships.
- **Warn users.** Removal doesn't uninstall copies people already have; they just stop getting updates. For a malicious app, the maintainers post a notice telling people to uninstall it:

  ```
  flatpak uninstall APP_ID
  ```

- **Report it upstream** to the app's developer, and to the forge hosting it if the developer is responsible.
