Team Names: Yuvraj Khullar, Aarush Aitha, Jeff Cheema, Ranju Krishna

Name of Workflow:  Feature Branch

Description of Basic Git workflow: Basic Git Workflow 
Basic Git Workflow works by starting with a master, or the original starting branch, and multiple developers who have cloned the repository of the original. Using these copies, each individual initializes their own local repository, which in turn creates their own working directory. Within these working directories, each developer makes their own changes on their copy of the master, set commits, and push these to the local repository. 

Description of Feature Branch workflow: 
	The feature branch workflow functions by creating a new branch every time a developer starts to work on a new feature. This makes it easier for all the developers to collaborate without disturbing the main code. This workflow functions by having the central repository be the official project history. When a developer makes changes in their branch, they must simply commit their changes, and push the feature branch to the remote. The owner will then approve the changes and push the changes. 

Key Differences from basic workflow, and key use cases
All feature development should take place in a dedicated branch instead of the master branch
Makes it possible to leverage pull requests
Composable workflow that can be leveraged by other high-level Git workflows
Guiding framework for managing and creating branches

Link to your Git example repository: https://github.com/aarush3002/Feature_Branch.git

Diagram or Diagrams of workflow:


Documentation of git commands used, and annotated sample sequence of commands used in creating your repository:
git init
git clone https://github.com/aarush3002/Feature_Branch.git
git fetch
git merge origin/master
git branch new_feature
git checkout new_feature
git add new_file.txt
git commit -m “message”
git fetch
git merge origin/master
git push origin new_feature
