# Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

### NAME:Ajay J
### REG NO:212224110003

## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
## Steps:
1.Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
2.Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
3.Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.
## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
## Steps:
1.Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
2.Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
3.Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
4.Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
6.Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
7.Login to Kali Linux:

Use root credentials.
8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
## Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox 
<img width="1919" height="999" alt="image" src="https://github.com/user-attachments/assets/11938eed-3b40-4d91-9e77-99e1512c3d1e" />


Snapshot 2: Kali Running in Virtual 
<img width="1581" height="955" alt="image" src="https://github.com/user-attachments/assets/4655e61f-285e-4866-a45f-b3ae60cb585c" />




## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
## Linux Commands:
1.ls Command

The ls command is used to display a list of content of a directory.

### Syntax:
```
ls
```
<img width="714" height="70" alt="image" src="https://github.com/user-attachments/assets/5623b68d-69bf-442a-95cc-a63107788fa6" />


2.pwd Command

The pwd command is used to display the location of the current working directory.

### Syntax:
```
pwd
```
<img width="193" height="67" alt="image" src="https://github.com/user-attachments/assets/2f7b5a96-59be-4341-87af-d892234a97c0" />


3.mkdir Command

The mkdir command is used to create a new directory under any directory.

### Syntax:
```
mkdir <directory_name>
```
<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/5455ac54-ae53-4ddb-b859-25b106674600" />


4.rmdir Command

The rmdir command is used to delete a directory.

### Syntax:
```
rmdir <directory_name>
```
<img width="308" height="50" alt="image" src="https://github.com/user-attachments/assets/0a7b6f49-674e-4bfb-a175-9ccefb5d2172" />


5.cd Command 

The cd command is used to change the current directory

### Syntax:
```
cd <directory_name>
```
<img width="223" height="42" alt="image" src="https://github.com/user-attachments/assets/66844a24-dd55-4a4f-8db8-9c34e3e959ac" />


6.cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

### Syntax:
```
cat [options] [file_name]
```
<img width="632" height="73" alt="image" src="https://github.com/user-attachments/assets/8ef818d9-6d5b-4da5-8c56-07c4c2af5761" />


<img width="866" height="71" alt="image" src="https://github.com/user-attachments/assets/9d6fbaad-125c-441b-b148-cea14140e335" />


7.cp Command

The cp command is used to copy a file or directory.

### Syntax:
```
cp [source] [destination]
```
<img width="300" height="52" alt="image" src="https://github.com/user-attachments/assets/e75fb201-22a8-48ad-9075-a806957cdc87" />


<img width="831" height="62" alt="image" src="https://github.com/user-attachments/assets/5ed79a08-672b-4950-b28f-c02990a7be24" />


8.mv Command

The mv command is used to move a file or a directory form one location to another location.

### Syntax:
```
mv [source] [destination]
```
<img width="293" height="52" alt="image" src="https://github.com/user-attachments/assets/3af1d493-5fb1-4f01-92a9-19a3ab6ea3d6" />


<img width="339" height="64" alt="image" src="https://github.com/user-attachments/assets/53917924-e993-4f20-8df1-e425b01905e8" />


9.touch Command

Create empty file.

### Syntax:
```
touch [filename]
```
<img width="185" height="44" alt="image" src="https://github.com/user-attachments/assets/2e2109d8-f568-4f2d-8d2d-9d5df00400c4" />

10.vi Command

Edit file contents using editor.

### Syntax:
```
vi [filename]
```
<img width="192" height="51" alt="image" src="https://github.com/user-attachments/assets/26b30482-bf34-49d2-b257-9db0d74bbbaa" />


## Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
