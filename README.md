# Metasploitable 3 Direct Installer

A one-click installer for Metasploitable 3 that automatically handles all dependencies including VirtualBox installation.

## Features

- Fully automated installation process
- Downloads and configures VirtualBox if needed
- Installs both Ubuntu and Windows Metasploitable 3 VMs
- Built-in 7-Zip installation for RAR extraction
- Detailed progress logging
- User-friendly GUI

## Requirements

- Windows 10/11 (64-bit recommended)
- 10GB free disk space
- 4GB RAM minimum (8GB recommended)
- Internet connection for downloads
- Administrator privileges
- Virtual Box
- 7-Zip

## Installation

1. Download the latest `Metasploitable3-Installer.exe` from [Here](Metasploitable3.exe)
2. Run the executable as Administrator
3. Follow the on-screen instructions

The installer will:
- Check for/install VirtualBox if needed
- Download the Metasploitable 3 OVA files
- Extract and import the VMs automatically

## Usage

After installation:
1. Launch VirtualBox
2. Start either the "Metasploitable3-Ubuntu" or "Metasploitable3-Windows" VM
3. Use your preferred security tools to test against these vulnerable VMs

## Important Notes

- This installer downloads large files (several GB)
- Some antivirus software may flag the installer (false positive)
- Metasploitable VMs are intentionally vulnerable - don't expose them to untrusted networks

## Troubleshooting

If you encounter issues:
1. Check the log file at `C:\metasploitable3-workspace\installer_log.txt`
2. Ensure you have enough disk space
3. Try running as Administrator
4. Check for error messages in the installer window

## Legal

- Metasploitable is a trademark of Rapid7
- VirtualBox is a trademark of Oracle
- This installer is not affiliated with either company

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.
