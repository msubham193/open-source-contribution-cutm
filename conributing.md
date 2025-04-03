# Contributing to TechStore Website Project

Thank you for your interest in contributing to the TechStore Website Project! This document outlines the process for contributing, coding standards, and expectations to ensure a smooth collaboration.

## How to Contribute

Follow these steps to contribute to the project:

### Fork the Repository

1. Go to the TechStore repository on GitHub.
2. Click the "Fork" button to create a copy under your GitHub account.

### Clone Your Fork

Run this command in your terminal:

```bash
git clone https://github.com/your-username/techstore.git
```

Replace `your-username` with your GitHub username.

### Create a Branch

Use a descriptive branch name related to your task (e.g., `fix-nav-responsive`, `add-dark-mode`):

```bash
git checkout -b branch-name
```

### Make Changes

1. Work on your assigned task (see tasks in the repository's issue tracker).
2. Modify the relevant files (e.g., `index.html`, `css/styles.css`, `js/script.js`).

### Test Your Changes

- Open `index.html` in a browser to verify your changes work as expected.
- Test across different screen sizes if applicable (e.g., mobile responsiveness).

### Commit Your Changes

Stage and commit your work with a clear message:

```bash
git add .
git commit -m "Fixed navigation menu overlap on mobile"
```

### Push to Your Fork

Upload your branch to your GitHub fork:

```bash
git push origin branch-name
```

### Submit a Pull Request (PR)

1. Go to your fork on GitHub and click "New Pull Request."
2. Select your branch and submit it to the main repository’s main branch.
3. Include a clear description of your changes (e.g., what you fixed/added, files modified).

## Assigned Tasks

Refer to the repository's issue tracker for the full list of bug fixes and feature enhancements. Each task includes:

- **Issue**: Description of the problem or feature.
- **Task**: What needs to be done.
- **Files to Modify**: Specific files to work on.

## Coding Standards

To maintain consistency, please adhere to these guidelines:

### HTML

- Use semantic tags (e.g., `<header>`, `<footer>`).
- Indent with 2 spaces.

### CSS

- Use lowercase class names with hyphens (e.g., `.cart-count`).
- Group media queries at the end of `styles.css`.
- Indent with 2 spaces.

### JavaScript

- Use camelCase for variables and functions.
- Add comments for complex logic.
- Indent with 2 spaces.

### File Naming

- Keep existing naming conventions (e.g., `styles.css`, `script.js`).

### Commit Messages

- Write concise, descriptive messages in past tense (e.g., "Added dark mode toggle").

## Pull Request Process

### Title

Summarize your change (e.g., "Fix Navigation Menu Responsiveness").

### Description

Explain:

- What you changed.
- Why it was necessary.
- Files modified.

#### Example

```
Fixed overlapping navigation menu items on mobile screens (<768px).
Modified: css/styles.css (updated media queries).
Tested on Chrome and Firefox.
```

### Submit

- Request a review from the project maintainers.

Thank you for contributing to the TechStore Website Project!

