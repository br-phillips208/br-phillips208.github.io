# Benjamin Phillips — Portfolio Website

A clean, minimal portfolio site with tailored resume pages, built for GitHub Pages hosting.

---

## Files

| File | URL (after setup) | Purpose |
|---|---|---|
| `index.html` | `yoursite.com/` | Main portfolio — public facing |
| `hospitality.html` | `yoursite.com/hospitality` | Tailored resume — restaurants & hospitality |
| `enablement.html` | `yoursite.com/enablement` | Tailored resume — enablement & L&D roles |
| `support-leadership.html` | `yoursite.com/support-leadership` | Tailored resume — support & CX leadership |

The three resume pages are **not linked from the main site** — share the URLs directly when applying.

---

## How to Publish on GitHub Pages (Free)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the **+** icon in the top right and choose **New repository**
2. Name it exactly: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload your files
1. On the repository page, click **Add file** > **Upload files**
2. Drag and drop all 5 files:
   - `index.html`
   - `hospitality.html`
   - `enablement.html`
   - `support-leadership.html`
   - `README.md`
3. Scroll down and click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository **Settings** (tab at the top)
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and keep **/ (root)**
5. Click **Save**

### Step 5 — Wait ~2 minutes, then visit your site
Your portfolio will be live at: `https://yourusername.github.io`

---

## Your Resume URLs

Once live, share these links when applying:

- **Restaurants / Hospitality:** `https://yourusername.github.io/hospitality.html`
- **Enablement roles:** `https://yourusername.github.io/enablement.html`
- **Support Leadership:** `https://yourusername.github.io/support-leadership.html`

These pages are not linked from your main portfolio, so they're only findable if you share the direct link.

---

## Updating Your Site

To update any page later:
1. Go to your GitHub repository
2. Click the file you want to edit
3. Click the pencil icon (Edit)
4. Make your changes and click **Commit changes**

Changes go live within about 60 seconds.

---

## Adding Photos

When you have photos ready, swap out the emoji placeholders in `index.html`. Look for the `personal-card-img` divs in the Personal section and replace the emoji content with an `<img>` tag:

```html
<img src="your-photo.jpg" alt="Trail running in Idaho" style="width:100%; height:100%; object-fit:cover;">
```

Upload your photos to the GitHub repository the same way you uploaded the HTML files.

---

## Custom Domain (Optional)

If you want a custom domain like `benjaminphillips.com`:
1. Buy a domain from a registrar (Namecheap, Squarespace Domains, etc.)
2. In GitHub Pages settings, add your custom domain
3. Update your domain's DNS settings as instructed by GitHub

GitHub has a step-by-step guide at: `docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site`
