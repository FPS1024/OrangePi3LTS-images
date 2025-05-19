# OrangePi 3 LTS Images

## Project Overview
This project aims to share some unofficial available images for the OrangePi 3 LTS. These images have been tested and are suitable for the OrangePi 3 LTS development board, helping users quickly deploy and use the board.

## Features
- Provides multiple operating system images, including Kali Linux and Raspberry Pi OS.
- Easy to download and use.
- Continuously updated to meet various user needs.

## Releases
### Latest Versions
- **vx.1**:will update the Kali Linux image, suitable for security testing and development.
- **vx.2**:will update the Raspberry Pi OS image, suitable for general development and learning.

### Other Versions
- For more release information, please visit the [Releases Page](https://github.com/FPS1024/OrangePi3LTS-images/releases).

## File Structure
```
LICENSE
README.md
dts/
    sun50i-h6-orangepi-3-lts.dtb
    sun50i-h6-orangepi-3-lts.dts
u-boot/
    u-boot-sunxi-with-spl.bin
```
- `dts/`: Contains device tree files.
- `u-boot/`: Contains the U-Boot bootloader.

## Usage
1. Download the required image file.
2. Use a tool (e.g., `Etcher`) to burn the image to an SD card or eMMC.
3. Insert the SD card into the OrangePi 3 LTS development board and boot it up.

## License
This project is licensed under the [Unlicense](./LICENSE). For details, please see the LICENSE file.

## Contribution
Feel free to submit Issues or Pull Requests to improve this project.

## Contact
If you have any questions, please contact us via GitHub Issues.