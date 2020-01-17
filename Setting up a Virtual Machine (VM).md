# So you want to set up a VM?
You should only be here if you are running windows or can't complete the guide in the README.md of this repo. This guide should allow you to get working in an environment that has all of the software we need installed and set up correctly.

Laptop requirements:
- 24GB free memory to store the virtual operating system

## What is a VM?
VM stands for Virtual Machine. VM software allows you to easily and quickly run most operating systems on top of your current operating system. For example you can run an Ubuntu Linux virtual machine from a device that currently runs Windows.

## Download the VM software
### Windows and Linux
Go [here](https://my.vmware.com/en/web/vmware/free#desktop_end_user_computing/vmware_workstation_player/15_0|PLAYER-1551|product_downloads) and download the appropriate version of VMWare Workstation Player based on your operating system.

### Mac
Go [here](https://www.virtualbox.org/) and download the appropriate version of Virtual Box for mac.

## Getting the virtual machine to already have everything we need installed
Download the Ubuntu Linux *image* `ubuntuVM.ova` file from this [link](https://drive.google.com/open?id=1giG9zenxvxhBGcfw2Lkxll7TiORtvKg_). It's pretty fat (7GB).

## Starting your VM
### Windows and Linux
1. Start the VMWare software
2. Click "Open a virtual machine"
3. Browse for the `ubuntuVM.ova` file which you just downloaded using the above link.
4. This should create a virtual machine in the list on the left.
5. Start your VM by selecting in and then pressing the green arrow in the main panel.
### Mac
1. Start the VirtualBox software
2. Click new
3. Click File in the top left corner.
4. Select import applicance. Then browse for the ubuntuVM.ova file which you just installed.
5. This should create a virtual machine in the list on the left.
6. Start your VM by selecting in and then pressing the green arrow in the main panel.

This should open up a window displaying a desktop that you would see if you were running the operating system that is on this virtual machine.
