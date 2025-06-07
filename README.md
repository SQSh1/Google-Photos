## Google Photos 

**Magisk/Zygisk Module** — Enable **Unlimited Google Photos Backup** by spoofing your device as a Pixel.

🔗 GitHub: [`SQSh1/PixelifyPhotos`](https://github.com/SQSh1/PixelifyPhotos)


## 👨‍💻 توسعه‌دهنده

- **𝚂𝚀 𝚂𝚑𝚊𝚋𝚊𝚗𝚒**  
  [GitHub](https://github.com/SQSh1)

#  PixelifyPhotos - Unlimited Google Photos Backup

A simple Magisk/Zygisk module that unlocks **unlimited Google Photos backup** by spoofing your device as a Pixel.  
Works without root access for Google Photos itself — just system-level modifications.

## ✨ Features

- Unlock **unlimited** original-quality Google Photos backup
- Spoof as Pixel 2016–2019 models
- Zygisk-based for best compatibility
- No extra code, only essential files
- Clean, minimal, and efficient


## 📁 Module Structure

<pre>
PixelifyPhotos/
├── module.prop
├── customize.sh
├── zygisk/
│   ├── arm64-v8a.so
│   └── armeabi-v7a.so
├── system/
│   ├── etc/
│   │   └── sysconfig/
│   │       ├── pixel_2017_exclusive.xml
│   │       ├── pixel_2018_exclusive.xml
│   │       └── pixel_2019_exclusive.xml
│   └── product/
│       └── etc/
│           └── sysconfig/
│               ├── pixel_2016_exclusive.xml
│               ├── pixel_2017_exclusive.xml
│               └── pixel_2018_exclusive.xml
└── META-INF/
    └── com/
        └── google/
            └── android/
                ├── update-binary
                └── updater-script
</pre>


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

این پروژه
---

> این پروژه به‌هیچ‌عنوان به Google یا Google Photos وابسته یا مرتبط نیست.
