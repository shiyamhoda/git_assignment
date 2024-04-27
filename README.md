# Git Assignment - shiyamhoda
a. What is an issue?

Issue in the context of GitHub is a feature that allows users to track bugs, enhancements, or tasks for a project. It serves as a one stop communication tool with project repo. It enables collaboration and discussing among contributers. 
Every Issue typically has a Title, and description. It can also have assignees, labels and milestones. Issues can be assigned to specific teams members, labeled for categorisation, linked to pull requests or other issues for organisation and tracking during project development. 

b. What is a pull request?

When any contributers wants to make changes to a project, they initially make changes to thier own copy of the code called a branch makes the changes in thier own branch and when they want it to be reviewed, tested nad potentially merged into the main branch of the repo they create a pull request. 
Pull requests are an essential part of the collaborative development process, allowing for peer review, discussion, and ensuring that only high-quality code is merged into the main branch of a project.

c. How do I open up a pull request?

To open a pull request on github we first need to fork the repo we want to contribute to and the follow the below steps
1. Fork the repo
2. clone the forked repo. From CLI repo can be cloned using command git clone <repo_URL>
3. create a branch (git branch -c <BRANCH_NAME>)
4. navigate to the branch ( git checkout <BRANCH_NAME> ) make he required changes in the new branch
5. stage the changes ( git add <FILE_NAME>)
6. Commit the changes (git commit origin -m "Change description") 
7. Push the changes (git push origin <BRANCH_NAME>)
8. Open GitHUb, It will detect that a new branch i pushed and will prompt to create a pull request, Click on "Compare and pull request" button
9. Fill out the pull request form
10. create the pull request

The pull request is now open for rewiev and feedback

d. Give me a step by step guide on how to add someone to your repository.

The following steps can be followed to add someone to my repository 
1. Go to the GitHUb page of the repository 
2. Click on the settings tab
3. Click on the Collaborators option on the left sidebar
4. Add Collaborator using the github username 
5. send invitation
6. the invited collaborator need to accept the invite 

e. What is the difference between git and GitHub?

Git : It is a version control managment system which allows developers to track changes, collaborat with other and mange multiple versions of the project. Git operates on developers machine locally. 
GitHub : A web-based platform that hosts git repos and provides additional collaborative tools to developers. It allows users to host thier repos remotly on GitHub servers. Additional features available on GitHUb are issue tracking, Pull Requests, code reviews, sikis etc. 

f. What does git diff do?

The git diff command is used to show the differences between different states of a Git repository. Like between different branches, working directory and staging area, staged and last committed version etc. 

g. What is the main branch?

As the name suggests it is the main or the default branch or the code. It typically represents the most stable and up-to-date version of the project. The main branch often serves as the base from which other branches are created, and it's where integration of new features, bug fixes, and other changes typically occurs.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

Pushing changes directly to the main branch is generally not recommended.The best practice to follow a workflow that incorporates feature branches and pull requests. While pushing changes directly to the main branch is technically possible, following a feature branch-based workflow with pull requests offers several benefits, including improved code quality, collaboration, and release management. 
