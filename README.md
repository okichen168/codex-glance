# Codex Glance

Codex Glance is a small floating macOS window that keeps your Codex usage, reset credits, and token bucket in view.

It is free to download and use. No purchase or GitHub sign-in is required. You receive an official compiled application build, not a source-code license. Codex Glance is no longer licensed under MIT; its complete source code is not public.

## Download

[Download the latest release](https://github.com/okichen168/codex-glance/releases/latest)

- [macOS Apple Silicon DMG](https://github.com/okichen168/codex-glance/releases/latest/download/Codex-Glance-macOS-arm64.dmg)
- [macOS Apple Silicon ZIP](https://github.com/okichen168/codex-glance/releases/latest/download/Codex-Glance-macOS-arm64.zip) — alternate archive

## Requirements and installation

- macOS 11 or later on Apple Silicon. An Intel build is not in this initial release.
- The official Codex CLI or Codex desktop app must already be installed and signed in. Codex Glance reads usage from its local `codex app-server`; it does not replace Codex.
- Open the DMG and drag **Codex Glance** to Applications. The ZIP contains the same app as a fallback.

The first release is not commercially code-signed or notarized. macOS may show a Gatekeeper warning. Download only from this official release page, verify the SHA-256 value in `SHA256SUMS.txt`, then use Finder to Control-click the app, choose **Open**, and confirm **Open**. No administrator access is required.

To remove the app, quit Codex Glance and move it from Applications to Trash.

## What is public

This repository intentionally contains documentation, screenshots, icons, release checksums, and official binary assets only. It does not upload or publish the private source code. Third-party components continue to be governed by their own licenses; see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Codex Glance is unofficial and is not affiliated with OpenAI.
