# Chrome Web Store Permission Justifications

## storage
Required to keep KTVis.IT session metadata and locally generated recording data available for preview/download after a recording.

## tabs
Required to coordinate the recording workflow with browser tabs and identify the tab context involved in the KT session.

## downloads
Required to let the user save the locally generated KT video to the user's computer.

## offscreen
Required because Chrome's MediaRecorder/display-capture processing is performed in an offscreen extension document while the browser UI remains available to the user.

## Host permissions: <all_urls>
KTVis.IT's core purpose is browser walkthrough recording. The content script is used on the pages where the user performs the walkthrough so the floating recording controls and chapter controls can operate during the session. The extension does not use this access to collect browsing history or transmit page content to a developer-operated server.
