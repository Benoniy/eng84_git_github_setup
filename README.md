# GIT and GIT-HUB setup with Git Bash:  

### Step 1 - Install git bash:  
  ***Install git from this [link](https://git-scm.com/downloads), making certain that you download the correct version and***  
  ***install the bash client with it!***  

### Step 2 - Create a git hub account if you have not done so, (skip to 3 if you have):
  ***You can create a github account at this [link](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)***  
  
### Step 3 - Generate an SSH key pair:  
  ***Follow these steps in order to generate your SSH key pair***  
1. Open Git Bash
2. type the following command  
  ```ssh-keygen -t rsa -C "your_email@example.com"```  
3. It will now ask you for a file in which to save this key, leave it empty and press ENTER  
4. It will now ask you to enter a pass phrase, again leave it empty and press ENTER  
5. Finally it will ask you to confirm your pass phrase, for the final time leave it empty and press ENTER  
  
### Step 4 - Find your key:  
1. You should now be in git bash, if you doubt this close the window and open git bash again  
2. You should now navigate to the SSH key pair by using:  
  ```cd .ssh```
3. Once in this folder we can access our SSH key by opening our .pub file, first identify the name of that file using:  
```dir```  
4. Now open the file by using:  
```cat filename.pub```
5. You should now see a very long line of text starting with "ssh-rsa".  
  
### Step 5 - Add the key to Git-Hub:  
1. Use your mouse to select the whole key and then right click and copy it  
2. Go to [Git-Hub](https://github.com/login) in a web browser and log in to your account  
3. Click on your profile picture at the top right of the screen and then click on settings
4. Find "SSH and GPG Keys" and click on it  
5. You should now see an option to add a new SSH key, click on it
6. Paste the key from earlier in the key section and add an appropriate name in the name section  
7. Finally click add SSH key  

### Step 6 - You are done!
