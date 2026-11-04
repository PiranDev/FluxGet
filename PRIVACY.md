# FluxGet Privacy Policy

**Applies to:** FluxGet Desktop (Core and Media) and the FluxGet Download Manager browser extension.

## 1. Overview

FluxGet is a free Windows download manager. Its browser extension connects Firefox to the FluxGet desktop application running on the same computer.

This policy describes the information processed for download management, local browser integration, and optional network-based features.

## 2. Browser Extension

The Firefox extension lets users send supported download links to the FluxGet desktop application. When a user sends a link or enables browser download integration, information needed to handle the download, such as its URL, may be transferred to the locally running application.

The extension communicates with the local FluxGet service at `127.0.0.1` on port `6874`. A pairing mechanism is used to authorize this connection.

The extension does not request browser cookie or browsing-history permissions. This does not mean that download URLs or other information needed for a requested download are never processed.

## 3. Local Storage

FluxGet stores download-related information and settings locally on the user's device. Such information may include:

- Download URLs and filenames
- Download status and progress
- Application preferences
- Browser-extension pairing credentials

## 4. External Network Connections

Although the browser extension communicates with the desktop application locally, the desktop application may contact external services to perform requested operations, including:

- Download servers for user-requested files
- Third-party media-tool release services, when an applicable feature is used
- The GitHub API (`api.github.com`) to check for updates when configured

External services can receive ordinary connection metadata, including the user's IP address, and may process requests under their own privacy policies.

## 5. User Choices

Users can choose which links to send to FluxGet. Optional browser-download integration can be enabled or disabled in the extension's settings. Users can stop browser integration by disabling or uninstalling the extension.

## 6. Support

For privacy questions or bug reports, visit:

https://github.com/PiranDev/FluxGet/issues

**Official project:** https://github.com/PiranDev/FluxGet
