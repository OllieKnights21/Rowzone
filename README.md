# RowZone

Live heart rate zone display for rowing (or any indoor session). Open the page, connect your Bluetooth heart rate strap, and go.

- **Gauge** showing your current heart rate across Zones 1 to 5, with the target zone marked.
- **Line graph** of heart rate over time with your target zone shaded (default Zone 2, selectable).
- **Time in zone** bars for Zones 1 to 5, with the share of the session in your target.
- Zones are editable (or set from max HR) and saved in your browser. Defaults come from Ollie's Garmin zones (max 189).
- Export the session as CSV. Keeps the screen awake while connected.

## Browser support

Uses Web Bluetooth: works in **Chrome or Edge** on Windows, macOS, Android and ChromeOS. Safari/iOS don't support it; on iPhone/iPad use the **Bluefy** browser app. Press **Demo** to see it working without a strap.

Single static file (`index.html`), no build step, no data leaves the browser.
