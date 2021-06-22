How to use Git and Github?


## Install git: [Link with downloads](https://git-scm.com/downloads)


## Creating a new project

1) Create a new folder on computer – you can choose any name, but let’s call it “Git Tutorial”

2) You can use notepad from your computer to create a new file called “Readme.md” – Don’t forget.md in the end and save it in the folder “Git Tutorial”

3) Open the “Git Tutorial” and inside it open the terminal command line using the right mouse button

4) Write on this file “Today, it’s a beautiful day to learn some commands about git and github!” and save it.



## Using git

1) Through the command line inside the folder "Git Tutorial", write `git init` to start the repository

2) Add the file Readme.md write `git add  Readme.md` 

3) Commit this file `git commit -m “first commit”` - it is going to create the first commit!



## Interface Github

At this time, the first commit is already done. However, you probably want to create a repository on Github
If you don’t have an account, sign up!

1) At the repository part, create a new one called “Git Tutorial” – you can choose any name

2) Pass the commit to repository, you need to use `git remote add origin <link_repository>`
example: `git remote add origin https://github.com/leticialuna/GitTutorial.git`

* origin is a name used to call our repository

3) Push the commit to platarfom, you need to use `git push -u origin main`

4) Refresh the page and you will see the repository and the file!



## Changing or adding some file

1) Adding new sentence on the original file “Git Tutorial” – example: “We can do it!”

2) Creating new project file called ’Project.md’ and write whatever you want.

3) Passing this new modification using `git add .` 

* ‘.’ send all changes 

4) After this, use `git commit -m  “First modification”`

5) Pushing the file, `git push origin main`
*without -u



## Branch

Until now, we are doing everything on ‘main’ – main timeline. Now let’s create a new branch!


1) Create a new file called “new-project.md” and write whatever you want inside
2) Use command line `git checkout -b “new-project"`

3)  Use `git add .` and `git commit -m “new project”`

4) Then, pushing the file, `git push origin new-project`

If you want to come back to main project, just write `git checkout main`



## Merge

Now that we have our main project and new project, how to merge both together without problems?

1) Go to main project `git checkout main`

2) Marge the new project using `git merge new-project`

3) Push to platarfom using `git push origin main`

Done! Branch is together with main project



## Clone

In case you want to download someone’s else code or even your own code to a new machine, you can just clone it!

1) Go to some repository and copy the link 

2) Use the terminal command `git clone <link>`



## Pull

Update some repository in our machine, it is just necessary using pull.

1) Just use `git pull`



## Fork

If you want to put some repository in our Github account, you just need to use Fork!

1) Go to someone’s else repository and click on ‘Fork’ button! That’s all!



## Pull request

After you Fork someone’s else project, you can edit it and help in this project – but of course you will not be able to change the main project, so you REQUEST the owner using Pull request.
If you want to do it

1) You need to save the project in your machine and change it

2) `git add .` and `commit -m “new changes”`

3) `git push origin main` – nothing new


If this new modification do not have problem with the main project, you will be able to make pull request. It always a good practice write why you made this change and what did you do. 
After this, just wait for the owner accept or refuse your pull request.



## Comments

There are more functions on Git and Github, but these are the most used. 
In case, just take a look [documentation](https://git-scm.com/doc)


