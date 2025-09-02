# 🧭 Template Navigator: A Guide to Our Workflow

Welcome, Architect! This guide is your map to using the templates in our ecosystem. Following these workflows ensures that our projects, notes, and resources remain organized, consistent, and easy to find.

---

## `project-brief-template.md` 📋

-   **Purpose:** To define the **"What, Why, and How"** of a project before work begins. It aligns all collaborators on the goals, scope, and technical plan.
-   **When to Use It:** At the beginning of **any new collaborative project**, for both `learn-` and `folio-` repositories.
    -   For `learn-` projects, it can be a lightweight plan.
    -   For `folio-` projects, it should be a detailed architectural document.

### Step-by-Step Workflow

1.  ➡️ **Create Your Project Repository:** Name it `learn-<topic>` or `folio-<project-name>`.
2.  ➡️ **Navigate to the `/templates` Directory:** In the `learning-hub` repository, find and open `project-brief-template.md`.
3.  ➡️ **Copy the Template:** Click the "Raw" button to view the plain text, then copy all of the content.
4.  ➡️ **Create the Brief File:** In your **new project repository**, create a new file named `PROJECT-BRIEF.md` (using `SCREAMING_SNAKE_CASE` here helps it stand out as a foundational document).
5.  ➡️ **Paste and Collaborate:** Paste the template content and work with your team to fill out every section. This is your project's constitution!

---

## `learning-log-template.md` 📖

-   **Purpose:** To serve as a **personal or collaborative journal** for a `learn-` project. It captures the process, the "aha!" moments, and the key takeaways. This is the heart of our project-based learning.
-   **When to Use It:** As the primary document inside every `learn-` repository.

### Step-by-Step Workflow

1.  ➡️ **Create Your `learn-<topic>` Repository.**
2.  ➡️ **Copy the Template:** Go to `/templates/learning-log-template.md` in the Hub and copy the raw content.
3.  ➡️ **Create the Log File:** In your new `learn-` repo, create a file named `learning-log.md`.
4.  ➡️ **Paste and Plan:** Paste the template and fill out the "Learning Objectives" section first. This sets your intention.
5.  ➡️ **Document Your Journey:** Update this file regularly as you code, solve problems, and learn new things. It will become an invaluable record of your growth.

---

## `resource-submission-template.md` 🔗

-   **Purpose:** To add a valuable new article, video, tool, or course to our shared **Resource Library** in the `learning-hub`.
-   **When to Use It:** Whenever you find an amazing resource the whole team can benefit from.

### Step-by-Step Workflow

1.  ➡️ **Fork the `learning-hub` Repository:** Create a personal copy of the Hub on your own GitHub account.
2.  ➡️ **Create a New Branch:** In your fork, create a new branch with a descriptive name (e.g., `feat/add-react-hooks-guide`).
3.  ➡️ **Find the Right Home:** Navigate to the `/resources` directory. Choose or create a sub-directory that fits the resource (e.g., `/resources/javascript/`).
4.  ➡️ **Create the Resource File:** Inside that directory, create a new file named after the resource (e.g., `ultimate-guide-to-react-hooks.md`).
5.  ➡️ **Copy and Paste the Template:** Open `/templates/resource-submission-template.md` in the Hub, copy the raw content, and paste it into your new file.
6.  ➡️ **Fill It Out:** Complete the template with the link, summary, and tags.
7.  ➡️ **Submit a Pull Request (PR):** Commit your changes and open a PR from your branch to the `main` branch of the original `learning-hub`. Your submission will be reviewed and merged!

## ✍️ `learning-notes-template.md`

-   **Purpose:** To take structured notes on a specific, small-scale topic, often related to a larger roadmap or project.
-   **When to Use It:** For daily study, meeting notes, or breaking down a complex subject into smaller, digestible pieces.

### Step-by-Step Workflow

1.  ➡️ **Locate Your Project:** These notes typically live inside the project repository they relate to (a `learn-` or `folio-` repo).
2.  ➡️ **Create a Notes Directory (Optional):** For organization, it's a good practice to create a `/notes` or `/docs` directory inside your project repo.
3.  ➡️ **Create Your Note File:** Inside the appropriate directory, create a new file named with `kebab-case` (e.g., `notes/understanding-async-await.md`).
4.  ➡️ **Copy and Paste the Template:** Go to `/templates/learning-notes-template.md` in the `learning-hub`, copy the raw content, and paste it into your new note file.
5.  ➡️ **Document Your Learning:** Fill out the concepts, code snippets, and questions as you study. Commit these notes as you would any other project file.
