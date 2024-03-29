# mowblox-git-workflow
A basic repo to help orient new devs on the mowblox git workflow

## 1. Local Development:

* Clone the main repository: Use `git clone <repo_url>` to obtain a local copy of the project's codebase.
* Create a branch from develop: Use `git checkout -b <branch_name>` to create a new branch for your specific development task. This keeps your changes isolated from the main codebase. (Use descriptive branch names!)
* Develop and commit changes: Make changes to your code and commit them regularly with clear and concise commit messages using `git commit -m "<message>"`.

## 2. Collaboration and Code Review:

* Push your branch: Once satisfied with your changes, push your branch to the remote repository using `git push origin <branch_name>`.
* Create a pull request: In the remote repository's hosting platform (e.g., GitHub, GitLab), create a pull request to propose your changes for merging into the main codebase to the `develop` branch.
* Code review: Collaborate with other developers by receiving feedback and addressing any issues raised in the pull request review process.

## 3. Integration and Deployment:

* Merge changes: Once approved, your branch can be merged into the main codebase (often done through the pull request platform). Merging can only be done by a team lead.
* Local repo cleanup: After PR is merged, the remote branch (head branch) will be deleted. It is your duty to fetch and update `develop` and also delete your working branch whose work is over immediately after the merge.
* Deployment: Depending on the team's setup, automated or manual deployment processes might integrate your changes into the live environment.

## Additional Tips:

* Fetch and rebase: Regularly use `git fetch` and `git rebase` to keep your local branch up-to-date with the main codebase.
* Resolve conflicts: In case of conflicts during merging, you'll need to manually resolve them using Git tools and commands.
* Branch naming conventions: Use a consistent naming scheme for your branches (e.g., **feature/my-new-feature**, **bugfix/fix-login-issue**).
* Documentation: Refer to your team's specific Git documentation or ask senior developers for guidance on any additional workflows or tools used at Mowblox.