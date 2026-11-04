# Privacy Overview

FluxGet stores downloads and preferences locally on the user's computer. Local configurations may include URLs, filenames, and browser-extension pairing credentials.

The app can make network requests to download URLs requested by the user, optional third-party media-tool release services, and the GitHub API at `api.github.com` to check updates when configured. Requests to GitHub disclose ordinary network metadata such as the client's IP address to GitHub.

Browser extensions interact with the local FluxGet service at `127.0.0.1`. Separate browser-store permission notices apply. Do not interpret local storage as a promise that no external network requests occur.

This document is an initial disclosure requiring review against actual on-device behavior before public release.
