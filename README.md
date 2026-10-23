# Bert Lagare — Portfolio & OJT Landing Hub 🌐

An editorial-styled, responsive, high-performance landing page (Hub Page) crafted with **pure HTML & CSS**. Designed specifically to bridge visitors and recruiters to Bert Lagare's **Main Portfolio** and **OJT Practicum Blog**.

Designed to mirror the branding, typography (editorial serif + geometric sans), and signature deep forest green color palette from your Canva portfolio and GitHub Pages blog.

---

## 🚀 Features

- **Pure HTML5 & CSS3**: Zero build tools, zero dependencies, lightning-fast loading speed.
- **Dual Destination System**:
  1. **Button 1**: `View Main Portfolio` (Software engineering, machine learning, graphic design projects)
  2. **Button 2**: `Read OJT Blog` (324-hour NEMSU Information Office practicum report)
- **Editorial Design System**:
  - Warm linen/ivory canvas (`#faf8f5`)
  - Signature dark forest green (`#1b3524`)
  - Editorial serif typography (`DM Serif Display`) paired with clean modern sans (`Plus Jakarta Sans`)
  - Rounded pill buttons matching *"Let's Work Together"* and *"Read the Report"*
- **Fully Responsive & Accessible**:
  - Mobile-first layout with smooth collapsing grids
  - WCAG AA compliant contrast ratios and `:focus-visible` keyboard accessibility
  - `prefers-reduced-motion` support
- **Social Media Ready**: Built-in Open Graph metadata for rich link previews when sharing on LinkedIn, Discord, or messaging apps.

---

## 📁 Project Structure

```text
OJT_Page/
├── index.html        # Main landing page markup with clear URL paste sections
├── style.css         # Pure CSS styling, animations, and design tokens
├── assets/
│   └── profile.png   # Portrait photo with transparent alpha cutout
└── README.md         # Documentation & deployment guide
```

---

## ✏️ How to Customize Your Links

Open `index.html` in your code editor. The links have already been pre-filled with the URLs discovered from your screenshots:
- Portfolio: `https://nemsu-training.my.canva.site/bert-s-portfolio`
- OJT Blog: `https://baelagare.github.io/index.html`

If you ever need to change or update them, search for the comment blocks in `index.html`:

```html
<!-- ============================================================ -->
<!-- BUTTON 1: PASTE YOUR MAIN PORTFOLIO WEBSITE URL BELOW IN href -->
<!-- ============================================================ -->
<a href="PASTE_YOUR_PORTFOLIO_URL_HERE" class="btn btn-primary" ...>
  <span>View Main Portfolio</span>
</a>

<!-- ============================================================ -->
<!-- BUTTON 2: PASTE YOUR OJT BLOG WEBSITE URL BELOW IN href       -->
<!-- ============================================================ -->
<a href="PASTE_YOUR_OJT_BLOG_URL_HERE" class="btn btn-secondary" ...>
  <span>Read OJT Blog</span>
</a>
```

---

## 📸 Updating the Portrait Image

The page includes your photo in `assets/profile.png`. To replace it with any other photo:
1. Save your preferred image as `profile.png` inside the `assets/` folder.
2. The CSS automatically handles framing and responsive scaling.

---

## 🚢 How to Deploy to GitHub Pages

Deploying takes less than 2 minutes:

### Option 1: Using Git via Terminal / Command Prompt

1. Initialize git and commit your files:
   ```bash
   git init
   git add .
   git commit -m "feat: initial landing hub page"
   ```

2. Create a new repository on GitHub (e.g. named `OJT_Page` or `hub`).

3. Link and push to GitHub:
   ```bash
   git branch -M main
   git remote add origin https://github.com/baelagare/YOUR-REPO-NAME.git
   git push -u origin main
   ```

4. Turn on GitHub Pages:
   - Go to your repository on GitHub.
   - Click **Settings** (tab at the top).
   - In the left sidebar, click **Pages**.
   - Under **Build and deployment > Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and `/ (root)`.
   - Click **Save**.

Your landing page will be live at:
`https://baelagare.github.io/YOUR-REPO-NAME/`

---

### Option 2: Upload Directly on GitHub (No Git required)

1. Open [GitHub](https://github.com) and create a new repository.
2. Click **Upload an existing file**.
3. Drag and drop `index.html`, `style.css`, and the `assets/` folder.
4. Click **Commit changes**.
5. Go to **Settings** > **Pages** > Select `main` branch > Click **Save**.

---

&copy; 2026 Bert Lagare
