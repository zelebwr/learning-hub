# 📜 Naming Conventions Guide

A consistent naming strategy is essential for clarity and organization. These conventions provide a baseline for our ecosystem, ensuring everyone can navigate our projects intuitively.

---

## General Principle: Technology First

Our primary rule is to **always defer to the established conventions of the programming language or framework** being used within a specific project. For example, a Python project should use Python conventions, and a React project should use React conventions.

When no specific technology convention applies (e.g., for Markdown files, images, or general documentation), use **`kebab-case`**.

---

## 🗂️ Repositories

Repositories are prefixed to make their purpose immediately clear.

-   `learn-<topic-name>`: **For Learning Projects.** The goal is the learning process. These are our sandboxes for experimentation.
    -   _Example:_ `learn-css-flexbox-gallery`
-   `folio-<project-name>`: **For Portfolio Projects.** The goal is a polished, well-documented final product suitable for showcasing.
    -   _Example:_ `folio-recipe-sharing-app`

---

## 📄 Files: A Language-Specific Approach

This is where context matters most.

### General Purpose & Web Files (`kebab-case`)

For all documentation, configuration, and web asset files where a framework doesn't specify otherwise.

-   **Use Case:** `.md`, `.html`, `.css`, `.svg`, `.png`, `.json`, `.yml`
-   **Format:** `all-lowercase-words-separated-by-hyphens`
-   **Example:** `learning-log.md`, `user-profile-card.css`, `api-configuration.json`

### JavaScript: Components (`PascalCase`) & Modules (`camelCase`)

-   **`PascalCase`:** For files that export a class or a component (e.g., React, Vue, Svelte).
    -   **Format:** `WordsAreJoinedAndCapitalized`
    -   **Example:** `UserProfile.jsx`, `ModalDialog.vue`
-   **`camelCase`:** For general-purpose JavaScript modules and utility files.
    -   **Format:** `firstWordLowerThenCapitalized`
    -   **Example:** `apiClient.sjs`, `stringUtils.ts`

### Python (`snake_case`)

-   **Use Case:** All Python `.py` files.
-   **Format:** `all_lowercase_words_separated_by_underscores`
-   **Example:** `database_connector.py`, `data_processing_utils.py`

### Constants & Environment (`SCREAMING_SNAKE_CASE`)

-   **Use Case:** Environment variable files or files that export only constants.
-   **Format:** `ALL_UPPERCASE_WORDS_SEPARATED_BY_UNDERSCORES`
-   **Example:** `CONSTANTS.js`, `.env.production`

---

## 📦 In-Code Naming (Variable, Functions, Classes)

This is a critical layer of convention that ensures readability within our code files.

### General

-   **Constants:** `SCREAMING_SNAKE_CASE`
    -   **Use Case:** For variables that should not be changed (e.g., configuration values, fixed thresholds).
    -   **Example:** `const MAX_CONNECTIONS = 10;`, `API_KEY = "..."`

### JavaScript (and Variants like TypeScript)

-   **Variables & Functions:** `camelCase`
    -   **Format:** `firstWordLowerThenCapitalized`
    -   **Example:** `let userProfile;`, `function getUserData() {}`
-   **Classes & Components:** `PascalCase`
    -   **Format:** `WordsAreJoinedAndCapitalized`
    -   **Example:** `class ApiClient {}`, `function UserProfileCard() {}`

### Python

-   **Variables & Functions:** `snake_case`
    -   **Format:** `all_lowercase_words_separated_by_underscores`
    -   **Example:** `user_profile = {}`, `def get_user_data():`
-   **Classes:** `PascalCase` (often called `CapWords` in Python)
    -   **Format:** `WordsAreJoinedAndCapitalized`
    -   **Example:** `class ApiClient:`

> **Remember:** The goal is readability. Choose names that are descriptive and clear. A variable named `user_list` is infinitely better than `ul`.
