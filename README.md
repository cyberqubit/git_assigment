# Git Assignment - cyberqubit

a. What is an issue?

Issues are items for communicating with others to collaborate, track work, and give and receive feedback.


b. What is a pull request?

A pull request is a proposal to merge a set of changes from one branch into another. 


c. How do I open up a pull request?

To create a pull request on GitHub.com, first, I navigate to the main page of the repository. From the "Branch" menu, I select the branch containing my commits. Next, I click on "Compare & pull request" above the list of files, displayed in a yellow banner. I choose the base branch I want to merge my changes into from the base branch dropdown menu and select the topic branch with my changes from the compare branch dropdown menu. Then, I provide a title and description for my pull request. Finally, I click "Create Pull Request" to submit my pull request for review, or choose "Create Draft Pull Request" from the drop-down menu if I want to create a draft version for further refinement before submission.


d. Give me a step by step guide on how to add someone to your repository.

Step 1: Ask for the username of the person you're inviting as a collaborator. If they don't have a username yet, they can sign up for GitHub. For more information, see "Creating an account on GitHub."

Step 2: On GitHub.com, navigate to the main page of the repository.

Step 3: Under your repository name, click Settings. If you cannot see the "Settings" tab, select the dropdown menu, then click Settings.

Step 4: In the "Access" section of the sidebar, click Collaborators.

Step 5: Click Add people.

Step 6: In the search field, start typing the name of the person you want to invite, then click a name in the list of matches.

Step 7: Click Add Name to Repository.

Step 8: The user will receive an email inviting them to the repository. Once they accept your invitation, they will have collaborator access to your repository.


e. What is the difference between git and GitHub?

Git is a distributed version control system (VCS) that allows developers to track changes to their code over time. It provides features for managing different versions of files, facilitating collaboration among multiple developers, and enabling the rollback to previous versions if needed. With Git, developers can work on projects offline, commit changes locally, and later synchronize their work with a central repository or other team members' repositories.

GitHub, on the other hand, is a web-based platform built around Git. It serves as a hosting service for Git repositories and adds a layer of collaboration features on top of Git's version control capabilities. GitHub provides a centralized location for storing Git repositories, making it easy for developers to share code, collaborate on projects, and track issues and pull requests. It offers features like pull requests, code reviews, issue tracking, project management tools, and wikis, which enhance the collaborative development process.

In essence, Git is the version control system itself, while GitHub is a service built on top of Git that provides additional features and functionality to facilitate collaboration and project management within a development team.


f. What does git diff do?

It compares changes between the working directory and the staging area or between different commits or branches. This helps developers understand what modifications have been made to files, aiding in code review and tracking changes.


g. What is the main branch?

It is the default branch that typically holds the most stable and current version of your project. It acts as a central point of reference for collaboration and deployments.


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

It's generally recommended to avoid pushing directly to the main branch. Instead, it's best practice to follow a workflow where changes are made on separate branches, reviewed, and then merged into the main branch. This approach helps maintain a clean and stable main branch while allowing for effective collaboration and code review.