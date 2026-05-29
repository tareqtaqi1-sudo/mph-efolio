# Publishing Your MPH E-Folio to GitHub Pages
## Step-by-Step Instructions for a Public Shareable URL

---

## What You Have

Your portfolio is a single file: **`index.html`**
This is all you need to publish. No backend, no database — it works entirely in the browser.

---

## Step 1 — Create a Free GitHub Account

1. Go to [github.com](https://github.com) and click **Sign up**
2. Choose a username (e.g., `tareq-taqiaddin` or similar professional name)
3. Complete email verification

---

## Step 2 — Create a New Repository

1. Once logged in, click the **+** icon (top-right) → **New repository**
2. Name the repository exactly: `mph-efolio`
   *(or any name you prefer — it will appear in your URL)*
3. Set visibility to **Public**
4. Check **"Add a README file"**
5. Click **Create repository**

---

## Step 3 — Upload Your Files

1. Inside your new repository, click **Add file** → **Upload files**
2. Drag and drop **`index.html`** from your computer into the upload area
3. If you have a professional photo ready, upload it too (name it `photo.jpg` or `photo.png`)
4. If you have an Amazon One Medical image, upload it (name it `ape-image.jpg`)
5. Scroll down and click **Commit changes**

---

## Step 4 — Add Your Photo to the Site (Optional, but Recommended)

Once you've uploaded your photo, open `index.html` in a text editor and find this block:

```html
<div class="photo-placeholder">
  <i class="fas fa-user-circle"></i>
  <strong>Add a professional photo of Tareq here.</strong>
  ...
</div>
```

Replace the entire `<div class="photo-placeholder">...</div>` block with:

```html
<img src="photo.jpg" alt="Tareq Taqiaddin" style="width:100%; border-radius:12px; box-shadow:0 4px 24px rgba(30,45,61,.15);" />
```

*(Change `photo.jpg` to whatever filename you used)*

---

## Step 5 — Add Your APE Image (Optional)

Find this block in `index.html`:

```html
<div class="ape-img-placeholder">
  ...
</div>
```

Replace the entire block with:

```html
<img src="ape-image.jpg" alt="Amazon One Medical — Applied Practice Experience" class="ape-banner" />
```

---

## Step 6 — Add Your LinkedIn URL

Find this in the Contact section:

```html
<span class="linkedin-placeholder">
  Add your LinkedIn URL here ...
</span>
```

Replace it with:

```html
<a href="https://linkedin.com/in/YOUR-PROFILE-NAME">linkedin.com/in/YOUR-PROFILE-NAME</a>
```

---

## Step 7 — Enable GitHub Pages

1. In your repository, click **Settings** (top tab row)
2. In the left sidebar, click **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, choose **main** and folder **/ (root)**
5. Click **Save**
6. Wait about 1–2 minutes

---

## Step 8 — Get Your Public URL

After saving, refresh the **Pages** settings page.
You will see a green banner that says:

> **Your site is live at:** `https://YOUR-USERNAME.github.io/mph-efolio/`

**That is your shareable, public URL.**

---

## Step 9 — Submit to Canvas

1. Copy your GitHub Pages URL (e.g., `https://your-username.github.io/mph-efolio/`)
2. Paste it into your Canvas submission field
3. Open the link in an incognito/private browser window to confirm it works publicly

---

## Updating the Site Later

If you need to make changes (add your photo, fix wording, etc.):

1. Edit `index.html` on your computer
2. Go back to your GitHub repository
3. Click on `index.html` → click the pencil ✏️ icon → paste in updated content → Commit
4. The live site updates within 1–2 minutes automatically

---

## Summary

| What | Where |
|------|-------|
| Your public URL | `https://YOUR-USERNAME.github.io/mph-efolio/` |
| File to edit | `index.html` |
| Photo filename expected | `photo.jpg` (or update the src in the HTML) |
| APE image filename expected | `ape-image.jpg` (or update the src in the HTML) |
| LinkedIn | Find `linkedin-placeholder` in index.html and replace |

---

*Questions? The GitHub Pages documentation is at docs.github.com/pages*
