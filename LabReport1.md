# Lab Report 1
## Installing VS Code
Visit this link and download VS code onto your computer: [VSCode](https://code.visualstudio.com/)

<img width="1149" alt="Screen Shot 2023-01-14 at 10 07 32 AM" src="https://user-images.githubusercontent.com/52465268/212488578-8912019b-ffb0-4f99-bc8c-514274c38dd0.png">

1. It is important to identify the type of processing system of your commputer, so you can download accordingly.
2. Once downloaded, follow all the steps the app ay have in the download process.
3. Once done with the installation of the app, you can proceed to open the app for the upcoming steps.
4. Your computer may already have VSCode on it, so it may not be necessary to download.

---
## Remotely Connecting
First, you need to make sure git is installed iin your computer. If not, be sure to install it.

Then, you need to find your CSE 15L account using UCSD account lookup: [Account Search](https://sdacs.ucsd.edu/~icc/index.php)

<img width="1040" alt="Screen Shot 2023-01-14 at 10 16 32 AM" src="https://user-images.githubusercontent.com/52465268/212488898-b438c96a-870d-411b-be57-e37159580672.png">

Once you type in the appropriate information, you will find your account under "Additional Accounts."

<img width="527" alt="Screen Shot 2023-01-14 at 10 17 18 AM" src="https://user-images.githubusercontent.com/52465268/212488929-4e472a31-2160-451f-ba25-e103b87d6f25.png">

> Important Note: You may be required to change your password and may have to wait up to 15 minutes for it to use in the upcoming steps.

After finding, your acccount open up VSCode and open a new terminal.

<img width="252" alt="Screen Shot 2023-01-14 at 10 21 37 AM" src="https://user-images.githubusercontent.com/52465268/212489451-0cc73779-6ea3-4c4c-91bf-08509c0da924.png">

Once you have opened up the terminal, hover over the "+" symbol and select bash to use git bash.

<img width="1139" alt="Screen Shot 2023-01-14 at 10 22 45 AM" src="https://user-images.githubusercontent.com/52465268/212489672-c4a3bbaf-fa06-439f-8f14-638262fcf122.png">

In the bash terminal, enter the command **ssh cs15lwi23(abc)@ieng6.ucsd.edu** with abc beiing the 3 specific letters given to you for your account.

When you first login, it will provide this mmessage in the image below. Be sure to type "yes."

<img width="598" alt="Screen Shot 2023-01-14 at 10 26 33 AM" src="https://user-images.githubusercontent.com/52465268/212489815-ebbba83a-5cdd-4a41-9315-d0b23683e949.png">

The password may take multiple tries, so make sure to keep trying until it authenticates you.

<img width="563" alt="Screen Shot 2023-01-14 at 10 40 32 AM" src="https://user-images.githubusercontent.com/52465268/212490644-ef8dbc2f-2e33-435c-9320-5acaa4e5a2bd.png">

---
## Trying Some Commands
Once you complete the login process, you can begin to try some commands.
Some essential ccommands that you can choose to try include:
| Command | Description |
| `cd ~` | changes directory |
| `cd` | changes directory |
| `ls -lat` | lists files |
| `ls -a` | lists files |
| `ls <directory>` | lists files of another directory |
| `cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/` | classpath |
| `cat /home/linux/ieng6/cs15lwi23/public/hello.txt` | concatenate |
1. `cd ~` changes directory
2. `cd` changes directory
3. `ls -lat` lists files
4. `ls -a` lists files
5. `ls <directory>` lists files of another directory
6. `cp /home/linux/ieng6/cs15lwi23/public/hello.txt ~/`  classpath
7. `cat /home/linux/ieng6/cs15lwi23/public/hello.txt` concatenate

Be sure to observe how these different commands affect the results or the terminal itself.
Here is an example of me trying some commands.

 <img width="401" alt="Screen Shot 2023-01-14 at 10 41 03 AM" src="https://user-images.githubusercontent.com/52465268/212490669-3d1e18cd-4174-4a51-8b3d-e23f18d1c33b.png">

> To exit the terminal, run the command exit or control+D.
