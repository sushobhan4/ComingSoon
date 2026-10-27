# KebabZilla — Coming Soon Page

Clean, responsive, pure HTML & CSS holding page for [kebabzilla.in](https://kebabzilla.in).

## Features
- **Zero JavaScript**: Ultra-fast loading, lightweight, and completely accessible.
- **Responsive Design**: Mobile-first layout with smooth CSS micro-animations.
- **Dark Brand Theme**: Charcoal obsidian background (`bgImage.jpg`) with warm ember/amber glowing accents.
- **OpenGraph & SEO Ready**: Includes social card sharing metadata and mobile viewport controls.

## Deployment Options

### Option 1: GitHub Pages
1. Push this repository to GitHub (`https://github.com/sushobhan4/ComingSoon.git`).
2. Go to **Repository Settings** > **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch** (`main` / root `/`).
4. Under **Custom domain**, enter `kebabzilla.in` and enable HTTPS.

### Option 2: Firebase Hosting
1. Create the holding site in your Firebase project:
   ```bash
   firebase hosting:sites:create kebabzilla-holding
   ```
2. Deploy directly:
   ```bash
   firebase deploy --only hosting
   ```
3. In [Firebase Console](https://console.firebase.google.com/), add `kebabzilla.in` to `kebabzilla-holding`.
