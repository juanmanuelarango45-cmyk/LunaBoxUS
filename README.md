# LunaBox landing page

A responsive, static landing page for LunaBox. All three **Join the waitlist** buttons open the supplied Google Form in a new tab. No backend or environment variables are needed.

## Publish with GitHub + Netlify

1. Create a new GitHub repository (for example, `lunabox-landing`).
2. Upload `index.html`, `styles.css`, `script.js`, and `netlify.toml` to the **root** of the repository, then commit.
3. In Netlify, select **Add new project → Import an existing project → GitHub**. Authorize GitHub and select your repository.
4. Build command: **leave blank**. Publish directory: **`.`** (the repository root). Deploy.
5. Test the live page on desktop and mobile, and click **Join the waitlist** to verify your Google Form is publicly accessible.

## Customize

- Text and product descriptions: `index.html`
- Colors, fonts, spacing and mobile layout: `styles.css`
- Waitlist URL: replace all occurrences of the Google Forms URL in `index.html`.

Product-box illustrations are created with CSS; no image licenses or external image assets are required. Google Fonts are loaded from Google's CDN.
