Popup

The little window when you click the extension icon.

Built with popup.html + popup.css + popup.js.

Short-lived → closes when the popup is closed.

Good for small UI (buttons, status, settings).

Service Worker (Background)

A special script (no DOM, no HTML).

Runs in the background only when needed.

Good for: event handling (tab opened, message received, alarm fired).

Orchestrates: injects scripts, routes messages, stores data.

Content Scripts

JS files injected into webpages.

Can read and change the page DOM (like LinkedIn job cards).

Isolated from page JS for security, but can manipulate HTML elements.

👉 Think of it like:

Popup = your control panel

Service Worker = the project manager

Content Script = the worker inside the page