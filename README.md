
# BLIZZCORE — Technology Landing Page

## Project Overview

BLIZZCORE is a responsive static landing-page concept created as part of a Junior DevOps Engineer recruitment task. The project demonstrates basic web development, version control, documentation, and deployment planning.

## Technologies Used

- HTML5 — page structure and semantic elements
- CSS3 — styling, layout, and responsive design
- Git — version control
- GitHub — source code hosting
- GitHub Pages — planned static website hosting

## Project Structure

```text
blizzcore-devops-task/
├── index.html
└── README.md
```

## Features

- Responsive layout for desktop and mobile screens
- Modern navy, cyan, and white colour palette
- Navigation links to page sections
- Service cards and introductory content
- Semantic HTML and basic accessibility practices
- CSS variables for consistent styling

## Run Locally

No build tools or package installation are required.

1. Clone the repository:

   ```bash
   git clone YOUR-REPOSITORY-URL
   ```

2. Enter the project directory:

   ```bash
   cd blizzcore-devops-task
   ```

3. Open `index.html` in a web browser.

Alternatively, open the file directly in your browser from File Explorer.

Replace `YOUR-REPOSITORY-URL` with the actual GitHub repository URL after creating the repository.

## Deployment

The website is a static HTML and CSS project. It can be deployed using GitHub Pages without a backend server or build pipeline.

Deployment procedure:

1. Push the project to a GitHub repository.
2. Open the repository's Settings.
3. Navigate to Pages.
4. Under Build and deployment, select Deploy from a branch.
5. Select the `main` branch and the root folder (`/`).
6. Save the settings and wait for GitHub Pages to publish the site.
7. Open the published URL and verify that the page loads correctly.

Deployment should be considered complete only after the published website has been tested successfully.

## Environment Configuration and Security

This project does not require environment variables because it contains only static HTML and CSS. There are no API keys, credentials, or backend services to configure.

For a future application with a backend, environment-specific settings should be managed through environment variables or an appropriate secrets manager. Sensitive credentials must never be committed to version control. A `.env` file containing secrets should be excluded through `.gitignore`.

## Version Control

Git is used to track project changes. The development history includes documentation and webpage implementation commits.

## Future Improvements

- Add automated HTML validation.
- Introduce a CI/CD workflow for deployment.
- Add automated checks before publishing changes.
- Improve accessibility and cross-browser testing.

## Author

Victory
