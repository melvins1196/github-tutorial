# GitHub Tutorial

_by Melvin Santiago_

---
## Git vs. GitHub  
Git is like version control which keeps snapshots of your code. Github is a storage center for all the work you do in git.  
### **Git**  
* Runs in the command line  
* There is a directory which is like a folder of files  
    * once you initialize git, it becomes a repository
    * This can let you edit files
    * You than must add and commit them to make sure your files stay permanent  
* Local machine
* **Does not require Github**  

### **Github**  
* A cloud where ypu can store your code
* Interacts with repository's and lets you be able to see the changes made between commits
* You can start from scratch or clone someone else's project and start from there
* **Does require Git**




---
## Initial Setup  
 Here are the steps to making your account.  
 ### _Step 1_  
 One time setup to create your github account. You can sign up [here](github.com) to create your github account. You will need your own email and think of a password that you can remember. Then sign up for free.  
 ### _Step 2_  
 Than you make an account at cloud nine to actually code. [Click Here](c9.io)  
 ### _Step 3_  
 **SSH**(secure shell) can be found in both github and cloud 9. This is like a security system similarly to HTTPS but it's more efficient since it doesn't require you to log in every time. Your SSH can be found by going to github and going to the top right profile icon and press settings. Then go to the left sidebar and you should see it. So make sure you have SSH selected and not HTTPS.  
 ###_Step 4_  
 Git config is used to make you user name and email that everybody will reconize you as. You would do this by:  
 1. _git config --global user.name "Name you want"_  
 2. _git config --global user.email your emai_




---
## Repository Setup
There are a few steps to make your first repo. But once you got them down it'll be well worth it.  
###_Step 1_  
mkdir whatever you want to call your first repo.(**mkdir makes your repo**)  
###_Step 2_  
cd reponame (**goes into your repo**). Type in pwd just to make sure you are in your correct repository.  
###_Step 3_  
Type in git init which intializes your repo. Than type git config exactly how explained earlier in step 4 of initial setup.  
**We are not done yet**  
###_Step 4_  
We now want to make a readme file. Type in touch README.md(**in all caps**) to create the readme.  

_We would want to save this readme but theres nothing to send the code to. So we have to create a remote repo. And its really simple to create_

**Go on [Github](github.com) and on the top right there is a plus. Click it and press new repository.You MUST name it the same name as cloud 9. Than create the repository** (_you might be asked to vertify your email. Do it_).  
###_Final Step_  
To save your readme type git add README.md. Than press git commit -m "whatever message you want".  Than press git push. And just like that your repo is created



---
## Workflow & Commands
There are some things you should know to get your code working.  
**Git init**- initializes git  
**Git status**- is used to check up on how your codeis doing.  
**Git add**- adds the contents to your index  
**Git commit**- makes your changes permanent. Typed in is git commit -m "message"  
**Git push**- sends code to remote repo in github  
_Some other useful tips_  
If you init in the wrong directory don't panic. Just type in rm -rf .git and that should do the trick. This completely removes git from the project  





