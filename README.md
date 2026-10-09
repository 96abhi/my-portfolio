# Abhishek Singh — DevOps Portfolio

A responsive portfolio website for GitHub Pages, built with plain HTML, CSS, and JavaScript.

## Preview locally

No build tools are required. Open `index.html` in your browser, or start a simple local server:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish with GitHub Pages

1. Create a public repository named `devops-portfolio` at <https://github.com/new>.
2. Copy the files from this folder into the repository root.
3. Commit and push to the `main` branch:

   ```bash
   git add .
   git commit -m "Add DevOps portfolio website"
   git branch -M main
   git push -u origin main
   ```

4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then click **Save**.
7. Wait for deployment. The expected URL is:

   `https://96abhi.github.io/devops-portfolio/`

## Before publishing

- Replace `YOUR_EMAIL@example.com` in `index.html` with your professional email address.
- Update project cards with the direct URLs for the repositories you want to feature.
- Add a resume PDF to the repository if desired, and link it from the hero section.
- Verify experience dates and descriptions match your actual work.
- Do not upload passwords, access keys, Terraform state files, or other secrets.

## Files

```text
my-portfolio/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Featured projects

1. [Terraform + Docker](https://github.com/96abhi/terraform-docker) — Terraform-managed Docker resources.
2. [GitHub Actions CI/CD demo](https://github.com/96abhi/test-demo) — GitHub Actions workflow practice.
3. **Node.js + Jenkins Automation** — Add the direct repository link when the project repository is ready. The website currently links this card to the GitHub profile.

## Built with

- HTML5
- CSS3 (responsive layout)
- Vanilla JavaScript
- GitHub Pages
