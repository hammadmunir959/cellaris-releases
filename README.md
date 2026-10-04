# 📦 Cellaris Official Releases

Welcome to the official distribution repository for **Cellaris** — the smart, offline-first pharmacy management system powered by **The Guard SDK**.

---

## 📥 Download & Installation

### 🐧 Linux (Snap & Portable)

#### Option 1: Install via Snap Store (Recommended)
You can install Cellaris directly from Canonical Snapcraft on any Linux distribution (Ubuntu, Debian, Fedora, Arch, etc.):

```bash
# Install Cellaris via Snap
sudo snap install cellaris

# Or install from candidate / edge channels:
sudo snap install cellaris --edge
```

#### Option 2: Standalone Portable Bundle (`.tar.gz`)
If you prefer running without Snap:
1. Download [**`Cellaris-Linux.tar.gz`**](https://github.com/hammadmunir959/cellaris-releases/releases/latest/download/Cellaris-Linux.tar.gz) from the latest release.
2. Extract and launch:
   ```bash
   tar -xvf Cellaris-Linux.tar.gz
   cd Cellaris-Linux/
   ./cellaris
   ```

---

### 🪟 Windows Setup Installer (`.exe`)

1. Download [**`Cellaris-Setup.exe`**](https://github.com/hammadmunir959/cellaris-releases/releases/latest/download/Cellaris-Setup.exe).
2. Double-click the installer and follow the setup wizard.
3. A desktop shortcut and Start Menu entry will be automatically created.

---

### 📱 Android (`.apk`)

1. Download [**`Cellaris-Android.apk`**](https://github.com/hammadmunir959/cellaris-releases/releases/latest/download/Cellaris-Android.apk).
2. Open the APK on your Android device to install.

---

## 🚀 Quick Download Matrix

| Platform | Format | Direct Download | Installation Method |
| :--- | :--- | :--- | :--- |
| 🐧 **Linux** | **Snap** | [Snapcraft Store](https://snapcraft.io/cellaris) | `sudo snap install cellaris` |
| 🐧 **Linux** | **Tarball** | [Cellaris-Linux.tar.gz](https://github.com/hammadmunir959/cellaris-releases/releases/latest/download/Cellaris-Linux.tar.gz) | Extract & Run `./cellaris` |
| 🪟 **Windows** | **Setup Executable** | [Cellaris-Setup.exe](https://github.com/hammadmunir959/cellaris-releases/releases/latest/download/Cellaris-Setup.exe) | 1-Click Setup Wizard |
| 📱 **Android** | **APK** | [Cellaris-Android.apk](https://github.com/hammadmunir959/cellaris-releases/releases/latest/download/Cellaris-Android.apk) | Direct APK Sideload |

---

## 🔒 Security & Verification
* All desktop packages are generated through automated GitHub Actions CI/CD.
* Binaries are linked with verified metadata and SHA-256 integrity validation.
