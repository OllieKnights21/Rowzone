# RowZone

Live heart rate zone display for a Concept2 rower. Open the page, connect over Bluetooth, and row.

- **Line graph** of heart rate over time with your target zone shaded (default Zone 2, selectable).
- **Time in zone** bars for Zones 1 to 5, with the share of the session in your target.
- Live tiles for HR, elapsed time, time in target, average/max HR, pace /500m, stroke rate and distance.
- Zones are editable (or set from max HR) and saved in your browser. Defaults come from Ollie's Garmin zones (max 189).
- Export the session as CSV. Keeps the screen awake while connected.

## Connecting

| Source | What you get |
|---|---|
| **Connect PM5** | Pace, stroke rate, distance, and heart rate if your strap is paired to the PM5 |
| **Connect HR strap** | Heart rate directly from any standard Bluetooth HR strap/watch broadcasting HR |

Connect both if you like: strap HR is used in preference to PM5 HR. Note a Bluetooth strap can usually only connect to one device at a time, so pair it either to the PM5 or to the browser.

## Browser support

Uses Web Bluetooth: works in **Chrome or Edge** on Windows, macOS, Android and ChromeOS. Safari/iOS don't support it; on iPhone/iPad use the **Bluefy** browser app. Press **Demo** to see it working without hardware.

Single static file (`index.html`), no build step, no data leaves the browser.
