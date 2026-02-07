# Deep Work Control

**Deep Work Control** is a clean, focused, and highly customizable theme for [YASB](https://github.com/amnweb/yasb). Designed for productivity, it minimizes clutter by using grouped widgets while keeping essential system information accessible at a glance.

### Why no taskbar?
If you're using a window manager with workspaces or just Windows Desktops then you really don't need a taskbar as all your navigation will be done with your keyboard bindings through your window manager and app launcher (for example Flow Launcher/PowerToys). If you're not using a window manager or workspaces/desktops then feel free to add a taskbar widget, details are described in the [YASB Wiki](https://github.com/amnweb/yasb/wiki).

![Theme Screenshot](https://i.imgur.com/WdgaMto.png)

## Background Transparency
The theme is transparent by default to blend seamlessly with your wallpaper. To change this:
1.  Open `styles.css`.
2.  Locate the `.yasb-bar` class near the top of the file.
3.  **Uncomment** the `background-color` property.
4.  Edit the `var(--crust)` CSS variable to your preferred hex or RGB color.

## Widgets & Configuration

### Grouped Widgets
This theme utilizes the **Grouper** widget to organize information into visual groups. This keeps the bar organized and aesthetically pleasing.
* **Customization:** You can easily add, remove, or modify these groups within your `config.yaml`.
* **Documentation:** [YASB Grouper Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Grouper)

### Workspaces
By default, this theme is configured for **GlazeWM**. However, it is fully compatible with other window managers.
* **GlazeWM:** [Setup Guide](https://github.com/amnweb/yasb/wiki/(Widget)-GlazeWM-Workspaces)
* **Komorebi:** [Setup Guide](https://github.com/amnweb/yasb/wiki/(Widget)-Komorebi-Workspaces)
* **Windows Desktops:** [Setup Guide](https://github.com/amnweb/yasb/wiki/(Widget)-Windows-Desktops)

### Weather Widget
Feel free to remove this widget if not needed. It is included by default to help you plan your day at a glance.
* **Setup:** You must obtain a free API key from [WeatherAPI.com](https://www.weatherapi.com/).
* **Configuration:** You can hardcode your key/location in `config.yaml` or set the following environment variables:
    * `YASB_WEATHER_API_KEY`
    * `YASB_WEATHER_LOCATION`
* **Removal:** If you don't need it, you can remove this widget by deleting the `weather` entry under the `widgets` section in your `config.yaml` and by removing the `weather` from `grouped_widgets_3` in your `config.yaml`. You can remove `weather` related css in the `styles.css` file too.
, follow the [Weather Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Weather) to remove the entry from your config.

### Microphone
* **Microphone:** Included for quick visual confirmation of your mute status. Essential for frequent callers. Feel free to remove this widget if you don't want it, you can remove this widget by deleting the `microphone` entry under the `widgets` section in your `config.yaml` and by removing the `microphone` from `grouped_widgets_3` in your `config.yaml`. You can remove `Microphone` related css in the `styles.css` file too.
* **More inforemation:** If you prefer to read the documentation, follow the [Microphone Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Microphone).

### WiFi
* **Location access:** To get the exact WiFi strength you'll be prompted to give permission for location access to YASB. Feel free to remove this widget if you don't want it, you can remove this widget by deleting the `wifi` entry under the `widgets` section in your `config.yaml` and by removing the `wifi` from `grouped_widgets_3` in your `config.yaml`. You can remove `WiFi` related css in the `styles.css` file too.
* **More inforemation:** If you prefer to read the documentation, follow the [WiFi Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-WiFi).

### Battery
* **Battery:** If your system does not have a battery, you can remove this widget by deleting the `battery` entry under the `widgets` section in your `config.yaml` and by removing the `battery` from `grouped_widgets_1` in your `config.yaml`. You can remove `battery` related css in the `styles.css` file too.
* **More inforemation:** If you prefer to read the documentation, follow the [Battery Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Battery).

### Memory
* **More inforemation:** If you prefer to read the documentation, follow the [Memory Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Memory).

### CPU
* **More inforemation:** If you prefer to read the documentation, follow the [CPU Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-CPU).

### GPU
* **GPU:** Most modern systems have a GPU. If your system does not have a dedicated GPU, you can remove this widget by deleting the `gpu` entry under the `widgets` section in your `config.yaml` and by removing the `gpu` from `grouped_widgets_1` in your `config.yaml`. You can remove `gpu` related css in the `styles.css` file too.
* **More inforemation:** If you prefer to read the documentation, follow the [GPU Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-GPU).

### Systray
* **More inforemation:** If you prefer to read the documentation, follow the [Systray Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Systray).

### Media
* **More inforemation:** If you prefer to read the documentation or customize this widget, follow the [Media Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Media).

### Notification
* **More inforemation:** If you prefer to read the documentation, follow the [Notifications Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Notifications).

### Volume
* **More inforemation:** If you prefer to read the documentation, follow the [Volume Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Volume).

### Clock
* **More inforemation:** If you prefer to read the documentation, follow the [Clock Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Clock).

### Power Menu
* **More inforemation:** If you prefer to read the documentation, follow the [Power Menu Widget Wiki](https://github.com/amnweb/yasb/wiki/(Widget)-Power-Menu).

---

## Recommended Setup

To ensure a seamless experience, I highly recommend enabling **autostart** for both YASB and your chosen Window Manager (GlazeWM/Komorebi) and App Launcher (Flow Launcher). This ensures your workflow environment is ready the moment you log in.
