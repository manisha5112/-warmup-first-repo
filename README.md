# -warmup-first-repo

## Understand Git & Version Management

##1.basics of Git: staging, commits, push, pull, merge
### Objective:
To understand Git basics, version control, branching strategies, and team collaboration.

### Basics of Git:
Git is a distributed version control system that tracks code changes and helps developers collaborate.

### Important Git Commands:
1. Staging (git add)
Selects changes for the next commit.
git add README.md

2. Commit (git commit)
Saves staged changes with a message.
git commit -m "Update README"

3. Push (git push)
Uploads local commits to GitHub.
git push origin main

4. Pull (git pull)
Fetches and integrates remote changes.
git pull origin main

5. Merge (git merge)
Combines changes from one branch into another.
git merge feature/login


### Branching Strategies
main: Contains stable, production-ready code.
dev: Integrates and tests changes before release.
feature/*: Used to develop individual features, e.g., feature/login.

### What Git Solves in Collaborative Development
Git helps multiple developers work on the same project efficiently. It tracks code changes, maintains version history, and allows developers to work on separate branches without affecting the main code. It also helps identify and resolve merge conflicts, supports code reviews through Pull Requests, and allows teams to share their changes using push and pull. Overall, Git makes teamwork easier, safer, and more organized.


##2. Create a GitHub Repo

### Objective: 
Create a GitHub repository to store warmup learnings and practice Git version control.

### Tasks Completed:
•	Created a GitHub repository named warmup-first-repo.
•	Added a README.md file summarizing my learnings about Git, GitHub, branching strategies, collaborative development, and essential development tools.
•	Practiced making commits to track changes in the README file.


## 3. Release Management Process
### Objective
To understand the release process at FloCard and how QA, Testing, FOU, and Deployment are coordinated.

### What is a Release?
A release is a version of a software product that is prepared and made available to users or a target environment after the required checks and approvals.

### Key Activities

- **QA (Quality Assurance):** Ensures that the product meets quality standards.
- **Testing:** Checks features, identifies bugs, and verifies that changes work correctly.
- **FOU:** The role and responsibilities of FOU need to be confirmed through internal documentation or a mentor.
- **Deployment:** Makes the approved software version available in the target environment.
- **Coordination:** Development, QA, Testing, FOU, and Deployment teams coordinate to review changes, fix issues, obtain required approvals, and release the software smoothly.

### General Release Workflow
Development → QA & Testing → Issue Fixes → Required Approvals → Deployment → Post-release Verification

### Key Learning
Release management helps teams deliver software updates in a controlled and organized manner. Coordination between development, QA, testing, and deployment reduces errors and improves release reliability.


## 4. Setup Essential Development Tools
### Objective
To install, configure, and verify the essential tools required for software development and API testing.

### Tools and Their Uses
1. Git CLI / GitHub Desktop
Used for version control, tracking code changes, managing branches, and collaborating through GitHub.
Verification: git --version

2. VS Code / Android Studio
Used to write, edit, debug, and manage application code. The editor should be selected according to project requirements.
Verification for VS Code: code --version

3. Postman / Thunder Client
Used to test APIs by sending HTTP requests such as GET, POST, PUT, and DELETE and checking responses.
Verification: Open Postman or Thunder Client and test an API request.

4. Node.js and NPM
Node.js runs JavaScript outside the browser, while NPM manages project packages and dependencies.
Verification:
node --version
npm --version

5. Docker Desktop
Used to run applications and their dependencies inside containers, helping maintain consistent development environments.
Verification: docker --version



##Learning how to create branches and merge changes in Git.
