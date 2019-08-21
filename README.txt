Feature Branch Workflow

Team Names:  Lac-Phong N, Josh B, Michael R, Daylen B

Name of Workflow:  Feature Branch

Description of Basic Git workflow: In a basic git workflow, there are no branches, only the master. In this workflow, a user will pull any changes to their local repository, make their changes, and then just commit and push to the master branch. They must fix any merge conflicts that come up, as they come up. In this workflow everyone is working on the same codebase at the same time. To decrease merge errors, users should fetch before working and pushing to the remote. 

Description of Feature Branch: In the feature branch, production branches are created for individual features. These feature branches once tested can be merged into the master branch.When using this method you must keep in mind that you cannot work on the same thing in two different feature branches. 

Key Differences from basic workflow, and key use cases:
In the Basic Git workflow, there is a single master branch in which people will pull and push changes. In a Feature Branch, each person will create their own branch for the feature they are working on and eventually merge it back into the master branch.
Merge conflicts can be a common problem with Basic Git workflows due to people working/pushing to a branch at the same time. Feature branches solve this by each person creating their own branch. 
In Feature Branch, each branch is dedicated to a specific feature, and usually two people won’t work on the same feature. This allows for rapid development and safety against merge conflict. 

Link to your Git example repository: https://github.com/MichaelRejo1601/git-test


git clone _____URL______   //pulls repository
git pull //Fast Forwards and updates local copy of master
git checkout -b [name_of_your_new_branch]   //Creates new branch
git add //Adds file to staging area
git commit -m //Commits file with a message
git push //Pushes local branch to remote branch
git merge [name_of_your_remote]/master      //Merges the branch to the master branch
git branch -d [name_of_your_new_branch]     //deletes fast branch locally
