[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18434702&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
Fundamental Concepts of Version Control
Version control is a system that tracks changes to files over time, allowing developers to:
✅ Revert to previous versions if mistakes occur.
✅ Collaborate efficiently by merging code from multiple contributors.
✅ Maintain a history of changes for auditing and debugging.

There are two main types of version control:

- Centralized Version Control (CVCS) – Uses a single central repository (e.g., SVN, Perforce).
- Distributed Version Control (DVCS) – Each user has a complete copy of the repository (e.g., Git, Mercurial).

Why GitHub is a Popular Tool for Version Control
GitHub is a cloud-based Git repository hosting service that enhances collaboration and project management.

🔹 Key Features of GitHub:
✅ Remote Repository Hosting – Stores Git repositories online, making code accessible.
✅ Branching & Merging – Allows multiple developers to work on different features without conflicts.
✅ Pull Requests & Code Reviews – Facilitates peer code review before merging changes.
✅ CI/CD Integration – Automates testing and deployment pipelines.
✅ Issue Tracking & Documentation – Helps in managing project tasks and documenting code.

💡 Example: A team developing a data analytics dashboard can use GitHub to track code changes, fix bugs, and merge contributions smoothly.

How Version Control Helps Maintain Project Integrity
🔹 1. Prevents Data Loss – Changes are stored in a history log, ensuring that no code is permanently lost.
🔹 2. Enables Collaboration – Multiple developers can work on different parts of a project simultaneously.
🔹 3. Facilitates Debugging – Version history helps track who made changes and why, making error tracing easier.
🔹 4. Supports Parallel Development – Feature branches allow developers to experiment without affecting the main codebase.
🔹 5. Enhances Security & Accountability – Access control ensures only authorized users modify the code.


## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?

Process of Setting Up a New Repository on GitHub
Setting up a new repository on GitHub is essential for managing and tracking your code efficiently. Below are the key steps and important decisions to consider.

🔹 Step 1: Sign in to GitHub
Go to GitHub and log in to your account.
If you don’t have an account, sign up first.
🔹 Step 2: Create a New Repository
1️⃣ Click the “+” icon at the top-right and select “New repository”.
2️⃣ Enter a repository name (e.g., my-data-science-project).
3️⃣ (Optional) Add a description to explain the purpose of the repository.

🔹 Step 3: Choose Repository Visibility
Public: Anyone can view the repository. (Best for open-source projects).
Private: Only you and collaborators can access it. (Best for confidential projects).
Decision: If the project contains sensitive information or is in early development, choose Private.

🔹 Step 4: Initialize the Repository (Optional)
You can initialize the repository with:
✅ A README.md file – Provides project details.
✅ A .gitignore file – Specifies which files Git should ignore (e.g., __pycache__/, .env).
✅ A license – Defines usage permissions (e.g., MIT, GPL).
Decision: Including a README is highly recommended for documentation.

🔹 Step 5: Create the Repository
Click “Create repository” to finalize the setup.

🔹 Step 6: Clone the Repository to Your Local Machine
1️⃣ Copy the repository URL.
2️⃣ Open a terminal and run:

bash
Copy
Edit
git clone https://github.com/your-username/my-data-science-project.git
3️⃣ Navigate into the repository:

bash
Copy
Edit
cd my-data-science-project
Decision: If working with a team, consider SSH keys for authentication instead of HTTPS.

🔹 Step 7: Start Adding Code & Push to GitHub
1️⃣ Create or modify files in the repository.
2️⃣ Stage and commit changes:

bash
Copy
Edit
git add .
git commit -m "Initial commit"
3️⃣ Push changes to GitHub:

bash
Copy
Edit
git push origin main
Key Decisions to Make
✅ Public vs. Private Repository – Open-source or confidential?
✅ Initialize with README & .gitignore? – Helps with documentation and ignoring unnecessary files.
✅ Choose a License – Defines how others can use your code.
✅ Clone using HTTPS or SSH? – SSH is more secure for frequent contributions.

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?

Importance of the README File in a GitHub Repository
A README file is a crucial part of any GitHub repository as it serves as the project’s main documentation. It helps users, contributors, and collaborators understand the project’s purpose, setup, and usage.

🔹 Why is a README Important?
✅ Provides a Clear Overview – Explains what the project does and its objectives.
✅ Enhances Collaboration – Helps contributors understand how to participate.
✅ Improves Project Accessibility – Serves as a guide for new users and developers.
✅ Encourages Adoption – A well-documented project attracts more users and contributors.

What Should Be Included in a Well-Written README?
A great README should be structured, concise, and informative. Below are the key sections:

1️⃣ Project Title & Description
📌 Clearly state what the project is about.
✅ Example:

markdown
Copy
Edit
# Data Science Dashboard
A Python-based interactive dashboard for visualizing and analyzing real-time data.
2️⃣ Installation & Setup
📌 Explain how to install and set up the project locally.
✅ Example:

markdown
Copy
Edit
## Installation
1. Clone the repository:
git clone https://github.com/your-username/data-science-dashboard.git

css
Copy
Edit
2. Navigate to the project directory:
cd data-science-dashboard

markdown
Copy
Edit
3. Install dependencies:
pip install -r requirements.txt

markdown
Copy
Edit
4. Run the project:
python app.py

Copy
Edit
3️⃣ Usage Instructions
📌 Describe how to use the project, with examples if possible.
✅ Example:

markdown
Copy
Edit
## Usage
- Open `http://localhost:5000` in your browser.
- Upload a CSV file for data visualization.
- Choose a graph type and analyze insights.
4️⃣ Contributing Guidelines
📌 Provide guidelines for contributing to the project.
✅ Example:

markdown
Copy
Edit
## Contributing
We welcome contributions! Follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m "Added new feature"`).
4. Push to GitHub (`git push origin feature-branch`).
5. Submit a pull request.
5️⃣ License
📌 Specify the project’s license for legal clarity.
✅ Example:

markdown
Copy
Edit
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
How a README Contributes to Effective Collaboration
✅ Improves onboarding for new contributors – Saves time by providing clear setup instructions.
✅ Standardizes contributions – Ensures consistency in how features and fixes are added.
✅ Enhances project visibility – A detailed README makes a project more appealing to users.
✅ Reduces confusion – Developers can easily refer to the README instead of asking repeated questions.


## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?

Comparison of Public vs. Private Repositories on GitHub
GitHub allows users to create public and private repositories, each serving different purposes based on project requirements.

Feature	                             Public Repository                                                          Private Repository 🔒
Visibility	                         Accessible to anyone on GitHub.	                                          Only accessible to the owner and authorized collaborators.
Collaboration	                       Anyone can fork, contribute, or view the code.	                            Only invited team members can contribute.
Security & Privacy	                 Code is fully open-source and visible to all.	                            Code is protected, preventing unauthorized access.
Best for	                           Open-source projects, portfolio work, and community-driven development.	  Confidential, proprietary, or commercial projects.
Version Control	                     Maintains full version history accessible to all.	                        Maintains version history but restricts access.
GitHub Features	                     Supports issues, pull requests, and discussions.	                  Supports issues, pull requests, and discussions but limits external contributions.
Forking & Cloning	                   Anyone can fork and modify the project.	                                  Only authorized users can fork (in some GitHub plans).
Cost	                               Free for all users.	                                             Free for personal use; paid plans may be required for teams with advanced features.


Advantages & Disadvantages of Each
Public Repository ✅
✅ Advantages:
✔ Encourages open-source contributions and collaboration.
✔ Increases project visibility (great for portfolio projects).
✔ Allows community feedback and innovation.
✔ Free for all users.

❌ Disadvantages:
✘ No privacy – Anyone can view, copy, or misuse the code.
✘ Security risks – Exposes potential vulnerabilities.
✘ Difficult to monetize since the code is open.

💡 Example Use Case: Open-source projects like TensorFlow or Linux Kernel where public contributions improve development.

Private Repository 🔒
✅ Advantages:
✔ Protects intellectual property and sensitive data.
✔ Allows controlled access (only invited members can collaborate).
✔ Ideal for business, academic, or proprietary projects.
✔ Prevents unwanted forks or exposure.

❌ Disadvantages:
✘ Limited collaboration – External contributors need permissions.
✘ Paid plans may be required for advanced team features.
✘ Less visibility – Projects won't appear in public search results.

💡 Example Use Case: A startup’s software development or a company’s internal tool where security and control are crucial.

Which One Should You Choose?
🔹 Choose a Public Repository if:
✅ You are working on an open-source project.
✅ You want to showcase your work (e.g., portfolio projects).
✅ You need external contributions and community feedback.

🔹 Choose a Private Repository if:
✅ Your project contains confidential or proprietary code.
✅ You are working on a team project with restricted access.
✅ You need to comply with security policies (e.g., enterprise software).


## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?

Understanding Commits in Git and GitHub
A commit in Git is a snapshot of your project at a specific point in time. It helps in tracking changes, maintaining a version history, and allowing developers to revert to previous versions if needed. Each commit has a unique hash (ID) and a commit message that describes what was changed.

🔹 Steps to Make Your First Commit on GitHub
Step 1: Set Up Git (If Not Already Installed)
Before making a commit, ensure Git is installed. Check by running:

bash
Copy
Edit
git --version
If not installed, download and install it from git-scm.com.

Step 2: Configure Git (Only Needed Once)
Set your name and email (this is required for commit authorship):

bash
Copy
Edit
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Step 3: Create or Clone a Repository
You can either create a new repository or clone an existing one.

Option 1: Create a New Repository Locally
Open a terminal and create a new folder for your project:
bash
Copy
Edit
mkdir my-project
cd my-project
Initialize a new Git repository:
bash
Copy
Edit
git init
This creates a hidden .git folder that tracks your changes.
Option 2: Clone an Existing Repository from GitHub
If you already created a repository on GitHub, clone it with:

bash
Copy
Edit
git clone https://github.com/your-username/repository-name.git
cd repository-name
Step 4: Add a File to the Repository
Create a file (e.g., README.md) and add some content:

bash
Copy
Edit
echo "# My First GitHub Project" > README.md
Step 5: Stage the Changes
Staging prepares files for committing. Add all files using:

bash
Copy
Edit
git add .
or add specific files:

bash
Copy
Edit
git add README.md
Step 6: Commit the Changes
Create a commit with a meaningful message:

bash
Copy
Edit
git commit -m "Initial commit: Added README file"
This records the changes in Git’s history.

Step 7: Connect the Repository to GitHub (If Created Locally)
If you created the repository locally, link it to a GitHub repository:

bash
Copy
Edit
git remote add origin https://github.com/your-username/repository-name.git
git branch -M main
Step 8: Push the Changes to GitHub
Upload your commit to GitHub:

bash
Copy
Edit
git push -u origin main
Now, your commit is live on GitHub! 🎉

🔹 Why Are Commits Important?
✅ Version Control – Allows you to track every change in your project.
✅ Collaboration – Helps multiple developers work on the same project without conflicts.
✅ Revert to Previous Versions – If an error occurs, you can roll back to a previous commit.
✅ Documentation – Commit messages provide a history of changes, making it easier to understand the evolution of the project.



## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.

Understanding Branching in Git
Branching in Git allows developers to create separate lines of development within a repository. Instead of making changes directly to the main branch, developers can create new branches to work on features, bug fixes, or experiments without affecting the main project.

Why is branching important?
✅ Enables parallel development – Multiple developers can work on different features simultaneously.
✅ Keeps the main branch stable – New features or fixes are developed and tested before merging.
✅ Facilitates code reviews and testing – Changes can be reviewed in isolation before integration.
✅ Allows quick bug fixes – A separate branch can be created to address urgent issues without interfering with ongoing development.

🔹 How to Create, Use, and Merge Branches in GitHub
Step 1: Check Existing Branches
To see the current branches in your repository, run:

bash
Copy
Edit
git branch
The active branch will have an asterisk (*).

Step 2: Create a New Branch
To create a new branch (e.g., feature-branch):

bash
Copy
Edit
git branch feature-branch
But this only creates the branch—it doesn’t switch to it yet.

To switch to the new branch:

bash
Copy
Edit
git checkout feature-branch
Or, use the shortcut to create and switch at once:

bash
Copy
Edit
git checkout -b feature-branch
Step 3: Make Changes in the New Branch
Modify files, add new features, or fix bugs. Once changes are made, stage and commit them:

bash
Copy
Edit
git add .
git commit -m "Added a new feature"
Step 4: Push the Branch to GitHub
To share the branch on GitHub, push it using:

bash
Copy
Edit
git push -u origin feature-branch
This makes the branch available for collaboration.

Step 5: Merge the Branch into Main
Once the work is complete, merge it into the main branch:

1️⃣ Switch to the main branch:

bash
Copy
Edit
git checkout main
2️⃣ Pull the latest changes:

bash
Copy
Edit
git pull origin main
3️⃣ Merge the feature branch:

bash
Copy
Edit
git merge feature-branch
4️⃣ Push the updated main branch to GitHub:

bash
Copy
Edit
git push origin main
Step 6: Delete the Merged Branch (Optional)
After merging, if the branch is no longer needed, delete it locally:

bash
Copy
Edit
git branch -d feature-branch
And delete it on GitHub:

bash
Copy
Edit
git push origin --delete feature-branch
🔹 How Branching Supports Collaborative Development
Multiple developers can work on different features without interfering with each other.
Code reviews and pull requests ensure quality before merging into main.
Bug fixes can be quickly applied in separate branches without delaying feature development.
Safe experimentation allows developers to test new ideas without breaking the main codebase.


## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?

The Role of Pull Requests in GitHub Workflow
A Pull Request (PR) in GitHub is a feature that facilitates code review, discussion, and collaboration before merging changes into the main branch. It allows developers to propose changes, get feedback from team members, and ensure code quality before merging it into the main project.

✅ Why Are Pull Requests Important?
Encourages Code Review – Other team members can review and suggest improvements before merging.
Enhances Collaboration – Multiple contributors can discuss and refine changes in an organized way.
Prevents Bugs and Issues – Ensures that code is tested and meets project standards before integration.
Tracks History of Changes – Provides a transparent record of modifications and discussions.
🔹 Steps to Create and Merge a Pull Request on GitHub
Step 1: Create a New Branch
Before making changes, create and switch to a new branch:

bash
Copy
Edit
git checkout -b feature-branch
This isolates your work from the main branch.

Step 2: Make Changes and Commit Them
Modify your files, then stage and commit the changes:

bash
Copy
Edit
git add .
git commit -m "Added a new feature"
Step 3: Push the Branch to GitHub
Push the new branch to the remote repository:

bash
Copy
Edit
git push -u origin feature-branch
Now, the branch is visible on GitHub.

Step 4: Open a Pull Request (PR) on GitHub
1️⃣ Go to your repository on GitHub.
2️⃣ Click on the Pull Requests tab.
3️⃣ Click New Pull Request.
4️⃣ Select your feature-branch and compare it with main.
5️⃣ Write a title and description explaining the changes.
6️⃣ Click Create Pull Request.

Step 5: Review and Discuss the Changes
Other developers or team members review the PR and suggest improvements.
Comments and discussions happen directly on the changed lines of code.
Additional commits can be pushed to the same branch if modifications are needed.
Step 6: Merge the Pull Request
Once the PR is approved, merge it into the main branch:

1️⃣ Click Merge Pull Request on GitHub.
2️⃣ Confirm by clicking Confirm Merge.
3️⃣ Delete the feature branch (optional) after merging to keep the repository clean.

Alternatively, merge manually via Git:

bash
Copy
Edit
git checkout main
git pull origin main
git merge feature-branch
git push origin main
git branch -d feature-branch  # Delete locally
git push origin --delete feature-branch  # Delete on GitHub

## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?

Understanding Forking in GitHub
What is Forking?
Forking a repository on GitHub means creating a personal copy of another user’s repository in your own GitHub account. This allows you to freely experiment, make changes, and contribute to the original project without directly affecting it.

Key characteristics of forking:

Creates a separate copy of the repository under your GitHub account.
Maintains a connection with the original repository (upstream), allowing you to pull updates.
Enables contribution to open-source projects via pull requests.
🔹 Forking vs. Cloning: Key Differences
Feature	Forking	Cloning
Where the copy exists	On GitHub (remote)	On your local machine
Purpose	Contribute to someone else’s repo	Work on a local copy of any repository
Connection to the original repo	Maintains a link (upstream updates possible)	No link; it’s independent
Ownership	You own the forked repo on GitHub	You don’t own the cloned repo
Best for	Contributing to open source & public projects	Personal/local development
🔹 When is Forking Useful?
1️⃣ Contributing to Open-Source Projects

If you want to improve or fix a public project, you fork it, make changes, and submit a pull request to the original repository.
2️⃣ Experimenting with an Existing Project

You can modify and test a repository without affecting the original project.
3️⃣ Creating a Personal Version of a Public Repository

Useful if you want to maintain your own variations of a project while keeping access to upstream updates.
4️⃣ Collaborating Without Direct Access

If you don’t have write access to a repository, forking allows you to work on a copy and submit improvements later.
🔹 How to Fork and Work with a Repository on GitHub
Step 1: Fork the Repository
Navigate to the original GitHub repository.
Click the Fork button (top-right corner).
A copy of the repository appears in your GitHub account.
Step 2: Clone Your Fork Locally
bash
Copy
Edit
git clone https://github.com/your-username/forked-repository.git
cd forked-repository
This allows you to work on the project on your machine.

Step 3: Set Up the Original Repository as Upstream
To keep your fork updated with the latest changes from the original repository:

bash
Copy
Edit
git remote add upstream https://github.com/original-owner/original-repository.git
git fetch upstream
Step 4: Make Changes and Push to Your Fork
After modifying files:

bash
Copy
Edit
git add .
git commit -m "Made improvements"
git push origin main
Step 5: Submit a Pull Request
Go to your forked repository on GitHub.
Click Compare & pull request.
Add a title and description, then click Create pull request to suggest changes to the original repository.


## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.

The Importance of Issues and Project Boards on GitHub
GitHub provides Issues and Project Boards as essential tools for managing software development workflows. These tools help track bugs, manage tasks, and improve project organization, making collaboration more structured and efficient.

🔹 GitHub Issues: Tracking Bugs and Tasks
What Are GitHub Issues?
GitHub Issues act as a task management system within a repository. Developers can report bugs, suggest features, track progress, and assign tasks to team members.

How Issues Enhance Project Management
✅ Bug Tracking: Developers can log issues when they find bugs, describe the problem, and assign it to someone for resolution.
✅ Feature Requests: Users can propose new features, discuss them with maintainers, and get feedback.
✅ Task Management: Issues help break down work into smaller tasks, making large projects easier to manage.
✅ Collaboration & Discussion: Each issue has a comment section where contributors can discuss solutions.
✅ Integration with PRs: Issues can be linked to pull requests, automatically closing when the PR is merged.

Example of Using GitHub Issues
1️⃣ A user finds a bug in a project and opens an issue with a detailed description.
2️⃣ The maintainer assigns the issue to a developer.
3️⃣ The developer fixes the bug and submits a pull request that references the issue.
4️⃣ When the PR is merged, the issue is automatically closed.

🔹 GitHub Project Boards: Organizing Workflows
What Are GitHub Project Boards?
Project Boards in GitHub function as a Kanban-style task management tool. They help teams organize, prioritize, and track progress in a visual format.

How Project Boards Enhance Collaboration
✅ Visual Workflow: Organizes tasks in columns like "To Do," "In Progress," and "Done."
✅ Task Assignment: Developers can be assigned tasks, ensuring accountability.
✅ Customizable Statuses: Teams can create custom columns for better organization.
✅ Automation: Tasks can move between columns based on actions (e.g., closing an issue moves it to "Done").
✅ Improves Sprint Planning: Helps Agile teams manage short-term development cycles effectively.

Example of Using GitHub Project Boards
1️⃣ A project board is created with columns: Backlog, In Progress, Review, and Completed.
2️⃣ Issues are added to the Backlog column.
3️⃣ A developer starts working on an issue and moves it to In Progress.
4️⃣ When a pull request is submitted, the issue moves to Review.
5️⃣ Once merged, the issue moves to Completed.

🔹 How These Tools Improve Collaboration
Enhances transparency by allowing all team members to see ongoing work.
Improves efficiency by organizing tasks clearly and avoiding duplication.
Encourages teamwork through discussions, assignments, and shared accountability.
Streamlines bug fixes by ensuring no issue goes unnoticed.


## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?

🔹 Common Challenges and Best Practices in Using GitHub for Version Control
While GitHub is a powerful tool for version control and collaboration, new users often face challenges in managing repositories, merging changes, and understanding workflows. Below are some common pitfalls and best practices to help navigate these challenges effectively.

🔹 Common Pitfalls in Using GitHub
1️⃣ Merge Conflicts
Problem: When multiple people edit the same file, Git may struggle to merge changes.
Solution:
✅ Pull the latest changes before making edits:
bash
Copy
Edit
git pull origin main
✅ Use branches to work on separate features and avoid direct changes to main.
✅ Manually resolve conflicts by reviewing the conflicting lines before merging.
2️⃣ Forgetting to Commit Regularly
Problem: Making too many changes before committing can make debugging difficult.
Solution:
✅ Commit small, logical changes often.
✅ Write clear and descriptive commit messages (e.g., "Fixed login bug", not "Updated file").
bash
Copy
Edit
git commit -m "Refactored user authentication module"
3️⃣ Pushing to the Main Branch Directly
Problem: Directly pushing to main can introduce errors and disrupt a stable version.
Solution:
✅ Use feature branches:
bash
Copy
Edit
git checkout -b new-feature
✅ Open a Pull Request (PR) for review before merging into main.
4️⃣ Working Without a Remote Backup
Problem: Local changes can be lost if not pushed to GitHub.
Solution:
✅ Regularly push changes to a remote repository:
bash
Copy
Edit
git push origin feature-branch
✅ Use forking if working on a public repo without write access.
5️⃣ Cluttered or Disorganized Repository
Problem: Large, unorganized repositories make collaboration difficult.
Solution:
✅ Structure repositories with proper folders (e.g., src/, docs/, tests/).
✅ Maintain a clear README to guide contributors.
✅ Use .gitignore to exclude unnecessary files:
bash
Copy
Edit
__pycache__/
node_modules/
.env
🔹 Best Practices for Smooth Collaboration
✔️ 1. Use Branching Effectively
Keep the main branch stable and create feature branches for development.
Follow a naming convention (e.g., feature-login-page, bugfix-typo).
✔️ 2. Sync Regularly with the Remote Repository
Before starting work, always fetch the latest updates:
bash
Copy
Edit
git pull origin main
✔️ 3. Write Meaningful Commit Messages
A good commit message should describe what was changed and why.
Example of a good commit:
bash
Copy
Edit
git commit -m "Fixed issue #23: Resolved API timeout error"
✔️ 4. Leverage Pull Requests for Code Review
Open a PR and request team reviews before merging to main.
Discuss and suggest improvements in PR comments.
✔️ 5. Automate and Use GitHub Features
Use GitHub Actions to automate tests and deployments.
Leverage Issues and Project Boards for task tracking.
