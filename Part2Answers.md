# PART 2

# GitHub Questions

## Q1. Browser-Based Editing
**What GitHub features allow contributors to make simple code changes directly from the web browser? Describe at least two**

GitHub allows you to edit direct in the files or in code workspace
---

## Q2. Codespaces Lifecycle
**What are the lifecycle phases of a GitHub Codespace, and what happens in each phase?**

1. Creation   2. Runnning    3. Stopped     4. Deleted
---

## Q3. Unsaved Work in Codespaces
**What happens to your work if you stop a GitHub Codespace without committing your changes?**

If the codespace has not been deleted the changes will be there
---

## Q4. Two-Factor Authentication (2FA)
**Who should enable two-factor authentication (2FA) on GitHub, and why?**

Every user should enable it. Because it protects your account, code and repositories from unauthorized access
---

## Q5. Repository Permission Levels
**What permission levels exist for repositories owned by a personal GitHub account?**

Read, Triage, Write, Mantain, Admin
---

## Q6. Repository Visibility
**What repository visibility options does GitHub provide, and when would you use each?**

1. Public. You would use this when you are working with an open source project. 
2. Private. You would use this when working in intern projects or private project. 
3. Intenal. Use this when you want to collaborate with your organization.
---

## Q7. CODEOWNERS
**What is the purpose of a `CODEOWNERS` file?**

It defines what person or team is in charge of certain part of the code. When a file is modified it will need to be approved by the codeowner. 

---

## Q8. Required Status Checks
**How can you enforce that status checks must pass before merging into the `main` branch?**

1. Go to the repository Settings.
2. Open the Branches section.
3. Create or edit a Branch Protection Rule for main.
4. Enable Require status checks to pass before merging.
5. Select the required status checks.
---

## Q9. Required Review Approvals
**What steps can you take to ensure changes to `main` require approval from at least two reviewers?**

1. Go to Settings → Branches.
2. Create or edit the branch protection rule for main.
3. Enable Require a pull request before merging.
4. Set Required approving reviews to 2.
---

## Q10. CodeQL
**What is CodeQL, and how is it used in GitHub?**

It is a tool for code analysis. It allows you to detect vulnerabilites and security problemas through the source code. 
---

## Q11. Forks
**What is a fork in GitHub, and when should you use one?**

It a personal copy from other person repository. You would use it when working in open source projects. 

---

## Q12. Pull Requests
**What is a pull request in GitHub?**

It is a request to merge changes from a branch to other. It allows you to check code, modify and approve changes. 
---

## Q13. Base vs Compare Branch
**When creating a pull request from `feature-a` into `main`, which branch is the base and which is the compare?**

- **Base branch:** `main`
- **Compare branch:** `feature-a`

---

## Q14. Draft Pull Requests
**What are draft pull requests, and when should they be used?**

It is when a pr has not been merged. You still working on it. 
You can use when your changes are not fully done. 