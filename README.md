# Healtheon website

The whole website is in `index.html`. Fonts, the hero video and stock photos load from Google Fonts and Pexels; the logo and teammate portraits are built into the file.

## Put it live on GitHub Pages

1. On github.com, create a new repository (for example `healtheon-website`). Make it **Public**.
2. On the new repository's page, click **uploading an existing file**.
3. Drag in `index.html`, `404.html` and this `README.md`, then click **Commit changes**.
4. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, **Branch** to `main` and the folder to `/ (root)`. Click **Save**.
5. Wait one or two minutes, then refresh the Pages settings. The live address appears at the top, in the form `https://<your-username>.github.io/healtheon-website/`.

## Updating the site later

Upload a new `index.html` to the same repository and commit. GitHub Pages republishes it within a minute or two.

## Custom domain (optional)

In **Settings → Pages → Custom domain**, enter the domain (for example `www.healtheon.ai`) and follow GitHub's DNS instructions.

## Before you share it publicly

- **Forms are not connected yet.** The demo request form and the case study form validate input but don't send anything; they show a "Review build" note. To connect them, open `index.html`, search for `FORM_ENDPOINT` and `CASE_STUDY_ENDPOINT`, and paste your form service URLs between the quotes (for example from HubSpot, Formspree or Basin).
- **Legal pages are placeholders.** The privacy policy, terms and cookie policy pages say the full text will be published later.
- **Case studies are illustrative scenarios**, labelled as such on the page.
