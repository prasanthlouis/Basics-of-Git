# Basics-of-Git
Learn basics of git.

1) git init - Initializes a git repository. This is where you'll have files from a project that you'll be sharing 

with other people.

2) git add - There are files in your directory. By typing git add file-name, you'll be adding the file into a temporary 

location. You can use git add . to add all the files present in the directory. git add '.txt' , will add all the 

text files to the temp location.

3) git status- shows the status of the repo. (Files yet to commit, etc)

4) git commit - Remember the files we added? They're in the staging area. To prepare them to be added to the repo,

type git commit -m "Message". The -m is a message  argument. This way, when you add files to your shared project,

others will have an idea about the updates to the project from your message. Plus, its a good way to keep track

of your files.

5) git remote add origin "website.git" - This is where all your files will be pushed. Eg. github.com/prasanthlouis/basicsofgit.git

6)git push -u origin master - This pushes our branch (master) to the origin (defined above). -u means saving the parameters

so you don't need to type in the remote add origin every time you want to commit.

7)git pull origin master- this is to get the newly updated files from your shared repo. Eg. If someone made changes

to your project, you want to fetch the updates and start working from there.

8)git checkout branchname - to switch between the branches

