# AMD GPU EFI Variable

This repository contains the AMD GPU preset EFI variable for use in in my arch install guid. This variable will disable the AMD GPU on mac and arch.
it is just the [dosdude1](URL) way but without macOS 

**status**: UNTESTED ⚠️

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

This repository provides the necessary EFI variable settings for disableing AMD GPUs. 

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/amdgpu-efivar.git
   cd amd-gpu-preset-efi
   ```
   (make sure that this file have this name 'gpu-power-prefs-fa4ce28d-b62f-4c99-4cc3-6815686e30f9'
2. Copy the file to the efivar file
      ```bash
   cp gpu-power-prefs-fa4ce28d-b62f-4c99-4cc3-6815686e30f9 /sys/firmware/efi/efivar
   ```
3. unzip the file
   just install the unzip pkg and unzip it
   ```bash
   sudo pacman -S unzip
   unzip efivar.zip
   ```
## License



Feel free to customize the sections, especially the installation and usage instructions, based on your specific implementation and any additional details you want to include. also i am not reposible about any damege 
