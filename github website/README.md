# Eleanor K. MacDonald — Academic Website

A personal academic website for Eleanor K. MacDonald, PhD student in Biology at Temple University. Built with hand-coded HTML, CSS, and JavaScript — no frameworks, no dependencies.

## 🌐 Live Site

Once deployed, your site will be available at: `https://yourusername.github.io`

---

## 📁 Site Structure

```
├── index.html            → Home page
├── about.html            → About & bio (with link to CV)
├── research.html         → Research themes & projects
├── publications.html     → Publications list
├── gallery.html          → Photos & fieldwork gallery
├── contact.html          → Contact info, links & CV download
├── MacDonald_CV_2026.pdf → Academic CV (PDF)
├── css/
│   └── style.css         → All styles
├── js/
│   └── main.js           → Navigation, animations, lightbox
├── Photos/               → All photographs
└── README.md             → This file
```

---

## 🚀 How to Deploy on GitHub Pages (Free)

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com) and click **Sign up**
2. Choose a username (this becomes part of your URL: `username.github.io`)
3. Use your Temple email or personal email
4. Verify your email address

### Step 2: Create a New Repository
1. Click the **+** button in the top right → **New repository**
2. Name it exactly: `yourusername.github.io` (replace "yourusername" with your actual GitHub username)
   - For example, if your username is `emacdonald`, name it `emacdonald.github.io`
3. Keep it **Public**
4. Do NOT check "Add a README file" (we already have one)
5. Click **Create repository**

### Step 3: Upload Your Website Files
1. On your new repository page, click **"uploading an existing file"** (or drag & drop)
2. Drag ALL the files and folders from your `Website Creation Materials` folder:
   - All `.html` files
   - `MacDonald_CV_2026.pdf`
   - The `css/` folder
   - The `js/` folder
   - The `Photos/` folder
   - This `README.md`
3. Type a commit message like "Initial website upload"
4. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to your repository's **Settings** tab
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Select the **main** branch and **/ (root)** folder
5. Click **Save**
6. Wait 1-2 minutes, then visit `https://yourusername.github.io`

### 🎉 Your site is live!

---

## ✏️ How to Update Your Website

### Editing Content
1. Go to your repository on GitHub
2. Click on the file you want to edit (e.g., `publications.html`)
3. Click the **pencil icon** (Edit this file)
4. Make your changes
5. Click **Commit changes**
6. Your site will update automatically in ~1 minute

### Updating Your CV PDF
Whenever you update your CV, simply replace `MacDonald_CV_2026.pdf` in your repository with your updated PDF file (keeping the same filename, or updating the link target in `contact.html` and `about.html`).

### Adding New Photos
1. Upload new photos to the `Photos/` folder in your repository
2. Edit `gallery.html` to add new gallery items using this template:
```html
<div class="gallery-item" data-category="birds">
  <img src="Photos/your-new-photo.jpg" alt="Description of the photo">
  <div class="gallery-caption">Caption text</div>
</div>
```

---

## 🎨 Customizing the Design

### Changing Colors
Open `css/style.css` and edit the CSS custom properties at the top:
```css
:root {
  --color-primary: #2D4A3E;      /* Main green */
  --color-accent: #B8860B;       /* Gold accent */
  --color-cream: #FAF8F5;        /* Background cream */
}
```

### Changing Fonts
The site uses free Google Fonts. To change them, update the `<link>` tag in each HTML file's `<head>` and the font variables in `style.css`.

---

## 🌍 Adding a Custom Domain (Optional)

If you want a custom domain like `eleanormacdonald.com`:

1. Buy a domain from Namecheap, Google Domains, or similar (~$10-12/year)
2. In your GitHub repository **Settings → Pages**, enter your custom domain
3. At your domain registrar, add these DNS records:
   - A record: `185.199.108.153`
   - A record: `185.199.109.153`
   - A record: `185.199.110.153`
   - A record: `185.199.111.153`
   - CNAME record: `www` → `yourusername.github.io`
4. Check "Enforce HTTPS" in GitHub Pages settings
5. Wait up to 24 hours for DNS to propagate

---

Built with ❤️ using HTML, CSS, and vanilla JavaScript. No frameworks. No dependencies. No monthly fees.
