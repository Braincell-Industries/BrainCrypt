<div align="center">
    <img src="./assets/icon_64x.png" alt="BrainCrypt" />
    <h1>BrainCrypt</h1>
    <p>Discord message encryption plugin, it gives end-to-end client side encryption for your messages and files with automatic key exchange, works without BetterDiscord</p>
</div>

# (Unfinished Readme)

## ⚠️ Important Note
Please be aware that using any Discord modifications may violate Discord's terms of service and could result in account termination. Use this plugin responsibly and at your own risk.

---

## 💡 Acknowledgements
- [`Statsify`]: Inspirational source for README styling.
- [`SimpleDiscordCrypt`]: The base of this project, BrainCrypt is a modified version of it.
- [`DiscordCrypt`]: The original project upon which SimpleDiscordCrypt is based (Outdated).

## 📋 Feature Highlights
- **End-to-End Encryption:** Encrypt your messages and files for maximum security.

## 🚀 Installation
1. Download the [`Better Discord Installer`], open it as an administrator, and follow the installation instructions.
2. After installing Better Discord, go to your Discord settings, scroll down to the **Better Discord** category, and find the **Plugins** page. Click the blue **Open Plugins Folder** button and move the `BrainCryptLoader.plugin.js` file into this folder.

## 🚀 Usage
- **Opening the Menu:** Right-click on the Lock Icon located at the top of any channel next to its name.
- **Downloading Encrypted Images:** Middle-click on any encrypted image to download it.
- **Toggling Encryption:** Use the Lock Icon on top of any channel next to its name. You will see the text input box outlined in a different color. You can also use `:ENC:` to encrypt a message without toggling encryption.

## 🔄 Multiple Devices / Database Management
If you want to use the plugin on multiple devices, designate one as the main device and export its database. To switch to another installation, export and import your database. After new key exchanges, you'll need to repeat these steps.

## 🔒  Security
- **Key Exchanges:** BrainCrypt uses `ECDH P-521` for secure key exchanges.
- **Messages:** For messages, attachments, etc. BrainCrypt employs `AES256-CBC`, providing robust 256-bit security.

<!-- LINKS -->
[`statsify`]: https://github.com/Statsify/statsify
[`simplediscordcrypt`]: https://gitlab.com/An0/SimpleDiscordCrypt
[`discordcrypt`]: https://gitlab.com/leogx9r/DiscordCrypt
[`better discord installer`]: https://betterdiscord.app