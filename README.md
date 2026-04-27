# taum-call-notes

Static privacy policy page for GitHub Pages.

Project Pages URL format:
`https://<your-github-username>.github.io/github-page-privacy/`

## Publish

1. Push this repository to GitHub.
2. In GitHub, open `Settings -> Pages`.
3. Set `Build and deployment -> Source` to `GitHub Actions`.
4. Wait for the workflow to publish the site.

## Files

- `index.html` - privacy policy page
- `.nojekyll` - disables Jekyll processing
- `.github/workflows/pages.yml` - GitHub Pages deploy workflow

If you later want a custom domain, add a `CNAME` file with that domain name only.
