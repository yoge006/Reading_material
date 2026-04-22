# Bahdanau Attention — Visual Essay

A single-page visual explanation of how Bahdanau (additive) attention forms a soft alignment matrix between source and target sequences.

## 🚀 Deploy to GitHub Pages

### Option 1: Quickest (drag & drop)

1. Create a new repository on GitHub (e.g., `bahdanau-attention`).
2. Upload **`index.html`**, **`bahdanau_attention.svg`**, and **`README.md`** to the repo root.
3. Go to **Settings → Pages**.
4. Under **Source**, choose the `main` branch and `/ (root)` folder. Click **Save**.
5. Wait ~1 minute. Your site will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

### Option 2: From the command line

```bash
# 1. Initialise a local repo in this folder
git init
git add .
git commit -m "Initial commit: Bahdanau attention essay"

# 2. Create an empty repo on GitHub, then link it
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main

# 3. Enable GitHub Pages in repo Settings → Pages → Branch: main / root
```

### Option 3: Use the `docs/` folder

If you already have a repo and want this essay as a subsection:

1. Drop these files into a `docs/` folder at the repo root.
2. In **Settings → Pages**, choose `main` branch and `/docs` folder.

## 📁 File structure

```
bahdanau-site/
├── index.html                 # The page itself
├── bahdanau_attention.svg     # The diagram (referenced by index.html)
└── README.md                  # This file
```

Both files must sit **side-by-side** — the HTML references the SVG by its filename.

## 🎨 Customising

- **Colours** — edit the CSS variables at the top of `index.html` (look for `:root`).
- **Fonts** — currently uses Fraunces + Inter Tight + JetBrains Mono from Google Fonts.
- **Content** — the prose lives in clearly labelled `<section>` tags; edit in-place.

## 📝 License

Feel free to adapt and reuse.
