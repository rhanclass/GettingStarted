# GitHubs Commands
### These are commands used to upload and download your files from GitHub online. You should memorize these commands later on
## Cloning your repository
**Note:** You only need to clone the repository the first time you create it and want to move it to your local machine.
- Click the **Clone or download** green button on the right side of the screen.
- Copy the url under the **Clone with HTTPS**
- Go to your terminal and write the following command
```
git clone <past the link you just copied here>
```
- If your computer produces an error, try copying the url under **Clone with SSH** and running the code above again
- Find the repository you just cloned with the **ls** command and **cd** into that directory
*************************************************************************************************
## Uploading your work
- Make sure to save your code in your IDE first
- Go to your terminal and type in 
``` 
git add -A
```
- To check to see what files you changed you can type in 
```
git status
```
- Then write the code
```
git commit -m "a message describing what changes you made"
```
- If it asks you to config your username and email, do that first. Type in
```
git config user.email "email you used to sign up for github here"
```
- Then type 
```
git config user.name "username that you used for github"
```
- After typing both of the configs, write your git commit message again. 
- You have successfully updated your changes if you see a line that described the numbre of files/lines changed 
- Finally, type in
```
git push
```
*************************************************************************************************
## Pulling your work
- If you upload your changes from another machine and want to see those changes locally on the machine you are working on, type the following
``` 
git pull
```
- All of your changes should have been updated.
*************************************************************************************************
