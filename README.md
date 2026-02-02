# setup-drive
Local setup and action files to run from USB for desktop and laptop refurbishing.

# Documentation
See [Google Drive](https://drive.google.com/drive/folders/1d_S3faZrwhpUiTw1B-DxLmTf3okOl1hV?usp=sharing) for up-to-date refurbishing documentation.
Go [here](https://github.com/Through-the-Trees/setup-scripts) to see a more technical breakdown of what each script accomplishes.

# Updating
You must first install git on your machine.

## Windows
### /Windows/setup.cmd
Runs [setup-scripts/windows/setup.ps1](https://github.com/Through-the-Trees/setup-scripts/blob/main/windows/setup.ps1) (hosted in remote Github repository)
### /Windows/serial_number.cmd
Displays the device serial number stored in the firmware
### /autounattend.xml
Intended to be placed in the root of a Windows install drive. Will automatically run the Windows setup script Generated using utility created by [Christoph Schneegans](https://schneegans.de/christoph/) and modified for our purposes.

## Linux (Zorin OS)
### /Linux/setup.sh
Runs [setup-scripts/linux/zorin/setup.sh](https://github.com/Through-the-Trees/setup-scripts/blob/main/linux/zorin/setup.sh) (hosted in remote Github repository)
### /Linux/serial_number.sh
Displays the device serial number stored in the firmware

## MacOS
### /MacOS/setup.command
Runs [setup-scripts/macos/setup.sh](https://github.com/Through-the-Trees/setup-scripts/blob/main/macos/setup.sh) (hosted in remote Github repository)
### /MacOS/cpu_sku.command
Displays the CPU model number; MacOS natively outputs the speed and a partial model number.