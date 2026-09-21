# Aria for macOS

Public downloads and signed Sparkle updates for Aria, an on-device AI chat app. The app source is maintained separately.

[Download Aria 1.0.3](https://github.com/VISHNUVU/Aria-Downloads/releases/download/updates/Aria-1.0.3-1003.zip) · [All downloads](https://github.com/VISHNUVU/Aria-Downloads/releases/tag/updates)

## Requirements

- Apple Silicon Mac
- macOS 26.5 or newer
- Internet access for the initial language-model download and app updates

## Install and update

Unzip the download and move Aria.app into a writable Applications folder. This build is ad-hoc signed and not Apple notarized; macOS may require approval in System Settings → Privacy & Security on first launch. Do not disable Gatekeeper globally.

Later updates are available through **Aria → Check for Updates…**. Update archives are authenticated with Sparkle EdDSA signatures. The public feed is the `appcast.xml` release asset.

Conversations are saved locally. An older app without this feed requires a one-time manual installation of this version. The SwiftUI app's bundle identifier is `com.aria.localai.Aria`; other apps named Aria may be separate installations.

Version 1.0.3 adds model download progress, preparation status, and clearer retry guidance when setup fails.
