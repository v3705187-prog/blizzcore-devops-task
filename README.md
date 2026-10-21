
# BLIZZCORE — Responsive Technology Landing Page

## 1. Project Overview

BLIZZCORE is a responsive static landing-page concept developed as part of a Junior DevOps Engineer recruitment assessment.

The project demonstrates foundational skills in web development, Git version control, technical documentation, GitHub repository management, and static website deployment using GitHub Pages.

## 2. Live Deployment

**Live website:** https://v3705187-prog.github.io/blizzcore-devops-task/

**Source repository:** https://github.com/v3705187-prog/blizzcore-devops-task

The website is hosted using GitHub Pages. The deployed page was manually checked in a web browser.

## 3. Technologies Used

- HTML5 — semantic page structure and content
- CSS3 — styling, responsive layout, and visual presentation
- Git — version control and change tracking
- GitHub — remote source code hosting
- GitHub Pages — static website hosting

## 4. Project Structure

```text
blizzcore-devops-task/
├── index.html
└── README.md
```

- `index.html`: Contains the website structure, styling, navigation, and page content.
- `README.md`: Documents the project, local setup, deployment process, and configuration considerations.

## 5. Features

- Responsive layout for desktop and mobile screens
- Modern navy, cyan, and white colour palette
- Navigation links to page sections
- Service cards and introductory content
- Semantic HTML elements
- CSS custom properties for consistent styling
- No external packages or build tools required

## 6. Running the Project Locally

This is a static website and does not require a backend server, package manager, or build process.

### Prerequisites

- Git installed on your computer
- A modern web browser
- A code editor, such as Visual Studio Code (optional)

### Setup Instructions

Clone the repository:

```bash
git clone https://github.com/v3705187-prog/blizzcore-devops-task.git
```

Navigate to the project directory:

```bash
cd blizzcore-devops-task
```

Open `index.html` directly in a web browser.

Alternatively, open the project folder in Visual Studio Code and use a local preview extension if available.

## 7. Version Control Workflow

Git was used to track changes throughout development.

The project includes separate commits for documentation and webpage implementation.

Example commands used in the workflow:

```bash
git status
git add README.md
git commit -m "docs: add project documentation"

git add index.html
git commit -m "feat: add responsive BLIZZCORE landing page"

git log --oneline
```

These commands demonstrate working-tree inspection, staging, committing, and reviewing project history.

## 8. Deployment with GitHub Pages

GitHub Pages was used to publish the static website from the repository.

### Deployment Configuration

- Source: Deploy from a branch
- Branch: `main`
- Publishing directory: `/` (repository root)
- Entry point: `index.html`

### Deployment Procedure

1. Create a GitHub repository and push the project to the remote repository.
2. Open the repository's Settings.
3. Navigate to Pages.
4. Select Deploy from a branch as the publishing source.
5. Select the `main` branch and the root directory (`/`).
6. Save the configuration.
7. Allow GitHub Pages to build and publish the site.
8. Open the published URL and verify that the website loads correctly.

### Updating the Deployment

After making changes locally, commit and push them to GitHub:

```bash
git add .
git commit -m "update: improve project documentation"
git push origin main
```

GitHub Pages can publish the updated static files from the configured branch. The deployment should be checked after pushing changes.

## 9. Environment Configuration and Security

The current project consists entirely of static HTML and CSS. It does not require environment variables, API credentials, database connections, or backend services.

For a future application with a backend, configuration should be separated by environment where appropriate. Sensitive credentials should be stored using environment variables or an appropriate secrets manager and must never be committed to version control.

A `.env` file containing secrets should be excluded using `.gitignore`. Any secret exposed in a repository should be treated as compromised and rotated.

## 10. Testing and Verification

The following manual checks were performed:

- Opened the HTML page in a browser.
- Checked the Git repository and project files.
- Created separate Git commits for the documentation and webpage.
- Pushed the project to GitHub.
- Configured GitHub Pages.
- Opened the published website after resolving an initial deployment issue.

Automated tests, security scans, and cross-browser test suites have not been implemented in this version.

## 11. Current Limitations and Future Improvements

Potential improvements include:

- Add automated HTML validation and accessibility checks.
- Introduce a GitHub Actions workflow for automated validation and deployment.
- Add automated checks before changes are published.
- Expand accessibility and cross-browser testing.
- Separate CSS into its own stylesheet as the project grows.

## 12. Author

Victory


