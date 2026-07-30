# Up Stream Aerial Website

This folder is ready for GitHub Pages.

## Before publishing

Open `index.html` and replace:

- `YOUR-EMAIL@example.com` with your real business email
- `(503) 555-0123` with your real business phone number
- `+15035550123` with your phone number using only country code and digits

The contact form uses FormSubmit. The first test submission will send a confirmation email to the address you enter.

## Upload to GitHub

1. Create a new public repository on GitHub.
2. Click **Add file** then **Upload files**.
3. Upload:
   - `index.html`
   - `style.css`
   - `script.js`
   - the entire `assets` folder
4. Click **Commit changes**.
5. Open the repository's **Settings**.
6. Select **Pages**.
7. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
8. Save.

GitHub will display your website address after deployment.

## Connect your domain

In the GitHub Pages settings, enter your custom domain. GitHub will show the DNS records to add through the company where you purchased your domain.

## Add portfolio photos

The current portfolio panels are styled placeholders.

To use your own photos:

1. Put your photos inside `assets`.
2. In `style.css`, find `.portfolio-one`, `.portfolio-two`, `.portfolio-three`, or `.portfolio-four`.
3. Replace the existing `background:` property with:

```css
background:
  linear-gradient(to top, rgba(4,20,31,.80), transparent 60%),
  url("assets/your-photo-name.jpg") center / cover no-repeat;
```

Keep photo file names lowercase and avoid spaces.
