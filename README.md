# GitHub Deployment Workflow

This project demonstrates how to use GitHub Actions to automatically deploy a static website to GitHub Pages whenever the `index.html` file is changed.

## 📄 Project Structure

- `index.html` — Simple HTML file that says "Hello, GitHub Actions!"
- `.github/workflows/deploy.yml` — GitHub Actions workflow file that handles automatic deployment.
- `README.md` — This file explaining the project.

## 🚀 How It Works

- Every time you push changes to the `main` branch **and** the `index.html` file is modified, the GitHub Action will trigger.
- The workflow:
  1. Checks out the repository code.
  2. Prepares for deployment.
  3. Uploads the updated `index.html` as an artifact.
  4. Deploys it to GitHub Pages.

## 🌐 Live Website

Once deployed, you can view the website at: [https://zealp25.github.io/gh-deployment-workflow/](https://zealp25.github.io/gh-deployment-workflow/)

## ⚙️ Setup Instructions (for reference)

1. Create a GitHub repository.
2. Add an `index.html`, `README.md`, and a GitHub Actions workflow at `.github/workflows/deploy.yml`.
3. Enable GitHub Pages under repository **Settings** → **Pages** → **Source: GitHub Actions**.
4. Clear any **Custom Domain** unless you have your own domain.

## 📚 Additional Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
