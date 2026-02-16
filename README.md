# KpiClock Browser Extension — Releases

Pre-built packages for the KpiClock browser extension (Chrome and Firefox). Use this with the [KpiClock desktop app](https://github.com/KpiClock/app) for task tracking and website usage monitoring.

## How to install

### 1. Download the extension

1. Open the [Releases](https://github.com/KpiClock/browser-ext-release/releases) page.
2. Download the zip for your browser:
   - **Chrome / Edge / Brave:** `kpiclock-browser-ext-chrome-mv3-<version>.zip`
   - **Firefox:** `kpiclock-browser-ext-firefox-mv2-<version>.zip`
3. Unzip the file to a folder on your computer (e.g. `Downloads/KpiClock-chrome` or `Downloads/KpiClock-firefox`).

### 2. Install in Chrome (or Chromium-based browsers)

1. Open Chrome and go to `chrome://extensions/`.
2. Turn on **Developer mode** (toggle in the top-right corner).
3. Click **Load unpacked**.
4. Select the **unzipped folder** (e.g. the `chrome-mv3` folder inside the zip you extracted).
5. The KpiClock extension will appear in your toolbar. Pin it if you like.

### 3. Install in Firefox

1. Open Firefox and go to `about:debugging`.
2. Click **This Firefox** in the left sidebar.
3. Click **Load Temporary Add-on…**.
4. In the file picker, open the **unzipped folder** and select the **`manifest.json`** file (inside the `firefox-mv2` folder from the zip you extracted).
5. The extension will load. Note: “Temporary” means it will be removed when you close Firefox unless you use a different method (e.g. signing and installing via Add-ons site).

### 4. Connect to the desktop app

- Install and open the [KpiClock desktop app](https://github.com/KpiClock/app), then log in.
- Keep the desktop app running while you use the browser. The extension will connect to it for task tracking and website usage.
- If the extension shows as disconnected, check that the desktop app is running.

## Requirements

- **Desktop app:** The extension is designed to work with the KpiClock desktop application. Install it from the [KpiClock app releases](https://github.com/KpiClock/app/releases).
- **Permissions:** The extension may request access to storage, tabs, and active tab for time tracking and ClickUp integration.

## Support

For issues and feature requests, contact your administrator or refer to your organization’s KpiClock documentation.
