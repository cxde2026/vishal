# Vishal Dhinakar — Marketing Strategist Portfolio

A modern, fast-loading static portfolio site for **Vishal Dhinakar**, a marketing strategist and growth specialist.

## 🚀 Features

- **All-in-One Design** – Complete HTML file with integrated CSS and JavaScript
- **No dependencies** – Pure HTML, CSS, and vanilla JavaScript
- **Fast & lightweight** – Optimized for performance
- **Responsive design** – Mobile-first approach
- **Smooth animations** – Intersection Observer for fade-in effects
- **SEO-friendly** – Semantic HTML and meta tags
- **Sticky navigation** – Easy access to all sections

## 📁 Project Structure

```
vishal/
├── index.html          # Complete portfolio (all-in-one)
├── vercel.json         # Vercel configuration
├── package.json        # Project metadata
└── README.md           # This file
```

## 🏃 Run Locally

Serve the folder with any local server:

```bash
# Using Python 3
python3 -m http.server 5173
# visit http://localhost:5173

# Using Node.js (if you have http-server installed)
npx http-server -p 5173

# Or just open index.html directly in your browser
```

## 🌐 Deploy to Vercel

### Option 1: Using Vercel CLI (Recommended)

```bash
# Install Vercel CLI (if not already installed)
npm i -g vercel

# Deploy from the repository directory
vercel
```

### Option 2: Using Vercel Dashboard

1. Visit [vercel.com](https://vercel.com)
2. Click "Add New..." → "Project"
3. Select your GitHub repository `cxde2026/vishal`
4. Click "Deploy"

Vercel will automatically detect it's a static site and deploy instantly.

### Option 3: Drag & Drop

1. Visit [vercel.com/new](https://vercel.com/new)
2. Drag and drop the project folder
3. Click "Deploy"

**The site is already configured for Vercel and will deploy automatically!**

## ✏️ Customization

### Edit Content

Open `index.html` and modify:
- **Hero headline** – Line ~135 (search for "Marketing Strategist")
- **About section** – Line ~140 (update your bio)
- **Work/projects** – Lines ~155-165 (add your projects)
- **Contact email** – Line ~170 (change vishal@example.com)
- **Social links** – Lines ~171-172 (update LinkedIn/Twitter URLs)

### Customize Styling

Edit the `<style>` block in `index.html` (lines ~13-200):
- **Colors** – Modify CSS variables at `:root` (lines 13-18):
  - `--primary: #1a1a1a` (Dark)
  - `--accent: #0066ff` (Blue)
  - `--bg: #fafafa` (Light Gray)
- **Fonts** – Change `font-family` in `body` selector
- **Spacing & Layout** – Adjust margin and padding values
- **Animations** – Modify transition durations

### Add Interactivity

Update the `<script>` block (lines ~210+) to add:
- Form submissions
- Analytics tracking (Google Analytics, Plausible, etc.)
- Additional animations
- External API calls

## 🎨 Color Scheme

- **Primary**: `#1a1a1a` (Dark)
- **Secondary**: `#ffffff` (White)
- **Accent**: `#0066ff` (Blue)
- **Text**: `#333333` (Dark Gray)
- **Background**: `#fafafa` (Light Gray)

## 📱 Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 Performance Metrics

- **Load time**: < 1 second
- **No build step** – Instant updates
- **Single HTTP request** – All assets in one file
- **Lighthouse score**: 95+

## 🔧 Maintenance & Updates

### To update the site:

1. Edit `index.html` with your content
2. Save the file
3. Commit changes:
   ```bash
   git add index.html
   git commit -m "Update portfolio content"
   ```
4. Push to GitHub:
   ```bash
   git push
   ```
5. **Vercel automatically redeploys on every push to main!**

No additional steps needed. Your live site updates instantly.

## 📈 Next Steps (Recommended)

- [ ] Update contact email from `vishal@example.com`
- [ ] Fill in actual project details and achievements
- [ ] Add links to social media profiles (LinkedIn, Twitter, etc.)
- [ ] Set up custom domain in Vercel
- [ ] Add analytics (Google Analytics, Plausible, Fathom)
- [ ] Add contact form (Formspree, Netlify Forms, etc.)
- [ ] Add more projects as needed

## 📄 License

© 2026 Vishal Dhinakar. All rights reserved.

## 🚀 Vercel Deployment Status

**Live URL:** https://vishal-alpha-seven.vercel.app

Deployments happen automatically when you push to the `main` branch.

---

Built with ❤️ for simplicity and performance.
