# Automated Software Installation Using Python

## Project Overview
The Automated Software Installer is a Python-based automation project designed to simplify the process of downloading and installing software applications and Python libraries. It reduces manual effort by executing installation commands and managing installer files automatically.

## Key Features
- Automates the installation of Python libraries using pip.
- Downloads Windows application installers from specified URLs.
- Supports silent installation of Mozilla Firefox.
- Automatically removes downloaded installer files after installation.
- Implements exception handling to manage installation failures.
- Uses a reusable function to simplify software installation.

## Technologies Used
- **Programming Language:** Python
- **Libraries:** subprocess, urllib.request, os
- **Package Manager:** pip
- **Platform:** Windows

## How It Works
1. Defines a list of software packages.
2. Checks the software package name.
3. Downloads the Firefox installer if Firefox is selected.
4. Executes installation commands using subprocess.
5. Deletes the downloaded installer file after successful installation.
6. Displays installation status messages.

## Future Enhancements
- Develop a graphical user interface using Tkinter.
- Support multiple Windows applications.
- Add installation progress tracking.
- Detect previously installed software.
- Integrate Windows Package Manager (winget).
