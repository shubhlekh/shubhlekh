# SHUBHLEKH

A clean, professional personal blog website.

## Files Structure

```
shubhlekh/
├── index.html              ← Homepage (list of articles)
├── about.html              ← About page
├── css/
│   └── styles.css          ← All design styles
├── articles/
│   ├── the-quiet-power-of-writing.html
│   ├── starting-fresh.html
│   └── why-i-write.html
└── README.md               ← This file
```

## How to Publish Online for Free (Recommended)

### Option 1: GitHub Pages (Best & Permanent)

1. Go to [github.com](https://github.com) and create a free account.
2. Click **New repository**.
3. Name it `shubhlekh` (or any name you like).
4. Make it **Public**.
5. Click **Create repository**.
6. Click **uploading an existing file** and upload **all** the files and folders from this `shubhlekh` folder.
7. After upload, go to **Settings → Pages**.
8. Under "Source", select **Deploy from a branch**.
9. Choose branch **main** and folder **/ (root)**.
10. Click **Save**.

Your website will be live in 1–2 minutes at:  
`https://YOUR-USERNAME.github.io/shubhlekh`

### Option 2: Netlify (Even simpler)

1. Go to [netlify.com](https://www.netlify.com) and sign up free.
2. Drag and drop the entire `shubhlekh` folder onto the Netlify dashboard.
3. Your site is live instantly with a free URL.

---

## How to Add a New Article

1. Copy any existing file inside the `articles/` folder (for example `why-i-write.html`).
2. Rename the copy to something like `my-new-article.html`.
3. Open the new file and change:
   - The `<title>`
   - The date and category in the `.meta` div
   - The `<h1>` title
   - The entire content inside `.article-content`
4. Save the file.
5. Open `index.html`.
6. Copy one of the existing `<article class="article-card">...</article>` blocks.
7. Paste it at the top of the `.articles-grid` section.
8. Update the title, date, excerpt, and the two links so they point to your new file (`articles/my-new-article.html`).

That’s it! Your new article will appear on the homepage.

---

## Customization Tips

- To change the main color, edit the `--accent` value in `css/styles.css`.
- To change the site name, search and replace “SHUBHLEKH” in the HTML files.
- You can delete the sample articles and replace them with your own.

Enjoy writing!
