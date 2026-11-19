# BatteryHub (Wireless Device Battery Hub) 🔋🎮

*A lightweight Windows taskbar widget and tray monitor for wireless mice, keyboards, headsets, and gamepads.*

> **Fork / Enhanced Edition by [Sidar Yurdusever](https://github.com/SidarYurdusever)**  
> Added native support for **Fantech Shooter III Wireless Gamepad** (2.4 GHz Dongle & Bluetooth) with real-time numeric percentage readout and custom Fantech brand styling!

---

## 🇹🇷 Türkçe Açıklama & Yenilikler (Turkish Overview)

**BatteryHub**, kablosuz fare, klavye, kulaklık ve oyun kollarının şarj seviyelerini Windows görev çubuğunda (saatin yanında) ve sistem tepsisinde doğrudan gösteren hafif ve açık kaynaklı bir araçtır.

### 🌟 Bu Sürümde Eklenen Özellikler:
* **🎮 Fantech Shooter III Gamepad Desteği:** 
  - Fantech Shooter III (WGP13S / GP13) kablosuz oyun kolu (2.4 GHz USB alıcı ve Bluetooth modları) artık tam olarak destekleniyor.
  - Windows'un kablosuz USB dongle'ları "kablolu" sanarak filtrelemesi engellendi.
* **🔢 Sayısal Yüzdelik Gösterim:**
  - Genel metinler ("Dolu/Full") yerine doğrudan sayısal yüzde (`%100`, `%65`, `%30`, `%10`) gösterimi eklendi.
* **🔴 Fantech Özel Marka Rengi:**
  - Görev çubuğunda Fantech'in resmi canlı kırmızı rengi (`#ED1C24`) ve özel parıltı efekti ile şık bir görünüm sağlandı.
* **🚀 Arka Plan Servisi Gerektirmez:**
  - Ekstra üretici yazılımlarına gerek kalmadan doğrudan donanım arayüzü üzerinden hızlı ve sıfır gecikmeli okuma yapar.

### 📥 Kolay Kurulum & Kullanım:
1. [Releases](https://github.com/SidarYurdusever/Wireless-Device-Battery-Hub/releases/latest) sayfasından `BatteryHub-v1.2.0-Portable.zip` dosyasını indirin.
2. Arşivi istediğiniz bir klasöre çıkartın ve **`BatteryHub.exe`** dosyasını çalıştırın.
3. Görev çubuğunda cihazlarınızın pil durumu otomatik olarak belirecektir.
4. Windows ile otomatik başlaması için simgeye sağ tıklayıp **"Start with Windows"** (Windows ile Başlat) seçeneğini işaretleyebilirsiniz.

---

## 🇬🇧 English Overview & Features

Battery levels of your wireless gaming peripherals right on your Windows taskbar:
`🎧 70%  🖱 85%  🎮 100%`

### ✨ Key Features
- **Extremely Lightweight:** ~770 KB portable single executable using ~2 MB of RAM. Written in pure C++17 / Win32 API.
- **No Heavy Vendor Software Needed:** Talks directly to hardware via HID / XInput.
- **Taskbar & Tray Integration:** Shows customizable icon fonts, numeric levels, brand glow, and low-battery alerts.
- **Broad Device Support:**
  - **Gamepads:** Fantech Shooter III, Xbox Wireless Controllers, DualSense/DualShock, 8BitDo, Beitong, GameSir, Switch Pro, Steam Controller.
  - **Mice & Keyboards:** Logitech (Lightspeed/Bolt/Unifying), Razer, SteelSeries, Corsair, HyperX, ROG, ZOWIE, etc.
  - **Headsets:** SteelSeries Arctis, Razer BlackShark/Barracuda, Astro A50/A20, Corsair Void/Virtuoso, and more.

---

## 🛠️ Building from Source (MinGW-w64)

If you wish to compile the project yourself:

```cmd
git clone https://github.com/SidarYurdusever/Wireless-Device-Battery-Hub.git
cd Wireless-Device-Battery-Hub
build.bat
```

*Requirements:* MinGW-w64 (`g++` with C++17 support and `windres`).

---

## 📜 License & Credits

- Based on the open-source [Wireless-Device-Battery-Monitor](https://github.com/krisgfx9/Wireless-Device-Battery-Monitor) by **krisgfx**.
- Licensed under **GPL-3.0**.
