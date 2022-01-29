# Week 2 Lab Report
# Richard Xu 


* Install VS Code through their website and select the right download for mac or windows
* [VS Code link](https://code.visualstudio.com/)
* After downloading, open VS Code in applications and screen should look like

![image](https://user-images.githubusercontent.com/97650817/150315842-922bf44e-21b3-40ea-a097-902d672f5b00.png)

* Remote control access by opening the terminal and typing *ssh* then your email to access
* Enter password. It will not show up on your screen to protect privacy

![image](https://user-images.githubusercontent.com/97650817/150317906-2d81a293-adf2-4ffc-a1f6-d870c464930d.png)

* You can enter commands that will run on the computer in the CSE Basement

![image](https://user-images.githubusercontent.com/97650817/150318311-06c6c307-6e8c-488c-8512-0c8524c7c8d9.png)

* Transfer files using scp while in the directory of the file you are trying to transfer

![image](https://user-images.githubusercontent.com/97650817/150320158-ca354984-f5d2-4156-ae27-0ffcd8a2de55.png)

* Log into ucsd server again and using the ls command you will be able to see your transferred file

![image](https://user-images.githubusercontent.com/97650817/150320346-6775d750-5ca2-4a69-9161-51b4433b1367.png)

* To create a key enter the ssh-keygen command while on your local computer
* Then enter /Users/"your name"/.ssh/id_rsa and press enter twice to create no password

![image](https://user-images.githubusercontent.com/97650817/150322158-a7cb0915-e5c0-4d9a-8dc0-ebc2b1834e5a.png)

* log back onto the server and enter mkdir .ssh then log out and enter scp /Users/"yourname"/.ssh/id_rsa.pub cs15lwi22@ieng6.ucsd.edu:~/.ssh/authorized_keys

![image](https://user-images.githubusercontent.com/97650817/150322904-f90d878a-5733-478e-8639-cb465b4c4449.png)

* Use ; to run multiple commands and " to include it after logging in all in one line

![image](https://user-images.githubusercontent.com/97650817/150325947-a919a625-ebe1-476a-98f8-96147e4ded59.png)



