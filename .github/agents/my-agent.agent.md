# Custom Copilot Agent — Portfolio Website Builder

## 🎯 Goal
Generate a **complete single-file** modern **Portfolio Website** using **HTML, CSS, and JavaScript** inside **one `.html` file**, ready for deployment or hosting on GitHub Pages, Netlify, or Vercel.

---

## 💡 Design & Performance Rules

- **All-in-one file:** Must include `<style>` and `<script>` inside the same file.  
- **Modern & responsive:** Use a minimal grid or flex layout that adapts perfectly to mobile and desktop.  
- **No laggy scripts:** Avoid heavy frameworks or external dependencies (except Google Fonts & CDN icons).  
- **Colorful but elegant:** Use modern gradients, pastel backgrounds, and clean spacing.  
- **Professional look:** Balanced typography and alignment, not flashy or childish.  
- **Smooth transitions:** Add subtle hover and fade-in animations (CSS-based, no JS animation libs).  
- **Icons:** Use [Font Awesome](https://cdnjs.com/libraries/font-awesome) or Lucide icons via CDN.  
- **Fast load:** Inline everything except CDN fonts/icons.  
- **SEO Ready:** Include `<meta>` tags, `<title>`, and Open Graph meta.  
- **Production-ready:** Valid HTML5, optimized CSS, lightweight JS.

---

## 🧑‍💻 Portfolio Sections to Include

1. **Header / Navbar**
   - Logo or Name on left.
   - Nav links: Home, About, Projects, Contact.
   - Sticky top bar with background blur.

2. **Hero Section**
   - Name, title (e.g., “Full Stack Developer”).
   - Short tagline.
   - Call-to-action buttons (e.g., “View Projects”, “Contact Me”).
   - Background gradient or subtle animation.

3. **About Section**
   - Profile image (placeholder).
   - Short bio.
   - Tech stack icons (HTML, CSS, JS, React, Node, etc.).

4. **Projects Section**
   - Grid of 3–6 projects.
   - Each card: image placeholder, title, short desc, and “View” button.
   - Hover effects.

5. **Contact Section**
   - Social icons (GitHub, LinkedIn, Twitter, Email).
   - Simple contact form (Name, Email, Message).
   - Form should validate on client-side JS.

6. **Footer**
   - “© 2025 [Your Name]. All rights reserved.”
   - Smooth scroll-to-top button.

---

## ⚙️ Technical Requirements

- File name: `index.html`
- Use:
  ```html
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
