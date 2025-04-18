# deb-releases

This repository contains pre-built `.deb` packages for easy installation and distribution on Debian-based systems. These packages can be used to quickly set up and run software without the need to manually compile from source.

## Available Packages

- **`txt2ascii866_1.0-1.deb`**: A tool for converting text to ASCII with CP866 encoding. This tool processes input as a sequence of 16-bit little-endian words. Each word contains two characters, with the first stored in the lower byte. Intended for systems or encodings using CP866 character representation.

Feel free to explore the releases and install the packages that suit your needs.

## Installation

To install a package from this repository, follow these steps:

1. **Download the `.deb` package** you want to install.

   Example:
   ```bash
   wget https://github.com/bocharovas/deb-releases/releases/download/v1.0/txt2ascii866_1.0-1.deb

2. **Install the package using dpkg.

   ```bash
   sudo dpkg -i txt2ascii866_1.0-1.deb
