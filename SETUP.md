# Setup Guide - web-blob-tracker

## ✅ Already Deployed!

Your tracker is at:
```
https://YOUR-USERNAME.github.io/web-blob-tracker/
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## Enable GitHub Pages

If not already enabled:

1. Go to your repo: `github.com/YOUR-USERNAME/web-blob-tracker`
2. Click **Settings**
3. Scroll to **Pages** section (in sidebar)
4. Under "Source":
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

Wait 1-2 minutes, then visit your live site!

## Updating the Tracker

To make changes:

1. Edit `index.html` on GitHub (click file → pencil icon)
2. Make your changes
3. Commit
4. Changes go live in ~1 minute

## Update Links in README

Don't forget to update `README.md`:
- Replace `yourusername` with your actual GitHub username
- This makes all the links work correctly

## Custom Domain (Optional)

Want `blobtracker.yourdomain.com`?

1. Buy a domain
2. Settings → Pages → Custom domain
3. Enter: `blobtracker.yourdomain.com`
4. Add CNAME record at your domain provider:
   ```
   CNAME: blobtracker → YOUR-USERNAME.github.io
   ```
5. Enable "Enforce HTTPS"

## Local Testing

**Just open the file:**
- Double-click `index.html`
- Works in most browsers

**Or use a local server:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx serve
```

Then open: `http://localhost:8000`

## Sharing Your Tracker

Once live, share it:
- Direct link: `https://YOUR-USERNAME.github.io/web-blob-tracker/`
- Social media
- Tag @touchcollective

## Troubleshooting

**Camera not working?**
- Must use HTTPS (GitHub Pages does this)
- Chrome/Firefox work best
- Check browser permissions

**404 Error?**
- Wait 2-5 minutes after enabling Pages
- Check repository is Public
- Verify `index.html` is in root folder

**Changes not showing?**
- Hard refresh: Ctrl+Shift+R (Win) or Cmd+Shift+R (Mac)
- Clear browser cache
- Wait 1-2 minutes

**Performance issues?**
- Lower resolution scale
- Enable frame skip
- Use Chrome (fastest)

## File Structure

Your repo should look like:
```
web-blob-tracker/
├── index.html      # Main app
├── README.md       # Documentation
├── LICENSE         # MIT license
└── SETUP.md        # This file
```

## Support

Issues? Create a [GitHub issue](https://github.com/YOUR-USERNAME/web-blob-tracker/issues)

Made with touch collective
