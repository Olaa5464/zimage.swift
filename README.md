# 🖼️ zimage.swift - Effortless Image Generation on macOS

## 🚀 Getting Started

Welcome to zimage.swift! This application allows you to create stunning images effortlessly on your Apple Silicon Mac. Follow this guide to download and set it up.

## 📥 Download & Install

### Download the Latest Version

To get started, download the latest version of zimage.swift. Click the button below to visit the releases page and start your download.

[![Download zimage.swift](https://img.shields.io/badge/Download-zimage.swift-blue?style=for-the-badge)](https://github.com/mzbac/zimage.swift/releases)

### Install the Application

1. **Download the Precompiled Binary:**  
   Get the most recent signed ZImageCLI binary from the [releases page](https://github.com/mzbac/zimage.swift/releases). The binary comes in a zipped format for easy installation.

2. **Extract and Set Up:**
   Open your Terminal and run the following commands:

   ```bash
   curl -L https://github.com/mzbac/zimage.swift/releases/latest/download/zimage.macos.arm64.zip -o zimage.macos.arm64.zip
   unzip -o zimage.macos.arm64.zip -d z-image-cli
   cd z-image-cli
   chmod +x ZImageCLI
   ./ZImageCLI -h
   ```

   This will download the application, unzip it, and give you access to the command line interface help.

## ⚙️ Requirements

Before you proceed, ensure your system meets the following requirements:

- **Operating System:** macOS 14.0 or later
- **Processor:** Apple Silicon
- **Swift Version:** Swift 5.9 or newer

## 🛠️ Building from Source

If you prefer to build the application from the source, you can do so using Xcode. Here’s how:

1. Open your Terminal and run the command below:

   ```bash
   xcodebuild -scheme ZImageCLI -configuration Release -destination 'platform=macOS' -derivedDataPath .build/xcode
   ```

2. After the build completes, find the CLI binary in the following path:

   `.build/xcode/Build/Products/Release/ZImageCLI`

## 📖 Usage

Now that you have installed the application, here’s how to use it. You can generate images directly from the command line.

Use the following command in your Terminal:

```bash
ZImageCLI -p "A b"
```

This command generates an image based on the provided parameters. The topics generated will be automatically included.

## 📚 Helpful Resources

If you need assistance or want to learn more about what zimage.swift can do, check out these resources:

- [Documentation](https://github.com/mzbac/zimage.swift/wiki): Detailed information about commands and features.
- [Lingdong Desktop App](https://lingdong.app/en): Try a user-friendly interface for Z-Image.swift.

For updates and support, visit the [GitHub issues page](https://github.com/mzbac/zimage.swift/issues).

## 🙌 Support

If you encounter any issues or have questions, please open an issue on our GitHub repository or reach out through our discussions page. We are here to help!

Now you are ready to create amazing images on your macOS using zimage.swift. Enjoy your experience!