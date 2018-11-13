# SSB_Project_Sensor
Github repository to store code for the dry lab portion of SSB project team's biosensor project

# Github Introduction
Github is a remote database that you can store your work as you progress on projects. The following represents a schematic to illustrate how this works. 

 ______________________&nbsp;&nbsp;&nbsp;_______________________ <br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|       |                      | <br>
| David's Computer     |       |   Jenna's Computer   | <br>
|______________________|       |______________________| <br>
                  |   |          | | <br>
                  |   |          | | <br>
                  |   |          | | <br>
                 ___________________   <br>        
                |                   |  <br>      
                | Github Repository |  <br>        
                |___________________|  <br>

All people with access to the repository can download (represented by up arrows) the content of the repository and upload (represented by down arrows) new files and/or edited existing files. However you need to be careful about uploading files that you have changed, as imagine the situation where David changed the file input.txt and Jenna also changed the file input.txt in a different way. This causes what is known as a MERGE CONFLICT, which is when the Github server cannot tell which file to actually use. Therefore, there is a notion of a branch in the github. Heres a diagram of what branches are.
>
                   Jenna's Branch            Changes only in Jenna's branch
                |------------------------------------------------------> 
master branch   |
________________|_________________________________________________________________
 Common files   |                                                     /|\
                |                                                      |  Push to master
                |------------------------------------------------------|------> 
                    David's Branch           Changes only in David's branch

In this example, there are three branches to look at. In all Github Projects, there is usually a master branch. IMPORTANT: this branch should not be directly commited to. It stores the "FINAL" files that we want to use, so please make sure that everyone who is working on the porject is okay with you commiting to the master branch. 

As you can see, everyone has their own branch, and this is where you can edit the files to your heart's content. This is because no one else will be working on your branch, so there is no possible way for there to be merge conflicts. When you are done working on certain files, you will meet with everyone and if they approve your new files and edits, you can push your changes to the master branch, since your changes are now final. This way, no one has any merge conflicts.

You have a copy of this on your own machine, and there is a copy of this structure in the github. Therefore, when you make changes with your computer, you need to "push" your changes to the github from your local computer. Commands for doing this are below.

Useful commands (all of this needs to be done in ther terminal):

TO MAKE A BRANCH FOR YOURSELF:
run "git checkout -b *NAME OF YOUR BRANCH*"

TO ADD YOUR CHANGES ON YOUR LAPTOP TO THE GITHUB:
run "git add . --all"
run "git commit -m "*A MESSAGE YOU WANT TO ANNOTATE YOUR CHANGES TO*"
run "git push"


# Rules for the Github
# 1. This is the most important and only rule. Please, please, PLEASE do not work on the master branch
