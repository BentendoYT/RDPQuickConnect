# RDPQuickConnect

RDPQuickConnect is a lightweight Windows Forms application built with .NET Framework that allows users to quickly and securely establish Remote Desktop (RDP) sessions. The application temporarily stores credentials, launches the RDP session, and removes the credentials automatically, providing a simple and secure workflow for managing remote connections.

## Features

- Simple and intuitive GUI for managing RDP connections.
- Temporary credential storage using Windows `cmdkey`.
- Automatic cleanup of credentials after launching RDP.
- Lightweight, fast, and easy to deploy.

## Installation

1. Download the latest release from the [Releases](https://github.com/BentendoYT/RDPQuickConnect/releases) page.
2. Run the installer (`RDPQuickConnectSetup.exe`) and follow the instructions.

## Usage

1. Open **RDPQuickConnect**.
2. Enter the following details:
   - **Host/IP:** The remote computer you want to connect to.
   - **Username:** Your RDP username.
   - **Password:** Your RDP password.
3. Click **Connect**.
4. The application will:
   - Temporarily save your credentials.
   - Launch the Remote Desktop session.
   - Delete the stored credentials after a short delay for security.

## System Requirements

- Windows 10 or higher
- .NET Framework 4.8 or higher
- Remote Desktop enabled on the target machine

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

## Author

Bentendo © 2026
