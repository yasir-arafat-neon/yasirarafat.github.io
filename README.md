# Yasir Arafat — Portfolio

A responsive, static portfolio website built with HTML, CSS and vanilla JavaScript. No build step or framework is required.

## Run locally

Open `index.html` in a browser, or run a local static server:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy

### GitHub Pages
1. Push these files to your public repository (for example, `yasir-arafat-neon/yasirarafat.github.io`).
2. In **Settings → Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`.
3. Save. GitHub Pages will publish the site at `https://yasir-arafat-neon.github.io/`.

### Vercel
1. Import the GitHub repository into Vercel.
2. Choose **Other** as the framework preset if prompted.
3. Leave Build Command and Output Directory empty (or use `.` as the output directory).
4. Deploy.

### Netlify
1. Import the GitHub repository into Netlify, or drag and drop this project folder.
2. Leave Build command empty and set Publish directory to `.`.
3. Deploy.

## Customize
- Edit your biography, email, social links and project descriptions in `index.html`.
- Update colours and responsive layout in `style.css`.
- Navigation behavior and current year are in `script.js`.

All project links currently point to public repositories under `yasir-arafat-neon`. Verify/update contact and social URLs before publishing.
