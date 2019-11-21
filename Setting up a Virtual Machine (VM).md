# So you want to set up a VM?

You should only be here if you are running windows or can't comlete the guide in the README.md of this repo.

## Getting ubuntu
Firstly go [here](https://ubuntu.com/download/desktop) and download the latest version of Ubuntu (an awesome Linux distrbution).

# Download the VM software
Go [here](https://www.virtualbox.org/wiki/Downloads) and download the appropriate version of VirtualBox based on your operating system.

## Getting the virtual machine to already have everything we need installed
Download the `VMsnapshot` folder from this repo.

## Starting your VM
1. Start the VirtualBox software
2. Click new
3. Give your VM a name and then select its TYPE to be Linux and VERSION to be Ubuntu (probably 64-bit, depends on your computer)
4. Click next
5. Select the settings tab for the VM you just created
6. Go to the Storage section
7. Under "Controller: IDE" select where it says "empty". This is where your VM will look for an operating system image (like the ubuntu one that we downloaded) to run.
8. On the right hand side there is a dropdown menu called "Optical Drive". To the right of it there is a disk icon. Click the disk icon and then click "Choose virtual optical disk file". This should open up your file explorer. Select the ubuntu image that we downloaded earlier. It should have a .iso extension.
9. Click OK and close this settings window.
10. Start your VM by pressing the green arrow.
