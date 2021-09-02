<h1>Linux Command Line Tutorial: Manipulate Terminal with CD Commands</h1>

When we perform creating, moving or deleting files on PC. There are various options for File Management.

To manage your files, we can either use 

1. Terminal (Command Line Interface -CLI)
2. File manager (Graphical User Interface -GUI)

In this tutorial, I will learn-
*Why learn Command Line Interface?
*Launching the CLI on Ubuntu
*Present working Directory (pwd)
*Changing Directories (cd)
*Navigating to home directory (cd ~)
*Moving to root directory (cd /)
*Navigating through multiple directories
*Moving up one directory level (cd ..)
*Relative and Absolute Paths

# Why learn Command Line Interface?
Even though the world is moving to GUI based systems, CLI has its specific uses and is widely used in scripting and server administration. Let's look at it some compelling uses -
>* Comparatively, Commands offer more options & are flexible. Piping and stdin/stdout are immensely powerful are not available in GUI
>* Some configurations in GUI are up to 5 screens deep while in a CLI it's just a single command
>* Moving, renaming 1000's of the file in GUI will be time-consuming (Using Control /Shift to select multiple files), while in CLI, using regular expressions so can do the same task with a single command.
>* CLI load fast and do not consume RAM compared to GUI. In crunch scenarios this matters.

Both GUI and CLI have their specific uses. For example, in GUI, performance monitoring graphs give instant visual feedback on system health, while seeing hundreds of lines of logs in CLI is an eyesore. 

## Simple explain CLI on Ubuntu

There are two way to launch the terminal.
> 1.Go to the Dash and type terminal.
> 2.Press CTRL+Alt+T to launch the Terminal.

### Example:
guru99@VirtualBox:~$ 

1. guru99 name of the user
2. Virtual Box computer name or host name. 
3. : mean separator 
4. ~ only show when user are in the home directory. If chang the directory, the sign ~ will vanish.
5. $ mean regular user, #root user.

## Present Working Directory 
If you want to determine the directory you are presently working on, use the command -
> pwd
pwd command stands for print working directory

## Changing Directories 
If you want to change your current directory use the 'cd' command.
> cd /tmp

## Navigating to home directory 
If you want to navigate to the home directory, then type **cd**.
> cd 
> cd ~

## Root directory
The root of the file system in Linux is denoted by '/'. Silimar to 'c:\' in Windows.
\ in Window , / in Unix or Linux.

Type 'cd /' to move to the root directory.
> cd /
*Note*: Do not forget space between **cd** and **/**.

## Navigating through multiple directories
You can navigate through multiple directories at the same time by specifying its complete path.
Example: If you want to move the /cpu directory under /dev, we do not need to break this operation in two parts.
Instead, we can type '/dev/cpu' to reach the directory directly.
> cd /dev/cpu

## Moving up one directory level
For navigating up one directory level.
> cd..

## Relative and Absolute Paths
A path in computing is the address of a file or folder.

Example:
**Windows**
> c:\documentsandsettings\user\downloads

**Linux**
> /home/user/downloads

1. Absolute Path:
Let’s say you have to browse the images stored in the Pictures directory of the home folder ‘guru99’.The absolute file path of Pictures directory /home/guru99/Pictures. To navigate to this directory, you can use the command.
> cd/home/guru99/Pictures

This is called absolute path as you are specifying the full path to reach the file.

2. Relative Path:
s