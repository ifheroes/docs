---
layout: default
title: "Developer Guidelines"
parent: "Developers Docs"
nav_order: 1
---

# **Developer Guidelines - GitHub (2024)**

### **1. Purpose**

These guidelines outline the best practices and expectations for contributing to all repositories within our organization. Our aim is to foster a respectful, productive, and collaborative environment where everyone can contribute fairly and achieve the best results.

### **2. General Conduct**

1. **Respect and Courtesy**: Treat all contributors with respect. Conflicts should be resolved constructively and respectfully.
2. **Transparency**: Decisions, discussions, and changes should be communicated as openly as possible. This can include discussions on our Discord server or through GitHub Issues and discussions.
3. **Inclusivity**: All contributions are welcome, regardless of background, skills, or experience.
4. **Language**: We use **English** as the default language wherever possible. Repositories, documentation, pull requests, issues, and code comments should all be written in English to facilitate access for the wider developer community.

### **3. Branching and Merge Guidelines**

1. **`main` Branch**: This should contain production-ready, stable code.
2. **Feature Branches**: For new features or changes, follow clear naming conventions (`feature/...`, `bugfix/...`). You may include issue numbers in the branch name (`feature/#1234`).
3. **Changes in `main`**: Direct changes to the `main` branch are not allowed.
4. **Commit Messages**: Use clear and descriptive commit messages (`feat:`, `fix:`).
5. **Pull Requests**:
    1. Include detailed descriptions, screenshots, tests, and checklists where applicable.
    2. Ensure at least one review from a team member.
6. **Merge Strategies**:
    1. Use **Squash and Merge** to maintain a clean history.
    2. Ensure that tests, linters, and CI/CD checks pass before merging.

### **4. Handling Pull Requests and Forks**

1. **Submitting a Fork**: External contributors should ensure that their fork is up-to-date with the original repository. The PR should be well-documented with a description of the changes and their impact. The code should be well-structured and pass all tests. All merge conflicts must be resolved before submitting.
2. **Feedback**: Every external pull request (PR) should be reviewed and commented on promptly. This demonstrates appreciation for the contribution, motivates further involvement, and helps avoid misunderstandings or delays. Quick and professional feedback strengthens the organization’s reputation and facilitates efficient collaboration.
3. **Code Review**: Each PR must be reviewed before merging into the `main` or `feature` branch, as outlined in the Branching and Merge Guidelines.
4. **Feedback on Successful Reviews**: After a successful merge, we thank the contributor, update documentation if necessary, ensure all tests and CI checks have passed, clean the merge history for a tidy Git history, and provide constructive feedback.
5. **Feedback on Failed Reviews**: If a merge from a fork fails, we analyze the issues, provide feedback with suggested solutions, resolve conflicts together, recheck the code, and offer constructive feedback for improvement. In some cases, the PR may need to be closed and a new one opened.
6. **Merge Strategy**: When accepting a fork via PR, the team ensures that all tests and CI checks pass, selects the appropriate merge strategy (ideally “Squash and Merge”), performs the merge, provides feedback to the contributor, and updates documentation and tests as needed.

### **5. Consequences for Violations**

1. **Violation**: If a contributor violates these guidelines, they will initially be politely reminded and asked to correct the behavior.
2. **Severe Violations**: Repeated or severe violations may result in temporary limitations on contribution or permanent exclusion from the organization, with all actions communicated transparently.

## **Glossary 📖**

Here’s a quick reference for common abbreviations used in this guide:

1. **PR** – **Pull Request**: A request to merge changes from one branch (or fork) into another. Used to propose changes for review and approval.
2. **CI** – **Continuous Integration**: A development process where code changes are automatically integrated and tested to ensure they don’t break anything and keep the codebase stable.
3. **CD** – **Continuous Delivery/Continuous Deployment**: A development process where code changes, after passing CI checks, are automatically deployed to the production environment.
4. **Squash and Merge**: A merge strategy where all commits in a branch are combined into a single commit before merging into the target branch. This ensures a clean Git history.
5. **WIP** – **Work In Progress**: Indicates that a PR or branch is not yet complete and further work is needed.
6. **README**: A text file in a repository that provides important information about the project.
