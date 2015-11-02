# Basic Git and Github

## Tips & Tricks

1. If a GIF is going too fast <s>(gotta go fast)</s> for you, **right click** on them and select **"Show Controls"**

*

[](http://i.imgur.com/NXFAUc5.gif)[http://i.imgur.com/](http://i.imgur.com/NXFAUc5.gif)[NXFAUc5.gif](http://i.imgur.com/NXFAUc5.gif)

2. To see the GIF in another tab,** click the link under the GIF**: 

![](http://i.imgur.com/NXFAUc5.gif)

[](http://i.imgur.com/NXFAUc5.gif)http://i.imgur.com/NXFAUc5.gif

3. **Don't** **include** the **square brackets **mentioned** **( [text-here] ) when typing

*   Those are **indicators of areas where you type custom text**

![](http://puu.sh/l4T7s/881c9d2030.png)

*   This would be: git branch **custom-text**

4. After you type a command in the terminal, hit **"enter"** on your **keyboard** to complete the command

## Preparing your workspace for Git

If you already have a pre-existing workspace you can skip this section. 

Git requires at least **one **file in your workspace to be used, the steps below will take you through setting the workspace up.

**1. Login to your Cloud9 homepage - **[](https://c9.io/)**https://c9.io/**

*   Register if you haven't already (We recommend signing up with your Github account - [](https://github.com/))https://github.com/)

**2. Create a workspace! **

*   Press the create a new workspace button

*

[](http://i.imgur.com/hgzOQmk.gifv)http://i.imgur.com/hgzOQmk.gifv

*   Give the workspace a good name that conveys what the workshop is quickly, and concisely

        *   There are no spaces allowed in the name, use **- **for spaces if you need them

*   Add a short description, you'll thank yourself later!
*   Select public for the privacy settings, it'll make it easier for people to help you with your project.
*   If you already have a Github project with files and you want to have it ready when you create the workspace you can add its link in the box provided
*   For the template you may choose either **Custom** or **HTML5**

*

[](http://i.imgur.com/5G1mWxR.gifv)http://i.imgur.com/5G1mWxR.gifv

**3. Get rid of the unnecessary junk**

*   On the left sidebar: Right click on README.md and hello-world.html 

        *   Select "**Delete**" and **Yes** to any warnings

                *   You won't need these for your project

*   Close the opened README.md as well

*

[](http://i.imgur.com/mHWXJy0.gifv)http://i.imgur.com/mHWXJy0.gifv

**4. Create an index.html file**

*   On the left sidebar: Right click and press "**New File**"
*   Name the file **index.html**
*   Double-click and open it

**5. Write your name in the index.html file**

*   If you don't know how, you may use this pre-provided code:

*   <!DOCTYPE html>
*   <html>
*       <head></head>
*       <body>
*           <p>Your name here</p>
*       </body>
*   </html>
*

**6. Save the index.html file**

*   Make sure the active file is the index.html file by either clicking on it on the sidebar or clicking anywhere in the code
*   You may press Ctrl+S (Windows), Command+S (Mac) or go to File --> Save

*

[](http://i.imgur.com/g5NtFRL.gifv)http://i.imgur.com/g5NtFRL.gifv

**7. Celebrate!**

*   Your workspace is now ready to be used with Git!

## What is Git?
<undefined><li>**Git is a version control system - **[](https://git-scm.com/)**https://git-scm.com/**</li></undefined>

*   **Tracks **and **manages **changes to your code

![](http://i.imgur.com/XHZZDyb.png)

<undefined><li>**Example: If We Used Git With Word Documents**</li></undefined>

*   Git treats every version of code as a "**snapshot**" that you can look **back/ revert** to at anytime.

![](http://i.imgur.com/YwqTWJ5.png)

*   Running a command called **git log** in the terminal displays every change you've saved

## Git's Tools

**Repository (short-form: "repo")**

![](http://puu.sh/l4JtG/7671d31249.png)

**Branch**

*   Their own copy of the files is called a **fork **or **"forking a repo"**

*   Must be named without spaces -- **replace a space with a dash (-)**

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_gOQpi30cvG8_p.429802_1445749842921_git-structure.png)
<undefined><li>**Example: Why Branches?**</li></undefined>

_Bob & John are working on one repo and the same files at the same time: _

*   Bob encounters a bug, it will take about an hour to fix

<undefined><li>** Example: Branch Merging**</li></undefined>

*   Bob is working on the main.css file for the tool bar

*   John is also working on the main.css file, but for the header

**Master branch**

<undefined><li>**Diagram of Master branch versus Another Branch**</li></undefined>

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_gOQpi30cvG8_p.429802_1445746706194_git-branches.png)

*   Think of "**master**" as the **tree trunk **and "**feature**" as a literal **branch**

## What is Github? -  https://github.com/

Github is an online **Git** **repository** **hosting** **service**

*   A friendly way to look at and manage **repositories** and **branches with **a GUI (graphical user interface)

        *   Basically prettier than just text on the terminal

*   Has its own tools that makes it easier and faster to collaborate with others (we'll go into that later!)

## Using Git + Github Pages (w/ provided link)

**Github Pages is a free service by Github**

*   Allows you to host a website on their servers ([](https://pages.github.com/))[https://pages.github.com/](https://pages.github.com/))
*   The URL will have to be username.github.io/reponame

**Preparations**

1.  You **need** to have at least one **file** **named "index.html"**

2. You **provided** a** Git link** when you **made the workspace**:

![](http://i.imgur.com/RO1TDm6.png)

*   Nah, not familiar?** Follow the steps in "Using Git + Github Pages (w/o provided link)" in heading below **

<undefined><li>**You can find and click the other steps to the right instead of scrolling:**</li></undefined>

![](http://i.imgur.com/wDVvSX0.png?1)

**1. Open your terminal**

*   Depending on the workspace configuration you set, it might already be opened. 

*   Hit the "+" button in the bottom panel area **<u>OR</u>** on the top-bar click "Window" and "New Terminal"

*

[](http://i.imgur.com/2K3qUcU.gifv)http://i.imgur.com/2K3qUcU.gifv

**2. Type the command: git add [file] OR git add .  **

*

[](http://i.imgur.com/T1dNJwS.gifv)http://i.imgur.com/T1dNJwS.gifv

**3. Type: git commit -m "commit message here"**

*    Commits changes to be pushed to the branch

        *   -m stands for message and in quotations put a message that descriptions what you did

                *   If it is the first commit, simply put** git commit -m "first commit**"

*   Think of committing as packaging something into a package and putting the shipping label on it

*

[](http://i.imgur.com/QTy5NIv.gifv)http://i.imgur.com/QTy5NIv.gifv

**4. Type: git push**

*   Think of pushing as actually shipping the container to the recipient, which in this case is the repo

![](http://i.imgur.com/VBabXtF.png)

[](http://i.imgur.com/VBabXtF.png)http://i.imgur.com/VBabXtF.png

*   The characters for the password not show up in the terminal for security reasons -- just keep typing!

![](http://i.imgur.com/ktNQxpn.png)

*

[](http://i.imgur.com/jNsU2Fo.gifv)[http://i.imgur.com/jNsU2Fo.gifv](http://i.imgur.com/jNsU2Fo.gifv)

**5.  Type: git branch [branch-name]**

*   Creates a **branch**

*

[](http://i.imgur.com/FmTTMK6.gifv)[http://i.imgur.com/FmTTMK6.gifv](http://i.imgur.com/FmTTMK6.gifv)

**6. Type: git push gh-pages**

*   Push your branch, **gh-pages**, online to Github
*   Afterwards your website should be up at yourusername.github.io/reponame
*   It might take about 30 seconds to fully get online

*

[](http://i.imgur.com/GPnRfHp.gifv)[http://i.imgur.com/GPnRfHp.gifv](http://i.imgur.com/GPnRfHp.gifv)

**7. Go online to username.github.io/reponame**

*   **Example: jevinsidhu.github.io/Personal-Website**

**8. Celebrate!**

*   Congrats, now you're a Git (6) God!

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_gOQpi30cvG8_p.429802_1446176730661_31ZNk7R.gif)

## Using Git + Github Pages (w/o provided link)

**1. Open your terminal**

*   Depending on the workspace configuration you set, it might already be opened!

*   Hit the "+" button in the bottom panel area **<u>OR</u>** on the top-bar click "Window" (8th from the right) and "New Terminal"

*

[](http://i.imgur.com/2K3qUcU.gifv)[http://i.imgur.com/2K3qUcU.gifv](http://i.imgur.com/2K3qUcU.gifv)

**2. In the Terminal, Type: git init**

*

[](http://i.imgur.com/oVzcFX0.gifv)http://i.imgur.com/oVzcFX0.gifv

**2. Type: git remote add [remote-name] [link to repo]**

*   Your changes need to connect your local folder to a remote one on Github
*   You need a connection between the two --> Create a **remote**

*   On [Github](https://github.com), click** the green button that says "New Repository" near the middle-right area**

        *   Name your repo (e.g _hello-world_)  and give a short description

                *   No spaces between your name --> replace a space with a dash (-)
        *   Short and to the point description

*   Click the green button that says "Create repository"

*

[](http://i.imgur.com/n9KVMa5.gifv)[http://i.imgur.com/n9KVMa5.gifv](http://i.imgur.com/n9KVMa5.gifv)
<undefined><li>**Example: Remote is a TV Remote Controller**</li></undefined>

*   **Hand** is your **local copy**
*   **TV **is the **remote** **repo on Github**
*   The **remote** is the** controller**

If you want to change the channel, you hit one channel up on the **controller** **(remote) **with your **hand (local)** and it **changes** the channel one upon your **TV (remote repo).**

*   **Example command: **git remote add github [](https://github.com/nguyenbrian/example.git)[https://github.com/nguyenbrian/example.git](https://github.com/nguyenbrian/example.git)

*

[](http://i.imgur.com/ejZbdF9.gifv)http://i.imgur.com/ejZbdF9.gifv

**3. Type: git add [filename.extension] <u>OR</u> git add .  **

*

[](http://i.imgur.com/T1dNJwS.gifv)http://i.imgur.com/T1dNJwS.gifv

** 4. Type: git commit -m "a commit message here"**

*   Think of committing as packaging something and putting the shipping label on the box

*

[](http://i.imgur.com/QTy5NIv.gifv)http://i.imgur.com/QTy5NIv.gifv

**5. Type: git push [remote name] master**

Part two of saving, **"pushing"**

*   Uploading to Github

*   Think of pushing as actually shipping the container to the recipient, which in this case is the repo

*   Your **remote name** is the one you previously **created in step 2**

*   **Example command: git push github master**

![](http://i.imgur.com/ktNQxpn.png)

*   If you enter your username or password wrong, reenter the command, _git push github master_, and try again

*

[](http://i.imgur.com/jNsU2Fo.gifv)http://i.imgur.com/jNsU2Fo.gifv

**6. Type: git branch [branch-name]**

*   Creates a **branch**

*

[](http://i.imgur.com/FmTTMK6.gifv)http://i.imgur.com/FmTTMK6.gifv

**7. Type: git push [remote name] gh-pages**

*   **Example command: git push github gh-pages**

*

[](http://i.imgur.com/GPnRfHp.gifv)http://i.imgur.com/GPnRfHp.gifv

**8. Go online to username.github.io/reponame**

*   **Example: jevinsidhu.github.io/Personal-Website**

**8. Celebrate!**

*   You successfully pushed your site online!

![](http://nbatitlechase.com/blog/wp-content/uploads/2014/05/drake-clapping.gif)

## More Commands
<undefined><li>**Clone: g**it clone [repo-url]</li></undefined>

*   Clone a workable copy of a repo onto your local workspace

![](http://i.imgur.com/CihxQd6.png)

*   You'll find the **[repo-url]** when you click a into a repo and look at the bottom right for this:

![](http://puu.sh/l4SIm/18de8f81dd.png)
<undefined><li>**Merging: git merge [branch-to-merge-changes-from]**</li></undefined>

*   Combine the differences from another branch into the current branch you're working in
*   Better to stay away from this and do a pull request using Github

## Extended Github Knowledge

**Pull Requests**

*   A means to "pull" the changes from one branch into another.

*   Most commonly used to merge feature branches into master branches

*

[](http://i.imgur.com/48Dy2Cp.gifv)http://i.imgur.com/48Dy2Cp.gifv

A good Git Workflow:

![](http://i.imgur.com/3kgvTTL.png)

**Github Terminology**
<undefined><li>**Fork**</li></undefined>

*   Creates an identical repo under your name allowing you to edit its contents

*   Similar to a clone, except instead of merging you would do a pull request to merge your changes to the master repo

![](http://i.imgur.com/aVBgDGi.png)
<undefined><li>**Pull Request**</li></undefined>

*   Request to merge the contents of a branch or fork into a repo

*   Needs to be approved by the administrators of the repo you're trying to merge into

*   **Pulls **the data from your repo into the main repo

<undefined><li>**Issue**</li></undefined>

*   User-submitted bug tracker

*   Allows contributors to discuss the bugs

![](http://i.imgur.com/Awl6kix.png)

![](https://hackpad-attachments.s3.amazonaws.com/hackpad.com_gOQpi30cvG8_p.429802_1445788802453_undefined)
<undefined><li>**Contributor**</li></undefined>

*   Someone that contributes to the default branch through things such as commits, pull requests and submitting issues.

## Follow us on Github!

Brian: [](https://github.com/nguyenbrian)[https://github.com/nguyenbrian](https://github.com/nguyenbrian)

Jevin: [](https://github.com/JevinSidhu)[https://github.com/JevinSidhu](https://github.com/JevinSidhu)

Udit: [](https://github.com/uditdesai)[https://github.com/uditdesai](https://github.com/uditdesai)

Vaibhav: [](https://github.com/vaibhavyadaram)[https://github.com/vaibhavyadaram](https://github.com/vaibhavyadaram)

## Explore!