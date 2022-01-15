# How to install Java and IDE on your computer
### Note: This only works for Windows computers (only version 10 tested)
## Step 1: Getting Ubuntu on your computer
- Assuming you have 64-bit Windows (this won't work for 32-bit), head to the Control Panel > Programs > Turn Windows Features On or Off.
- Enable the "Windows Subsystem for Linux" option in the list, and then click the "OK" button.
- Restart your machine. You need to for the feature to work.
- After your computer restarts, open the Microsoft Store from the Start menu. 
- Search "Linux" in the store and click on "Get the Apps" under the "Linux on Windows?" banner. If you don't see the banner, just search for Ubuntu in the store
- Click Ubuntu and press "Get", then "Install". If you need to update your Windows 10 version then do so beforehand.
- Once it has downloaded pin it to your taskbar.
## Step 2: Installing Java
- First when you launch the Linux environment, it will ask you to input a new username and password. Input a username and password you will remember.
- Before you install anything, always remember to run
```
sudo apt-get update
```
- Afterwards, type in the command 
```
sudo apt-get install openjdk-8-jre
```
- Then, type in the command 
```
sudo apt-get install openjdk-8-jdk
```
- Then we are done!
## Step 3: Installing the IDE
- The preferred IDE we will be using is VSCode, because it is easy to learn and use.
- Go to this [website](https://code.visualstudio.com/download) and click download
- After you are done, also pin it to your taskbar. 

## Step 4: Opening Terminal
- To open the terminal once you open VSCode, press ```ctrl + ` ``` at the same time and it should open. On the upper right side of the terminal, you will see an option to switch the terminal type. Make sure your terminal is set to the ```wsl``` shell instead of powershell to use the ubuntu terminal. You could set it to default if you need.
- Follow this [tutorial](https://github.com/rhanclass/GettingStarted/blob/master/TerminalCommands.md) if you want to familiarize yourself with how to nagivate terminal. (Note that this will probably be useful in the future) 
