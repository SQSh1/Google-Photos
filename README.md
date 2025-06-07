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


## 📦 Installation

1. Make sure you have **Magisk** installed with **Zygisk** enabled.
2. Download the latest release of **PixelifyPhotos** from the [Releases](https://github.com/SQSh1/PixelifyPhotos/releases) tab.
3. Flash the module via Magisk:
   - Open Magisk > Modules > Install from storage
   - Select the `.zip` file
4. Reboot your device.
5. Open Google Photos and enjoy **unlimited backup** as a Pixel!

> ✅ Works best with Google Photos preinstalled and signed-in.



## 📄 License

Licensed under the [MIT License](./LICENSE)
