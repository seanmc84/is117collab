# is117collab

cd- This is a command that is used to change directories that you are in. you use it to go from a parent directory to a subdirectory. An example of this is if you were in the C:\ directory and wanted to go to the users directory, you would type "cd users" into the command line. This will change your active directory to the users directory and you can go further by typing the next directory contained inside the users directory.

mkdir- This command creates a new directory. You would use it if you wanted to create a new directory from inside the command line. If you were inside the C:\ directory and wanted to create a new "School" directory, you can type "mkdir School" to create a directory inside the C:\ directory. You can also use "mkdir School" to create a directory inside the C:\ directory. You can also use the "mkdir -p School/Homework". This will create a School directory that will be a parent directory for Homework. Then it will create the Homework directory inside School. 

cp- cp acts a copy paste command that will create an exact copy of a directory and paste it into the destination directory. This can be done with a single file, multiple files and even directories. You would use this if you want to make a back up of a directory before making an edit to the contents of it or to copy them to a removable drive. An example would be to locate a file Homework1 in the Homework directory. Once you locate the file, you can type "cp Homework1 Homework1SeanConroy F:\" which will make a copy of Homework1 and place it in the F:\ directory.

pwd- This command will print the full path of the current directory you are in. You would use this if you wanted to see where the directory you are working on is in your machine. You can use it like so: "pwd Homework1" this will then return "C:/Homework/Homework1". Now you are able to see exactly where the directory you are working on is located.

mv- similar to the cp command, you use this command if you wish to move a directory to another place. Again, you can move a single file, or multiple files and directories. This would come in handy if you were looking to just move a bunch of files into a new directory, and it can also be used to rename files. An example would be: "mv Homework1.doc Homework2" Which would then rename Homework1 to Homework2. You can also use it like "mv Homework1 NewHomework" which moves the Homework1 directory from the Homework directory to a new homework directory called NewHomework.

rm- This command is basically a delete command. It is used to remove files and directories from the system. You would use this if you wanted to clear up some space and get rid of a directory that hasn't been used. You can also use it if you accidentally made a directory that you don't need. An example would be "rm Homework" which would remove the Homework directory after the files have been moved to a new directory. All the files inside this directory will also be removed.

history- history command will show you all of your recent commands that have been entered into the command line. If you do not set a limit it will give you a list of 500 of the most recent used commands since you started the session. You would use this to see what commands you entered that may have caused an issue in your files. You can use it simply by just putting "history" in the command line or limit the list by doing "history 5" to show the last 5 commands entered.

Home directory / ~ - If you use the ~ in combination with cd to go back to your home directory. You would use this if you are deep into a line of directories but wanted to create a new directory in your home directory. You can also use it simply to just return back to your home directory to make it easier to locate a file towards the beginning of a line of directories. You use it in combination with cd so it would be "cd ~" and it will return you right back to the home directory. The home directory would be the same directory that you logged into the system with.

File paths in Linux- File paths are usually lengthy depending on how many different directories you have on your system and where the file is saved in the system. Usually they will show just a few of the directories that come before the directory where the file is saved in a simple file path. Using the history command will show the full file path similar to something like "C:/Homework/IS117/MiniProject/Part1/Part1.txt" This would be the full file path that you would get for the file Part1.txt file.

Using the Tab key to complete file paths- Using the Tab key will automatically fill in the next portion of the file path with an existing path after it. This will help you if you dont remember exactly what directories are in the current directory that you are in. You can use it by starting in the C:/ Directory and typing "cd Hom" and you can click the tab key to finish the word, or you can just tab after typing "cd " and it will fill in the space with the first directory in alphabetical order. It is a much more efficient way of completing commands and getting to your final destination.

Using the up and down arrow for history- Instead of using the history command, you can just use the up and down arrow on your keyboard to scroll through your recent commands. This is helpful when you just want to go back a few commands to reword or reuse the command. You can use it by just making sure you have the command line active and just clicking the up arrow on your keyboard, it will begin to scroll back through all the commands you have used in the session in order that you last used them. This is very helpful for using commands more than once at a time.

Gitflow workflow functions in a variety of ways. Commands are depicted in order to achieve a certain outcome. We can begin with a repository. A repository is a directory or storage space where projects can be appropriately organized. Items like code files, text files, and image files can be stored here.

Cloning - cloning repository means you’re downloading a copy of the source code from source control

Fork – better than a clone but it is also a copy of a repository; fork repository is always being monitored/compared with the original repository unlike the cloned; forking a repository allows you to freely experiment with changes without affecting the original project; forks are used to either propose changes to someone else’s project or to use someone else’s project as a starting point for your own idea

Branch – how multiple people can work on a project at the same time without Git glitching; “branch off” of the main project with their own versions full of changes each partner has made; afterwards, its time to “merge” that branch back with the “master,” the main directory of the project

Commit – the command that gives Git its power; when you commit, you are taking a ‘’snapshot” of your repository at that point in time; leaves a checkpoint to which you can reevaluate or restore the project to any previous state

Merge – when a branch is complete, merge changes back to the master branch which is visible to all collaborators (git merge); git merge cats would take all the changes you made to the “cats” branch and add them to the master

Checkout – git checkout: allows you to “check out” a repository that you are not currently inside; navigational command that lets you move to the repository you want to check

Push – if working on a local computer and you want your commits to be visible online on github as well, you “push” the changes up to github with this command (git push)

Pull – if you’re working on local computer and want the most up-to-date version of repository to work with, you “pull” changes down from github with this command (git pull)

Remote add/remove/show - remote add means adding to your repository; removing files from a repository; showing means displaying the repository

Status – check status of your repository; see which files are inside it, which changes need to be committed, and which branch of the repository you are currently working on

Master branch – in order to look at master branch, you use the command git checkout master

A fork is a copy of a repository that allows you to freely experiment with changes without affecting the original project. A forked repository differs from a clone in that a connection exists between your fork and the original repository itself. In this way, your fork acts as a bridge between the original repository and your personal copy where you can contribute back to the original project using Pull Requests.

When you create a new repository on GitHub, it exists as a remote location where your project is stored. You can clone your repository to create a local copy on your computer so that you can sync between both the local and remote locations of the project. Unlike forking, you won't be able to pull down changes from the original repository you cloned from, and if the project is owned by someone else you won't be able to contribute back to it unless you are specifically invited as a collaborator. 

Cloning is ideal for instances when you need a way to quickly get your own copy of a repository where you may not be contributing to the original project.To clone a repository, head over to the main page of a project and click the Clone or download button to get the the repository's HTTPS or SSH URL. Then, you can perform the clone using the `git clone` command in your command line interface of choice.

Pull requests let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

To create a pull request, you must have changes committed to the new branch. Go to the repository page on GitHub, and click on “Pull Requests” button in the repo header. Pick the branch you wish to have merged using the “Head branch” dropdown. You should leave the rest of the fields as is, unless you are working from a remote branch. In that case, just name sure that the base repo and base branch are set correctly. Enter a title and description for your pull request. Finally, click on the green “Send pull request” button to finish creating the pull request.

In order to use a pull request you can write comments related to a pull request and view all the commits by all contained by a pull request under the commits tab, or see all the file changes from the pull request across all the commits under the file changed tab. You can even leave a comment on particular lines in the code change simply by hovering to the left of a line and clicking on the blue note icon.

In order to merge a pull request you first can use github’s merge pull request button at the bottom of your pull request to merge your changes. This is only available when github can detect that there will be no merge conflicts with the base branch. If all goes well, you just have to add a commit message and click on confirm merge to merge the changes. If the pull request cannot be merged online due to merge conflicts or you wish to test things locally before sending the merge to the repo on github, you can perform the merge locally instead. You can find the instruction to do so by clicking the (i) icon on the merge bar.

Only members with owner privileges for an organization or admin privileges for a repository can add outside collaborators to a repository, unless an organization owner has restricted the ability to invite collaborators.Adding an outside collaborator to a private repository will use one of your organization's paid seats.

If your organization requires members and outside collaborators to use two-factor authentication, they must enable two-factor authentication before they can accept your invitation to collaborate on an organization repository.When you add an outside collaborator to a repository, you'll also need to add them to any forks of the repository you'd like them to access.

These are the steps to add a collaborator to your github repo. Ask for the username of the person you're inviting as a collaborator. If they don't have a username yet, they can sign up for GitHub For more information, see "Signing up for a new GitHub account". On GitHub, navigate to the main page of the repository.Under your repository name, click  Settings.In the left sidebar, click Collaborators.Under "Collaborators", start typing the collaborator's username.Select the collaborator's username from the drop-down menu.Click Add collaborator.The user will receive an email inviting them to the repository. Once they accept your invitation, they will have collaborator access to your repository.
