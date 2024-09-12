# Capture Text Ai

<img src="https://github.com/user-attachments/assets/82f1dd90-5e1b-4092-a3ec-369d0fea680a" alt="Capture Text Ai Logo" width="200">


**Developed by Dubu**

Capture Text Ai is a simple, user-friendly application that allows you to capture an image and extract the text from it using OCR (Optical Character Recognition). It supports both Windows and Linux, with a setup guide for both platforms below.

## Features
- Capture screenshots and extract text from images.
- Easy-to-use interface.
- Cross-platform support (Windows & Linux).

---

## Table of Contents
- [Features](#features)
- [Installation](#installation)
  - [Windows](#windows)
  - [Linux](#linux)
- [Uninstallation](#uninstallation)
  - [Windows](#uninstall-on-windows)
  - [Linux](#uninstall-on-linux)
- [Tesseract Installation](#tesseract-installation)
  - [Windows](#tesseract-on-windows)
  - [Linux](#tesseract-on-linux)
- [License](#license)

---

## Installation

### Windows

1. Download the installer from the [releases page](https://github.com/DulithaBandaranayake/CaptureTextAi/releases/tag/Windows).
2. Run the `CaptureTextAi_Setup.exe` file.
3. Follow the installation instructions.
   - **Note**: Tesseract is already bundled in the setup for Windows.
4. Launch the application from your Start Menu or Desktop.

### Linux

1. Download the `.deb` package for Linux from the [releases page](https://github.com/DulithaBandaranayake/CaptureTextAi/releases/tag/Linux).
2. Open a terminal and run the following command to install:
   ```bash
   sudo dpkg -i capture-text-ai-amd64.deb
   ```
3. If there are any dependency issues, run:
   ```bash
   sudo apt --fix-broken install
   ```

---

## Uninstallation

### Uninstall on Windows

1. Go to "Add or Remove Programs" in your Control Panel.
2. Find **Capture Text Ai** and click **Uninstall**.

### Uninstall on Linux

1. Run the following command in the terminal:
   ```bash
   sudo apt remove capture-text-ai
   ```

---

## Tesseract Installation

Capture Text Ai uses Tesseract for Optical Character Recognition (OCR). Here’s how to install it:

### Tesseract on Windows

- **No need to install**: Tesseract is bundled in the Windows installer.

### Tesseract on Linux

1. Install Tesseract by running the following command:
   ```bash
   sudo apt install tesseract-ocr
   ```

---

## License

Capture Text Ai is provided under the following license:

### License Agreement

Copyright (c) 2024 DuBu. All rights reserved.

1. **License Grant**  
   This license permits you to use, install, and run the Capture Text Ai application for personal and commercial purposes. You may not copy, redistribute, or modify the application in any form.

2. **Restrictions**  
   - You may not sell, lease, rent, or sublicense the application.  
   - You may not reverse engineer, decompile, or disassemble the application.  
   - You may not copy or redistribute the application or its components, except for backup purposes.

3. **Disclaimer**  
   The application is provided "as is" without warranty of any kind, either express or implied. The author is not responsible for any damages or losses arising from the use or inability to use the application.

4. **Termination**  
   This license is effective until terminated. Your rights under this license will terminate automatically without notice if you fail to comply with any term of this license.

5. **Governing Law**  
   This license shall be governed by and construed in accordance with the laws of Sri Lanka.

---

Thank you for using Capture Text Ai! If you encounter any issues, feel free to [open an issue](https://github.com/DulithaBandaranayake/CaptureTextAi/issues).

---
