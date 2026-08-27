# KTVis.IT — Reviewer Notes

KTVis.IT is a Manifest V3 Chrome extension with a single purpose: local visual knowledge-transfer recording.

### Basic test flow
1. Install the extension.
2. Open any normal HTTPS webpage.
3. Click the KTVis.IT toolbar icon.
4. Start KT recording.
5. Choose a tab, window, or screen in Chrome's capture chooser.
6. Use the floating controls to add a chapter.
7. Click Pause; the indicator changes from red to yellow.
8. Click the same button again to Resume; the indicator changes back to red.
9. Click Stop.
10. Preview and download the generated WebM recording.

### Privacy / network behavior
The extension package contains no remote URLs, fetch calls, WebSockets, or remotely hosted executable code. Recording and session processing are performed locally in the extension.

### Audio
KTVis.IT does not record audio.

### Why broad page access is used
The extension's purpose is to support a browser-wide walkthrough. The floating recording/chapter controls are injected into the page where the user performs the walkthrough. Page access is not used to transmit browsing content to a developer-operated server.

### Important product boundary
KTVis.IT does not currently provide DRM, encryption, enterprise identity enforcement, or technical prevention of a user sharing a downloaded video. The product's privacy design is local-only processing, not copy protection.
