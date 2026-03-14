# Personal Website

Simple personal website for Sotirios Lympakis, inspired by a minimal academic profile layout.

## Files

- `index.html` main page
- `styles.css` site styling
- `.github/workflows/deploy.yml` automatic GitHub Pages deployment

## Deploy permanently with GitHub Pages

1. Create a new GitHub repository (for example: `profile-website`).
2. Push this folder to the `main` branch.
3. In GitHub: **Settings → Pages → Source**, select **GitHub Actions**.
4. The workflow will deploy automatically after each push.
5. Your site URL will be:
   - `https://<your-username>.github.io/<repo-name>/` (project site)
   - or `https://<your-username>.github.io/` if the repo name is `<your-username>.github.io`.

## Optional: custom domain

If you have a domain, add a `CNAME` file in the project root with your domain name (example: `sotirios.dev`) and configure DNS records at your domain provider to point to GitHub Pages.

## Customize

- Replace `your-email@example.com` in `index.html` with your real email.
- Update the About and Selected Work sections with your own text and links.