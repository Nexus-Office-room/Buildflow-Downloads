# Buildflow Desktop downloads

Download the Buildflow desktop app for Windows, macOS, or Linux. This repository contains installer releases; the application source code is maintained separately and is not included here. Earlier releases use the name Nexus Office.

## Download and install

1. Open the [latest release](https://github.com/Nexus-Office-room/Buildflow-Downloads/releases/latest).
2. Under **Assets**, download the ZIP for your computer:

   | Computer | Download |
   | --- | --- |
   | Windows | `Buildflow-Windows.zip` |
   | macOS with Apple silicon | `Buildflow-macOS-Apple-Silicon.zip` |
   | macOS with an Intel processor | `Buildflow-macOS-Intel.zip` |
   | Linux | `Buildflow-Linux.zip` |

3. Extract the ZIP and follow the installation instructions included in the archive. Windows packages include an EXE or MSI installer; macOS packages include a DMG; Linux packages include a Debian package or AppImage.

The release page also provides individual installer files. Check the filename and architecture before downloading one directly. See [all releases](https://github.com/Nexus-Office-room/Buildflow-Downloads/releases) for earlier versions.

## Verify a download

GitHub displays a SHA-256 digest for each release asset. Compare that digest with the SHA-256 hash of your downloaded file. For example:

- **Windows PowerShell:** `Get-FileHash .\Buildflow-Windows.zip -Algorithm SHA256`
- **macOS Terminal:** `shasum -a 256 Buildflow-macOS-Apple-Silicon.zip`
- **Linux terminal:** `sha256sum Buildflow-Linux.zip`

Use the name of the file you actually downloaded. The two hashes should match exactly.

## Support

If you encounter a download or installation problem, [open an issue](https://github.com/Nexus-Office-room/Buildflow-Downloads/issues) and include your operating system, the release version, and the error message. Avoid posting passwords, tokens, or personal information.
