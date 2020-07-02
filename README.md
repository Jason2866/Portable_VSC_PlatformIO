# Portable VSC/Platformio/Python for Windows

[![GitHub Releases](https://img.shields.io/github/downloads/Jason2866/Portable_VSC_PlatformIO/total?label=downloads&color=%231FA3EC&style=for-the-badge)](https://github.com/Jason2866/Portable_VSC_PlatformIO/releases/latest)

[Download](https://github.com/Jason2866/Portable_VSC_PlatformIO/releases/download/1.3/VSC_PlatformIO_Python.zip) and extract to a folder on your PC or a fast extern drive/USB stick.

[Compile Pack Tasmota](https://github.com/Jason2866/Portable_VSC_PlatformIO/releases/download/1.3/Tasmota_compile_pack.zip) allows to build Tasmota without a Internet connection.

Optional: [Enhanced version with PyQt5](https://github.com/Jason2866/Portable_VSC_PlatformIO/releases/download/1.3/VSC_PlatformIO_Python_PyQt5.zip) included to run Projects with Qt GUI framework.

Built with:
- [Python64-3.7.7](http://dl.bintray.com/platformio/dl-misc/python-portable-windows_amd64-3.7.7.tar.gz)
- [Portable Git](https://github.com/sheabunge/GitPortable/releases/download/v2.21.0-devtest.1/GitPortable_2.21.0_Development_Test_1_online.paf.exe)

## How to do? 
- Just extract the [ZIP](https://github.com/Jason2866/Portable_VSC_PlatformIO/releases/download/1.3/VSC_PlatformIO_Python.zip) to a folder or a USB stick
- Run `VS Code.exe` in folder `VSC` 

## Example Projects:
- [Tasmota](http://Tasmota.com) preinstalled [ready to run](https://github.com/Jason2866/Portable_VSC_PlatformIO/releases/download/1.3/Tasmota_compile_pack.zip). 
  * Extract the [ZIP](https://github.com/Jason2866/Portable_VSC_PlatformIO/releases/download/1.3/Tasmota_compile_pack.zip) to the same destination as [VSC](https://github.com/Jason2866/Portable_VSC_PlatformIO/releases/download/1.3/VSC_PlatformIO_Python.zip) was unzipped
  * Start `VS Code.exe` (in folder `VSC`) and select in menu `File`-> `Open Folder...`
  * Navigate to folder `Tasmota-development` and choose this folder
  * Wait a while until `VSC`is ready...
  * Make your settings as described in [Tasmota Wiki](https://tasmota.github.io/docs/Visual-Studio-Code/)
  * Hit the blue compile Logo `tick` at the bottom of the VSC screen

- [Tasmota Device Manager](https://github.com/jziolkowski/tdm) with PyQt5<br>
  * Download TDM from the linked page with clicking<br>
   ![image](https://user-images.githubusercontent.com/24528715/70787391-d4bdee00-1d8e-11ea-9b53-f6e82f53c995.png)<br>
  * Choose `Download ZIP` Save the file `tdm-master.zip`<br>
  * Extract the `ZIP` to the place you want 
  * Start `VS Code.exe` (in folder `VSC`) and select in VSC menu `File`-> `Open Folder...`
  * Navigate to the folder where you have extracted the `ZIP` and choose this folder
  * Click in VSC on file `tdmgr.py`
  * Click with right! mouse button in Editor window of VSC and click `Run Python File in Terminal`
  * Tasmota Device Manager starts and GUI appears :-)

