# Setup Guide

## Quick Deploy to GitHub Pages

### 1. Create Repository
1. Go to [github.com/new](https://github.com/new)
2. Repository name: `blob-tracker`
3. Make it **Public**
4. Check "Add a README file"
5. Click "Create repository"

### 2. Upload Files
1. Click "Add file" → "Upload files"
2. Drag and drop these files:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `.gitignore`
3. Commit message: "Initial commit"
4. Click "Commit changes"

### 3. Enable GitHub Pages
1. Go to repository **Settings**
2. Scroll to **Pages** section (in sidebar)
3. Under "Source":
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**

### 4. Done!
After 1-2 minutes, your site will be live at:
```
https://YOUR-USERNAME.github.io/blob-tracker/
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## Updating

To update the tracker:
1. Edit `index.html` on GitHub (click the file → pencil icon)
2. Make changes
3. Commit
4. Changes go live in ~1 minute

## Custom Domain (Optional)

Want to use your own domain?

1. Buy a domain (Namecheap, Google Domains, etc.)
2. In your repo: Settings → Pages → Custom domain
3. Enter your domain: `blobtracker.yourdomain.com`
4. Add DNS records at your domain provider:
   ```
   CNAME: blobtracker → YOUR-USERNAME.github.io
   ```
5. Enable "Enforce HTTPS"

## Local Testing

Want to test locally before deploying?

**Option 1: Just open the file**
- Double-click `index.html`
- Works in most browsers

**Option 2: Local server (if having issues)**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx serve
```

Then open: `http://localhost:8000`

## Sharing

Once deployed, share your tracker:
- Direct link: `https://YOUR-USERNAME.github.io/blob-tracker/`
- QR code: Use any QR generator with your URL
- Social: Tag @touchcollective

## Troubleshooting

**Camera not working?**
- Must use HTTPS (GitHub Pages does this automatically)
- Chrome/Firefox work best
- Check browser permissions

**404 Error?**
- Wait 2-5 minutes after enabling Pages
- Check repository is Public
- Verify files are in root directory

**Changes not showing?**
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Clear browser cache
- Wait 1-2 minutes for GitHub to rebuild

**Performance issues?**
- Lower resolution scale
- Enable frame skip
- Try Chrome (fastest)

## Support

Issues? Create a [GitHub issue](https://github.com/YOUR-USERNAME/blob-tracker/issues)

Made with touch collective
