# Google-Photos
Magisk Module - Unlimited Google Photos Backup 

## 👨‍💻 توسعه‌دهنده

- **𝚂𝚀 𝚂𝚑𝚊𝚋𝚊𝚗𝚒**  
  [GitHub](https://github.com/SQSh1)

# 📸 PixelifyPhotos - Unlimited Google Photos Backup

A simple Magisk/Zygisk module that unlocks **unlimited Google Photos backup** by spoofing your device as a Pixel.  
Works without root access for Google Photos itself — just system-level modifications.

## ✨ Features

- Unlock unlimited storage in **Google Photos**
- Mimics official Pixel devices via system configuration
- Includes up-to-date `sysconfig` XML files for:
  - Pixel 2016, 2017, 2018, 2019, 2020, 2021, 2022, 2023...
- Lightweight module with Zygisk native hook (optional)
- Designed for **Magisk 25.2+** and modern Android versions

## 📁 Module Structure


## 📝 مجوزPixelifyPhotos/
├── module.prop
├── customize.sh
├── zygisk/
│ ├── arm64-v8a.so
│ └── armeabi-v7a.so (optional)
├── system/
│ ├── etc/sysconfig/
│ │ ├── pixel_2017_exclusive.xml
│ │ ├── pixel_2018_exclusive.xml
│ │ └── ...
│ └── product/etc/sysconfig/
│ ├── pixel_2016_exclusive.xml
│ ├── pixel_2017_exclusive.xml
│ └── ...
├── META-INF/com/google/android/
│ ├── update-binary
│ └── updater-script



## 🛠 Installation

1. Download the latest `.zip` from [Releases](https://github.com/SQSh1/PixelifyPhotos/releases)
2. Flash using **Magisk Manager**
3. Reboot and check **Google Photos** > **Backup settings**

## ⚙️ Requirements

- Magisk 25.2+
- Android 8.0+ recommended
- Zygisk enabled (for native hook support)

## 🔗 Repository

GitHub: [`SQSh1/PixelifyPhotos`](https://github.com/SQSh1/PixelifyPhotos)

## 📄 License

Licensed under the [MIT License](./LICENSE)

این پروژه تحت مجوز **MIT** منتشر شده است. برای اطلاعات بیشتر، [LICENSE](LICENSE) را ببینید.

---

> این پروژه به‌هیچ‌عنوان به Google یا Google Photos وابسته یا مرتبط نیست.
