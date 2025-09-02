# 🗺️ Ecosystem Workflows

> This document is our official playbook. It provides concise, step-by-step instructions for the most common scenarios in our collaborative learning ecosystem.

---

## Scenario 1: Proposing a New Project (`learn-` or `folio-`)

_Use this workflow when you have an idea for a new learning topic or portfolio project._

1.  ➡️ **Create Issue:** In the `learning-hub` repository, create a new **Issue** using the `💡 Propose a New Learning Topic` template.
2.  ➡️ **Fill & Submit:** Fill out the details of your proposal and submit the issue.
3.  ➡️ **Discuss & Approve:** The repository owner and collaborators will discuss the idea in the issue comments. The owner will approve it by adding a label (e.g., `status:approved`).
4.  ➡️ **Create Workspace:** Once approved, a new, separate **Repository** is created (e.g., `learn-css-animations`).
5.  ➡️ **Link to Hub:** A **Pull Request** is made to the `learning-hub` to add the new project's link to the `PROJECTS.md` file.
6.  ➡️ **Break Down Work:** The project idea is broken down into smaller tasks using the `🛠️ Define a Project Task` issue template.
7.  ➡️ **Begin Work:** You and other collaborators can now claim a task and begin contributing to the **new project repository**.

---

## Scenario 2: Fixing a Bug or Typo

_Use this workflow for fixing any errors in the `learning-hub` or any of the project repositories._

1.  ➡️ **Create Issue:** In the repository where you found the error, create an **Issue** using the `🐞 Bug Report` template.
2.  ➡️ **Fork & Branch:** Create a fork of the repository and make a new branch with a name like `fix/correct-readme-typo`.
3.  ➡️ **Fix It:** Make the necessary changes to fix the bug.
4.  ➡️ **Create PR:** Open a **Pull Request** back to the original repository. In the description, link the issue you created (e.g., "Closes #123").
5.  ➡️ **Review & Merge:** Wait for a teammate to review and approve your PR. Once merged, the fix is live!

---

## Scenario 3: Contributing a New Resource

_Use this workflow for adding a helpful article, video, or tool to the `learning-hub`'s resource library._

1.  ➡️ **Fork & Branch:** Fork the `learning-hub` repository and create a new branch (e.g., `feat/add-flexbox-video-guide`).
2.  ➡️ **Create File:** Go to the `/resources` directory, find the appropriate sub-folder, and add a new `.md` file.
3.  ➡️ **Use Template:** Fill out the new file using the content from the `🔗 Resource Submission` template.
4.  ➡️ **Create PR:** Open a **Pull Request** to merge your new resource file into the `learning-hub`.
5.  ➡️ **Review & Merge:** Your submission will be reviewed, and once approved, it will be added to the library.
