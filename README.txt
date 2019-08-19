# Git Workflow Example
Team Names: Yuvraj Khullar, Aarush Aitha, Jeff Cheema, Ranju Krishna

Name of Workflow:  Feature Branch

Description of Basic Git workflow: Basic Git Workflow 
Basic Git Workflow works by starting with a master, or the original starting branch, and multiple developers who have cloned the repository of the original. Using these copies, each individual initialize

Description of Feature Branch workflow: 

Key Differences from basic workflow, and key use cases
All feature development should take place in a dedicated branch instead of the master branch
Makes it possible to leverage pull requests
Composable workflow that can be leveraged by other high-level Git workflows
Guiding framework for managing and creating branches

Link to your Git example repository: https://github.com/aarush3002/Feature_Branch.git


Documentation of git commands used, and annotated sample sequence of commands used in creating your repository:
1. git init
2. git clone https://github.com/aarush3002/Feature_Branch.git
3. git fetch
4. git merge origin/master
5. git branch new_feature
6. git checkout new_feature
7. git add new_file.txt
8. git commit -m “message”
9. git fetch
10. git merge origin/master
