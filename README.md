Hello, welcome to my empty repo!
==========

a. What is a git hub issue?

Issues are used to track todos, bugs, feature requests, and more. As issues are created, they’ll appear here in a searchable and filterable list

b. What is a Pull request

Pull Request is a method for proposing changes to a codebase in a collaborative way. It allows developers to notify team members that they have completed a feature, bug fix, or other update, and would like those changes to be reviewed and potentially merged into the main branch of the project.

c. Describe the steps to open a pull request?
i. Fork the Repository: If you don’t have write access to the original repository, you’ll need to create a fork. This makes a copy of the repository under your GitHub account.

ii. Clone the Repository:
Clone the repository to your local machine so you can work on it.

iii. Create a New Branch:
Create a new branch where you will make your changes. It’s good practice to name the branch something relevant to the changes you're making.

iv. Make Your Changes
Edit the files in your branch to add your new feature, fix a bug, or make any other changes.
Once your changes are made, save the files.

v. Commit Your Changes
Stage the changes you’ve made by running

vi. Push the Branch to GitHub

vii. Open a Pull Request
Go to the original repository on GitHub (not your fork) where you want to submit your changes.
GitHub usually detects the recent push and shows an option to create a pull request for the branch you just pushed.

viii. Provide a Description
Give your pull request a title.
In the description, explain what changes you made and why. Include any relevant details, such as related issues or context.

ix. Create the Pull Request
Once everything is filled out, click on the "Create pull request" button.

x. Respond to Feedback
The reviewers may request changes or ask questions. You can make additional commits to your branch, and they will automatically update the pull request.

xi. Merge the Pull Request (if applicable)
Once the pull request is approved, it can be merged into the main branch. If you have the necessary permissions, you can do this yourself. 

xii. Close the Pull Request
If for some reason the pull request should not be merged, it can be closed without merging.


d. Describe the steps to add a collaborator to a repository (share write permission)
====
i. Navigate to the Repository

ii. Access the Repository Settings
In the repository, find the "Settings" tab and click on it.

iii.  Open the Collaborators & Teams Section
In the "Settings" menu, scroll down until you find the "Collaborators & teams" option in the left sidebar.
Click on "Collaborators & teams."

iv. Add a Collaborator
Under the "Collaborators" section, click the "Add people" button.
A search bar will appear. Enter the GitHub username, full name, or email address of the person you want to add as a collaborator.
Select the correct user from the search results.

v. Send an Invitation
After selecting the user, click the "Add" button.
An invitation will be sent to the selected user.

vi. Collaborator Accepts the Invitation

vii. Manage Collaborators (Optional)
You can manage or remove collaborators from the same "Collaborators & teams" section by clicking the "Manage access" button next to a collaborator’s name.
You can also change their role, such as promoting them to admin if needed.
==========

e. What is the difference between git and github?

Git is a distributed version control system (VCS) that tracks changes in source code during software development while GitHub allows developers to store their Git repositories online, making it easier to collaborate with others.

f. What does "git diff" do?

The git diff command in Git is used to show the differences between various states of your files or between commits. It helps you see what has changed in your code, either before committing changes, between different commits, or between branches

g. What is "main" branch?

The "main" branch on GitHub is the default and primary branch in a Git repository where the final, production-ready code typically resides. It is the branch where all changes are eventually merged after they have been reviewed and tested in other branches.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

If you’re working on a small, personal project where the main branch is not tied to any CI/CD pipelines or production releases, you might push directly to main but in general, avoid pushing changes directly to the main branch especially if there is a collaborative project work going on. Instead, use a branch and pull request workflow to ensure your main branch remains stable, tested, and ready for production. This approach promotes better collaboration, code quality, and project management.