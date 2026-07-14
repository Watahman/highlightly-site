# Highlightly GitHub Pages website

A static landing page for Highlightly, ready to publish with GitHub Pages.

## Included

- Product landing page
- Features and workflow
- Free and Plus pricing
- Privacy policy
- Terms of use
- Refund policy
- Responsive design
- No backend or database required

## Before publishing

Use search and replace in all files for:

1. `YOUR_EMAIL@example.com`
   - Replace this with your real support email.

2. `YOUR_EXTENSION_STORE_URL`
   - Replace this with the public Chrome Web Store, Edge Add-ons, Firefox Add-ons, or installation-page link.
   - While the extension is not published yet, you can temporarily change the button to `href="#"`.

3. `REPLACE_WITH_DATE`
   - Replace this with the date on which you publish the policies, for example `15 July 2026`.

Also check that the price, trial period, feature limits, refund period, and payment description match your actual product setup.

## Publish with GitHub Pages

1. Create a new public GitHub repository, for example `highlightly-site`.
2. Upload all files from this folder to the root of the repository.
3. Open the repository on GitHub.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**.
7. Save the settings.
8. GitHub will provide a public URL similar to:
   `https://YOUR_GITHUB_USERNAME.github.io/highlightly-site/`

You can then use that public URL in Stripe.

## Local preview

Open `index.html` directly in your browser, or run a simple local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Important

The included legal pages are practical templates, not legal advice. Review them and adapt them to your actual business, location, payment flow, and data practices before publishing.
