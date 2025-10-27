# 1342 Drexel Association Website

A clean, modern website for the 1342 Drexel Association condominium in Miami Beach, Florida.

## Setup for GitHub Pages

### Initial Setup

1. Initialize git repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: 1342 Drexel Association website"
   ```

2. Create a new repository on GitHub (e.g., `1342drexel-website`)

3. Add the remote and push:
   ```bash
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

### Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select the `main` branch
5. Click **Save**
6. Your site will be published at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Important: Add Your Google Drive Link

Before deploying, you need to update the Google Drive link in `index.html`:

1. Open `index.html`
2. Find the line with `<a href="#" class="btn btn-primary"` (around line 38)
3. Replace the `#` with your actual Google Drive link
4. Commit and push the changes

## Customization

- **Colors**: Edit the CSS variables in `styles.css` at the top of the file
- **Content**: Modify `index.html` to update text and contact information
- **Images**: Replace images in the `images/` folder with your own

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── images/             # Image assets
│   ├── drexel.png
│   └── drexel-final.jpg
└── README.md           # This file
```

## Support

For issues or questions about the website, contact the board at president@1342drexel.com
