# Virtualization
## AIM:
To install Oracle VM VirtualBox, a free and open-source hosted hypervisor, on a computer system,enabling the creation and management of virtual machines for running multiple operating systems on a single host machine
## EQUIPMENTS REQUIRED:
●Hardware: PCs
●Software: Oracle VM ware  , CENT OS 
●A system with Oracle VM VirtualBox installed.  At least 4 GB RAM and 20 GB free disk space.
●  Kali Linux ISO image, which can be downloaded from the official website.

## Procedure:
Step 1: Download VirtualBox

 Go to the VirtualBox official website: VirtualBox Downloads  Choose the appropriate version for your operating system:
 
 Windows hosts (for Windows users)
 
 macOS hosts (for Mac users)
 
 Linux distributions (for Linux users)
 
Step 2: Install VirtualBox (Windows/macOS)

For Windows:

1.Open the downloaded installer ( VirtualBox-x.x.x-xxxx-Win.exe ).

2.Follow the setup wizard:  Click Next.

 Select the installation location (default is recommended).
 
  Choose the components you want to install and click Next.
  
 The installer may show a warning about network interfaces; allow it to proceed by clicking Yes.
 
3.Click Install and allow the process to complete.

Step 3: Verify the Installation

1.Launch VirtualBox from the desktop or start menu.

2.The VirtualBox Manager should open, showing options to create and manage virtual machines.

Step-by-Step Installation Guide:

Step 1: Download Kali Linux ISO

1.Go to the Kali Linux download page.

2.Download the Kali Linux ISO file.

 Choose between 32-bit or 64-bit depending on your system (most systems are 64-bit).  Download the Installer version for a full installation.
 
Step 2: Open Oracle VM VirtualBox

1.Launch VirtualBox on your computer.

<img width="1920" height="1080" alt="Screenshot 2025-08-24 173912" src="https://github.com/user-attachments/assets/de65a5b1-255b-4d41-a7b2-a37b8eb7ca4e" />

Step 3: Create a New Virtual Machine

1.In VirtualBox, click on the New button to create a new virtual machine.

2.Name and Type Settings:

 Name: Give a name like "Kali Linux".
 
 Type: Select Linux.
 
 Version: Select Debian (64-bit) or Debian (32-bit) depending on the ISO version you downloaded.
 
3.Click Next to proceed.

Step 4: Allocate Memory (RAM)

1.Choose how much RAM to allocate to your virtual machine.

  Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible.
  
2.Click Next.

Step 5: Create a Virtual Hard Disk

1.Select Create a virtual hard disk now.

2.Click Create.

Step 6: Select Hard Disk File Type

1.Choose VDI (VirtualBox Disk Image).

2.Click Next.

Step 7: Storage on Physical Hard Disk

1.Select Dynamically allocated (so the disk will grow as needed).

2.Click Next.

Step 8: Allocate Storage Space

1.Set the hard disk size. Kali Linux requires at least 20 GB of storage.

  You can increase this if you plan to install many additional tools later.
  
2.Click Create.

Step 9: Configure Kali Linux ISO

1.Select the VM from the list in VirtualBox and click Settings.

2.Navigate to Storage from the side menu.

3.Under Controller: IDE, click the Empty CD icon.

4.On the right, click the CD icon next to Optical Drive and choose Choose a disk file....

5.Locate and select the Kali Linux ISO you downloaded.

6.Click OK.

Step 10: Start the Virtual Machine

1.In VirtualBox, click Start to boot up your Kali Linux virtual machine.

