# WSL Primer

## Basics
  - [Installation](https://docs.microsoft.com/en-us/windows/wsl/about)
  - Launching WSL
    - From Start menu
    - From Command Prompt or PowerShell
      - ubuntu.exe, debian.exe, wsl.exe, bash.exe
  - Debian/Ubuntu stuff
    - Install `build-essential` meta-package to get things like Make, gcc and basic things related to development
  - Editor
    - Typical text editors like nano and vi should already be available.
    - Otherwise can install [VSCode](https://code.visualstudio.com/) on Windows and launch the `code.exe` from within WSL
  - Accessing Windows files from Linux
    - Your C: drive is mounted under /mnt/c in WSL. You can symlink stuff like `C:\Users\Your User Name` in your WSL home directory
  - Launching Window binaries
    - Launching VSCode, notepad.exe

## Anaconda
  - Install the 64-bit Linux version of [Anaconda](https://www.anaconda.com/download/#linux)
  - Be sure to set your PATH correctly. Follow the instructions from Anaconda
  - Launching jupyter lab
  - Setup [conda environment and other stuff](https://docs.anaconda.com/anaconda/)

## Docker
  - Setup Docker on Windows first
  - Setup Docker commandline


  