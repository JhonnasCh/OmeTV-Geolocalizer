# OmeTV-Geolocalizer

Real-time WebRTC IP & location lookup overlay for OmeTV.

---

## Features

- **WebRTC Interception:** Intercepts ICE candidates (`srflx`) to extract the peer's public IP address in real time.
- **Geolocation & Network Info:** Displays country, region, city, ISP, language, timezone, and precise coordinates with one-click copy.
- **Auto Video Snapshot:** Captures a centered snapshot directly from the remote video stream when connected.
- **Draggable & Minimizable HUD:** Modern, dark-themed floating panel that can be repositioned or collapsed.
- **Local Simulator:** Includes an offline HTML simulator to test UI and mock connections without accessing OmeTV.

---

## Setup Guide

### 1. Create an IPGeolocation account
Visit [https://ipgeolocation.io/](https://ipgeolocation.io/) and create a free account.

### 2. Copy your API key
After signing in, open your dashboard and copy your API key.

### 3. Configure the script
Open `ometv_console_snippet.js` and replace:

```javascript
let apiKey = "";
```

with:

```javascript
let apiKey = "YOUR_API_KEY";
```

### 4. Open OmeTV
Go to [https://ome.tv/](https://ome.tv/) and sign in.

### 5. Open Developer Tools
Press `F12` or `Ctrl + Shift + I`.

### 6. Open the Console
Select the **Console** tab.

If Chrome displays:
> Warning: Don't paste code into the DevTools Console...

type:
```text
allow pasting
```
and press **Enter**.

### 7. Run the script
Paste the entire script into the Console and press **Enter**.

### 8. Start using OmeTV Uncover
Once connected to another user, the floating panel will automatically display the available information.

---

## Disclaimer

This project is created for educational and security testing purposes only. Use responsibly and in accordance with local regulations and terms of service.
