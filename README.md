# Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## NAME: Thanika Sree B
## REG NO: 212222100055

# Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

# 3.a) Installation and Configuration of Oracle VirtualBox
# Aim:
To install and configure Oracle VM VirtualBox.

# Pre-requisites:
* Machine with Internet access
* Minimum 4 GB RAM
* Sufficient storage space

# Steps:
1.Download Oracle VM VirtualBox:
 * Visit Oracle VirtualBox Official Site
 * Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):
* Launch Installer → Allow Changes → Click Next.
* Choose Installation Options → Click Next.
* Accept Network Interface Warning → Click Yes.
* Click Install.
* Finish Installation and Launch VirtualBox.
  
3.Configure VirtualBox:
* Open VirtualBox.
* Click New → Name VM → Select Type (Linux/Windows) and Version.
* Allocate:
    * Minimum 2 GB RAM
    * Create Virtual Hard Disk (20 GB recommended).
* Start Virtual Machine and provide ISO to install OS.
# Result:
Thus, Oracle VM VirtualBox was installed successfully.

# 3.b) Installation and Configuration of Kali Linux
# Aim:
To install and configure Kali Linux in Oracle VirtualBox.

# Pre-requisites:
* Oracle VM VirtualBox Installed
* 4 GB RAM and 20 GB Storage Minimum
* Kali Linux ISO image
# Steps:
1. Download Kali Linux ISO:
  * Visit Kali Linux Official Site
  * Download 64-bit ISO (Installer version).
  
2. Create a New Virtual Machine:
  * Open VirtualBox → Click New.
  * Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
    
3. Allocate Memory:
  * Minimum 2 GB RAM (recommended 4 GB).
    
4. Create Virtual Hard Disk:
  * Select VDI (VirtualBox Disk Image).
  * Choose Dynamically allocated.
  * Set Disk size to 20 GB or more.
    
5. Configure ISO Image:
  * Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
    
6. Start Installation:
   * Boot Virtual Machine → Choose Graphical Install.
   * Set Language, Region, Keyboard.
   * Configure Network → Set Hostname (e.g., kali).
   * Set root password.
   * Disk Partitioning: Use entire disk → All files in one partition.
   * Install System → Install GRUB Bootloader → Finish Installation.
     
7.Login to Kali Linux:
   * Use root credentials.
     
8.(Optional) Install Guest Additions:
  * Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

# Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox
<img width="1919" height="999" alt="image" src="https://github.com/user-attachments/assets/8fd52095-1a58-4d1e-809e-8c59c8ede58d" />

Snapshot 2: Kali Running in Virtual
<img width="1603" height="974" alt="image" src="https://github.com/user-attachments/assets/3394be22-1de0-4f66-af25-adbeb170d24a" />

# Result:
Thus, Kali Linux guest OS was installed and configured successfully.

# 3.c) Execution of Linux Commands in Kali

# About Linux:
  * Open-source operating system.
  * Kernel manages communication between hardware and software.
   * Commands are case-sensitive.
# Linux Commands:

1. ls Command
   The ls command is used to display a list of content of a directory.
   
## Syntax:
```
ls
```
<img width="714" height="70" alt="image" src="https://github.com/user-attachments/assets/3a288965-c471-48fe-9b8e-36e0a66003ec" />


2.pwd Command
   The pwd command is used to display the location of the current working directory.
   
## Syntax:
```
pwd
```
<img width="193" height="67" alt="image" src="https://github.com/user-attachments/assets/8634f211-eca1-4954-8154-63967329d02e" />


 3.mkdir Command
    The mkdir command is used to create a new directory under any directory. 

## Syntax:
```
mkdir <directory_name>
```
<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/7766e5cc-7365-4f0b-81a2-11f49a812278" />

4. rmdir Command
   The rmdir command is used to delete a directory.

## Syntax:
```
rmdir <directory_name>
```
<img width="308" height="50" alt="image" src="https://github.com/user-attachments/assets/af192fa2-59e3-4be9-9eff-02f71ca1eb91" />

5. cd Command The cd command is used to change the current directory

## Syntax:
```
cd <directory_name>
```

6 . cat Command
      The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

## Syntax:
```
cat [options] [file_name]
```
<img width="632" height="73" alt="image" src="https://github.com/user-attachments/assets/180d0bca-ec77-44d9-b13f-f68f8d3dfedb" />

<img width="866" height="71" alt="image" src="https://github.com/user-attachments/assets/b7251e08-41d8-4b2a-ba1b-1d7097f1d418" />

7 . cp Command
     The cp command is used to copy a file or directory.

## Syntax:
```
cp [source] [destination]
```
<img width="300" height="52" alt="image" src="https://github.com/user-attachments/assets/a3b12ac1-7da1-475e-b70c-836d98469333" />
<img width="831" height="62" alt="image" src="https://github.com/user-attachments/assets/94537dfa-6b92-4223-8a88-e05b451863db" />

8. mv Command
    The mv command is used to move a file or a directory form one location to another location.
   
## Syntax:
```
mv [source] [destination]
```
<img width="293" height="52" alt="image" src="https://github.com/user-attachments/assets/9d6b6782-35bc-4bf7-a9d9-dfde9c99debf" />
<img width="339" height="64" alt="image" src="https://github.com/user-attachments/assets/cda48f44-0aee-43a7-90b0-388f4ae3dd01" />

9.touch Command
    Create empty file.

## Syntax:
```
touch [filename]
```
<img width="185" height="44" alt="image" src="https://github.com/user-attachments/assets/6ad741c1-b678-44b4-8a6e-82d2ecb67348" />

10. vi Command
     Edit file contents using editor.

## Syntax:
```
vi [filename]
```

# Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
