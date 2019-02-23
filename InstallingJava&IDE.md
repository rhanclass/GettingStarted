# How to install Java and IDE on your computer
### Note: This only works for Windows computers (only version 10 tested)
## Step 1: Getting Ubuntu on your computer
- Assuming you have 64-bit Windows (this won't work for 32-bit), head to the Control Panel > Programs > Turn Windows Features On or Off.
- Enable the "Windows Subsystem for Linux" option in the list, and then click the "OK" button.
- Restart your machine. You need to for the feature to work.
- After your computer restarts, open the Microsoft Store from the Start menu. 
- Search "Linux" in the store and click on "Get the Apps" under the "Linux on Windows?" banner. 
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
- The preferred IDE we will be using is ATOM, because it is linked to Github.
- Go to this [website](https://atom.io/) and click download
- After you are done, also pin it to your taskbar. 


To access your C drive from the Linux environment, type in the comand 
```
cd /mnt/c
```
