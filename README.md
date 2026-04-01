# Kaoru Website (Quarto)

## Quick Start
1. Install Quarto: https://quarto.org/
2. Preview locally:
   ```bash
   quarto preview
   ```
3. Initialize git & push to GitHub (main branch).
4. In GitHub → Settings → Pages → Source = GitHub Actions.
5. If you use a custom domain, commit `CNAME` with your domain and set DNS.

## Update cycle
- Update `references/ref.bib` from Zotero.
- Add latest talks PDFs under `talks/YYYY-MM-venue/`.
- Commit & push → auto deploy.
