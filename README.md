# Linux Server Learning Journey

## Introduction
This repository is dedicated to documenting my journey of learning and exploring Linux, specifically using Ubuntu Server. Each step taken and project undertaken is recorded here to track progress and share knowledge. I have a second laptop that I don't use. I wanted to use it as a Linux Server.

## Progress

## Setting Up the Linux Server Environment

### Choosing and Installing Ubuntu Server
- [x] Researched Linux distributions and decided on Ubuntu Server for its wide use and support.
- [x] Downloaded the Ubuntu Server ISO from the official [Ubuntu Downloads](https://ubuntu.com/download/server) page.
- [x] Created a bootable USB drive using Rufus, which can be downloaded from the [Rufus Official Site](https://rufus.ie/).

### Creating Bootable USB with Rufus
- [x] Used the following settings in Rufus:
  - **Device:** Selected the USB drive
  - **Boot selection:** Chose the Ubuntu Server ISO file
  - **Partition scheme:** GPT for UEFI computers
  - **File system:** FAT32
  - **Cluster size:** Left as default
  - **Persistent partition size:** Set to 0 as it's not needed for installation media

### Preparing the Laptop
- [x] Configured the HP Pavilion laptop to remain operational even when the lid is closed by adjusting the power settings in the Control Panel under "Hardware and Sound" > "Power Options" > "System Settings".
