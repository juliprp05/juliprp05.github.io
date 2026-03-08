# Language Studies Portfolio & Lesson Plans

This repository contains a static, personal portfolio website highlighting studies in Spanish and English as a foreign or second language. The site also includes a comprehensive EFL (English as a Foreign Language) lesson plan focused on exploring myths and legends, designed using Communicative Language Teaching (CLT) and Task-Based Language Teaching (TBLT) principles.

## Deployment to GitHub Pages

This project is configured to be automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the `main` branch.

### Prerequisites for GitHub Pages

To ensure the automatic deployment works correctly, verify the following settings in your GitHub repository:

1. Go to your repository on GitHub.
2. Click on the **Settings** tab.
3. In the left sidebar, click on **Pages**.
4. Under "Build and deployment", select **GitHub Actions** as the "Source".

Once this is set up, any commit to the `main` branch will trigger the `.github/workflows/static.yml` workflow, and your portfolio will be published to your `<username>.github.io/<repository-name>` URL.

## Local Development

To view the site locally before pushing:

1. Clone the repository.
2. Open a terminal in the root directory.
3. Run a local HTTP server. For example, using Python:
   ```bash
   python -m http.server
   ```
4. Open your browser and navigate to `http://localhost:8000`.
