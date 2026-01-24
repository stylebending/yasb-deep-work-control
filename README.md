# Deep Work Control

**Deep Work Control** is a clean, focused, and highly customizable theme for [YASB](https://github.com/amnweb/yasb). Designed for productivity, it minimizes clutter by using grouped "pill" widgets while keeping essential system information accessible at a glance.

![Theme Screenshot](https://i.imgur.com/5IS0qY1.png)

---

## 🛠 Features & Configuration

### 🧩 Grouped Widgets
This theme utilizes the **Grouper** widget to organize information into visual "pills." This keeps the bar organized and aesthetically pleasing.
* **Customization:** You can easily add, remove, or modify these groups within your `config.yaml`.
* **Documentation:** [YASB Grouper Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Grouper)

### 🪟 Workspaces
By default, this theme is configured for **GlazeWM**. However, it is fully compatible with other window managers.
* **GlazeWM:** [Setup Guide](https://github.com/amnweb/yasb/wiki/(Widget)-GlazeWM-Workspaces)
* **Komorebi:** [Setup Guide](https://github.com/amnweb/yasb/wiki/(Widget)-Komorebi-Workspaces)
* **Windows Desktops:** [Setup Guide](https://github.com/amnweb/yasb/wiki/(Widget)-Windows-Desktops)

### 🌤 Weather Widget
Included by default to help you plan your day at a glance.
* **Setup:** You must obtain a free API key from [WeatherAPI.com](https://www.weatherapi.com/).
* **Configuration:** You can hardcode your key/location in `config.yaml` or set the following environment variables:
    * `YASB_WEATHER_API_KEY`
    * `YASB_WEATHER_LOCATION`
* **Removal:** If you don't need it, follow the [Weather Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Weather) to remove the entry from your config.

### 🎙 Microphone & 🎮 GPU
* **Microphone:** Included for quick visual confirmation of your mute status—essential for frequent callers.
* **GPU:** Most modern systems benefit from GPU monitoring. If your system does not have a dedicated GPU, you can remove this widget by deleting the `gpu` entry under the `widgets` section in your `config.yaml`.

### 📶 WiFi Widget
The WiFi widget is **excluded** by default for two reasons:
1.  **Privacy:** It requires location access.
2.  **Focus:** In a "Deep Work" environment, constant visual confirmation of a stable connection is often unnecessary noise.
* **How to add it:** If you prefer to have it, follow the [WiFi Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-WiFi).

---

## 🎨 Customization

### Background Transparency
The theme is transparent by default to blend seamlessly with your wallpaper. To change this:
1.  Open `styles.css`.
2.  Locate the `.yasb-bar` class.
3.  **Uncomment** the `background-color` property.
4.  Edit the `--crust` CSS variable to your preferred hex or RGB color.

---

## 🚀 Recommended Setup

To ensure a seamless experience, I highly recommend enabling **autostart** for both YASB and your chosen Window Manager (GlazeWM/Komorebi). This ensures your workflow environment is ready the moment you log in.
