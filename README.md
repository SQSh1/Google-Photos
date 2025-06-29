# PixelifyPhotos 

Magisk Module - Unlock unlimited Google Photos backup with Pixel-exclusive features.

🔗 GitHub Repository: [https://github.com/SQSh1/PixelifyPhotos](https://github.com/SQSh1/PixelifyPhotos)

🔗 [دانلود آخرین نسخه](https://github.com/SQSh1/PixelifyPhotos/releases/latest/download/PixelifyPhotos.zip)

---

## ✨ Features

- Unlock **unlimited** original-quality Google Photos backup  
- Spoof as Pixel 2016–2019 models  
- Zygisk-based for best compatibility  
- No extra code, only essential files  
- Clean, minimal, and efficient  

---

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

---

## 📦 Installation

1. Make sure you have **Magisk** installed with **Zygisk** enabled.  
2. Download the latest release of **PixelifyPhotos** from the [Releases](https://github.com/SQSh1/PixelifyPhotos/releases) tab.  
3. Flash the module via Magisk:
   - Open Magisk > Modules > Install from storage  
   - Select the `.zip` file  
4. Reboot your device.  
5. Open Google Photos and enjoy **unlimited backup** as a Pixel!

> ✅ Works best with Google Photos preinstalled and signed-in.

---

## 🙏 Credits & Acknowledgements

- Based on community work around **Pixel feature spoofing**  
- Inspired by modules like Pixelify & PixelPropsUtils  
- Thanks to developers and testers in the Android modding community  

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
