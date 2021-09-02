<h1> Linux vs Windows: What is the Difference Between Linux and Windows? </h1>

In this page, I will know about Linux OS and see the difference between Linux and Windows. 

* Windows Vs. Linux: File System
* Linux Types of Files
* Windows Vs. Linux: Users
* Windows Vs. Linux: File Name Convention
* Windows Vs. Linux: HOME Directory
* Windows Vs. Linux: Other Directories
* Windows Vs. Linux: Key Differences
  
# Windows Vs. Linux File System

## Window
> When we compare file system in Windows and Linux, in Windows, files are stored in folders on different data drives like ( C: D: E: )

## Linux 
> Linux files are ordered in a tree structure starting with the root directory. This root directory can be considered as the start of the file system, and it further branches out various other subdirectories. The root is denoted with a forward slash '/'. A general tree file system on your UNIX may look like this.

![](https://cdn.guru99.com/images/FolderStructure.png)

# KEY DIFFERENCE

## What programmer can do what programmer can't do in Linux and Windows
>* Linux is an open source operating system so user can change source code as per requirement where as Windows OS is a commercial OS so user doesn't have access to source code. 

## What is the benefit ?
>* Linux is very well secure as it is easy to detect bugs and fix where as Windows has a huge user base, so it becomes a target of hackers to attack windows system. 

## Is there any different in speed? 
>* Comparing Windows file system vs Linux file system, Linux runs faster even with older hardware where as Windows are slower compared to Linux. 

## How OS name the hardware? 
>* Linux peripherals like hard drives, CD-ROMs, printers are considered files whereas Windows, hard drives, CD-ROMs, printers are considered as devices.

## How file stored? 
>* Linux files are ordered in a tree structure starting with the root directory where as in Windows, files are stored in folders on different data drivses like C: D: E:

## Can it store multiple file with same name in same directory?
>* In Linux you can have 2 files with the same name in the same directory while in Windows, you cannot have 2 files with the same name in the same folder.

## Where file save?
>* In Linux you would find the system and program files in different directories, whereas in Windows system and program files are usually saved in C: drive.

</br>

# Types of Files 
In Linux everything is a file. Directories are files, files are files, and devices like Printer, mouse, keyboard etc are files.

Let's look into the File types in more detail.

## General Files
General Files also called as Ordinary files. They can contain image, video, program or simply text. They can be in ASCII or a Binary format. These are the most commonly used files by Linux Users.
## Directory Files
These files are a warehouse for other file types. You can have a directory file within a directory (sub-directory).You can take them as 'Folders' found in Windows operating system.
## Decvice Files: 
In Microsoft Windows, device like printers, CD-ROM, and hard drives are represented as drive letters like G: H:. In Linux, there are represented as files.For example, if the first SATA hard drive had three primary partitions, they would be named and numbered as /dev/sda1, /dev/sda2 and /dev/sda3.

## Windows Vs. Linux: Users
There are 3 types of users in Linux.

1.Regular
2.Administrative(root)
3.Service

## What is Regular User?
A regular user account is created for you when you install Ubuntu on your system. All your files and folders are stored in /home/ which is your home directory. As a regular user, you do not have access to directories of other users.

## What is Root User?
Other than your regular account another user account called root is created at the time of installation. The root account is a superuser who can access restricted files, install software and has administrative privileges. Whenever you want to install software, make changes to system files or perform any administrative task on Linux; you need to log in as a root user. Otherwise, for general tasks like playing music and browsing the internet, you can use your regular account.

## What is Service User?
Linux is widely used as a Server Operating System. Services such as Apache, Squid, email, etc. have their own individual service accounts. Having service accounts increases the security of your computer. Linux can allow or deny access to various resources depending on the service.

<h2>Note:</h2>
You will not see service accounts in Ubuntu Desktop version.
Regular accounts are called standard accounts in Ubuntu Desktop

In the other hand In Window,there are 4 types of user account types:
Administrator
Standard
Child
Guest

## Window VS Linux: File Name Convention 
> Windows, Report and REPORT file are now able to save in same file 
> Linux,  same name in the same directory, provided they use different cases.

## Windows VS Linux: Other Directories 
Windows, System and Program files are usually saved in C: drive.
Linux,the boot files are stored in the /boot directory, and program and software files can be found under /bin, device files in /dev.
![](https://cdn.guru99.com/images/LinuxDirectories.png)

## Windows VS Linux:
|Windows|Linux|
|----------------|----------------|
|Windows uses different data drives like C: D: E to stored files and folders.|Unix/Linux uses a tree like a hierarchical file system.|
|Windows has different drives like C: D: E|There are no drives in Linux|
|Hard drives, CD-ROMs, printers are considered as devices|Peripherals like hard drives, CD-ROMs, printers are also considered files in Linux/Unix|
|There are 4 types of user account types 1) Administrator, 2) Standard, 3) Child, 4) Guest|There are 3 types of user account types 1) Regular, 2) Root and 3) Service Account|
|Administrator user has all administrative privileges of computers.|Root user is the super user and has all administrative privileges.|
|In Windows, you cannot have 2 files with the same name in the same folder|Linux file naming convention is case sensitive. Thus, sample and SAMPLE are 2 different files in Linux/Unix operating system.|
|In windows, My Documents is default home directory.|For every user /home/username directory is created which is called his home directory.|