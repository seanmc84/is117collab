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

The gitflow workflow functions in a variety of ways. Specific commands are depicted in order to achieve a certain outcome. We can begin with a repository. A repository is a directory or storage space where projects can live. Items like code files, text files, and image files can be stored here. 

Another function could be cloning something. By cloning a repository, that meeans you are downloading a copy of the source code from the source control.

Much like a clone, a fork does also copy a repository but in a better form. A fork repository is always being monitored or compared to the original repository unlike the cloned. Forking allows you to freely experiment with changes without affecting the original project. Forks are used to either propose changes to someone else's project or to use their project as a starting point for your own ideas.

branch - this is how multiple people can work on a project at the same time without Git glitching. By "branching off" of the main project with their own versions full of changes each partner is able to make. Afterwards, it is time to "merge" that branch back with the "master," the main directory of the project. 

commit - this is the command that gives Git its power. When you commit, you are taking a "snapshot" of your repository at that point in time. It leaves a checkpoint to which you can reevaluate or restore the project to any previous state.

Merging is when a branch is complete, you can merge changes back to the master branch which is visible to all collaborators (git merge). For example, "git merge cats" would take all the changes you made to the "cats" branch and add them to the master.

Checking out allows you to "check out" a repository that you are not currently inside. It is a navigational command that lets you move to the repository you want to check; (git checkout).

An example of a push command is if you are working on a local computer and you want your commits to be visible online on github as well, you "push" changes up to github with this command (git push).

An example of a pull command is if you are working on a local computer and want the most up-to-date version of a repository to work with, you "pull" changes down from github with this command (git pull).

By remote adding, removing, or showing, you are using these commands to help you manage connections to remote repositories. By adding, you are creating new connections to a remote repository. By removing, you are disconnecting the remote from the local repository. By showing, it just displays the URLs of the remote repositories. 

You can also check the status of your repository. You are able to see which files are inside of it, which changes need to be committed, and which rbanch of the repository you are currently working on.

All in all, a master branch is the entire composition, the lead repository. Everything is located or merged into this spot and you are able to access it by using the command "git checkout master."
