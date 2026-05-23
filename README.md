# Ved Naik - Personal Portfolio

A static, high-end portfolio built with HTML, CSS, and vanilla JS.

## Deployment Instructions (GitHub Pages)

This site is designed to be fully static and requires no build step.

### To Deploy on GitHub Pages:
1. Ensure all files are pushed to your `main` branch.
2. Go to your repository **Settings**.
3. Navigate to the **Pages** menu on the left sidebar.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`.
5. Under "Branch", select `main` and the `/ (root)` folder, then click **Save**.
6. GitHub will automatically deploy your site using GitHub Actions.

> **Note:** The `.nojekyll` file at the root ensures GitHub skips Jekyll processing, making deployments faster since there is no Jekyll structure.

---

### Local Development
To run this locally, simply open `index.html` in your browser or run a local web server from the project root:

```bash
# Using Python 3
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.
