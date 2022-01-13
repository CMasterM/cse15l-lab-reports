**Week 1 Lab Report**
=====================
- The fist step to getting started is downloading Visual Studio Code
- It should be donwloadable [here](https://code.visualstudio.com/download)
- When you download and install, use the wizard and then open the program
- If it worked it should look like this ![image](vsCOde.png)
- The next thing we did was to remotely connect to a server 
- First install OpenSSH using instructions from the link [here](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
- then use the SSH command to remotely access the server
- my command looked like *ssh cs15lwi22arh@ieng6.ucsd.edu*
- type yes the first time you log in and then enter your password when promted
- no text shows up when typing so don't be alarmed, (and make sure not to mess up when you type in your password)
- Once you log on you should see this 
- ![image](justLoggedin.png)
- The server I logged into was linux based so we can run some linux commands as shown ![image](someCOmmands.png)
- In order to use this computer we need to upload files onto it.
- I used the command scp in order to upload a file
- my command looked like *scp WhereAmI.java cs15lwi22ase@ieng6.ucsd.edu:~/
- Here is a screenshot of my uploading a file, logging on and checking for it ![image](uploadedFilek.png)