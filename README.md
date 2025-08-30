
# Outerpals CSAE Standards – GitHub Pages Setup

This folder serves the Outerpals Standards Against Child Sexual Abuse and Exploitation (CSAE) page at:
`https://<your-gh-pages-domain>/safety/`

## How to deploy

1. Create (or open) your GitHub Pages repository, typically:
   - **User/Org site:** `outerpals/outerpals.github.io`
   - **Project site:** enable Pages in repo settings and choose the branch/folder

2. Copy the `safety/` folder from this package into the repository root.

3. Commit and push:
   ```bash
   git add safety
   git commit -m "Add CSAE Standards page"
   git push
   ```

4. Your page will be available at:
   - User/Org site: `https://outerpals.github.io/safety/`
   - If using a custom domain, e.g. `outerpals.app`, at: `https://outerpals.app/safety/`

## Optional
- If you want to maintain a separate homepage, keep it as is; this `safety/` subfolder will not interfere.
- To update the "Last updated" line, edit `safety/index.html`.
