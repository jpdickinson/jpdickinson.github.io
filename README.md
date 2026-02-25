# Jayson Dickinson Portfolio Website

A professional portfolio website with integrated blog functionality, built for GitHub Pages.

## 🌟 Features

- **Professional Portfolio** - Showcase your professional projects, experience, and skills
- **Personal Blog** - Share personal updates, hobbies, and non-professional content
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI** - Clean, professional design with smooth animations and transitions

## 📁 Structure

```
├── index.html      # Main portfolio/homepage
├── blog.html       # Personal blog page
├── projects.html   # Detailed projects showcase
├── styles.css      # All styling
└── README.md       # This file
```

## 🎨 Pages

### 1. Homepage (index.html)
- Hero section with call-to-action
- About section with skills
- Project highlights (links to full projects page)
- Professional experience timeline
- Contact information

### 2. Projects Page (projects.html)
- Featured project spotlight
- Comprehensive list of all projects
- Technologies and skills overview
- Detailed project descriptions with impact metrics

### 3. Blog (blog.html)
- Personal blog posts
- Category filtering
- Blog post previews with tags
- Separate from professional content

## ✏️ Customization Guide

### Update Your Information

1. **Personal Details** - Replace "JP Dickinson" throughout all files with your name
2. **Contact Info** - Update email, LinkedIn, and GitHub links in the contact section
3. **About Section** - Edit the about text in [index.html](index.html#L38-L45)
4. **Skills** - Update skill tags in [index.html](index.html#L48-L57)

### Add Your Projects

Edit project cards in both:
- [index.html](index.html#L67-L120) - for project highlights
- [projects.html](projects.html#L27-L165) - for detailed project list

### Add Blog Posts

Add new blog post articles in [blog.html](blog.html#L28-L100) following this structure:

```html
<article class="blog-post">
  <div class="post-date">Date</div>
  <h2 class="post-title">Title</h2>
  <p class="post-excerpt">Excerpt...</p>
  <a href="#" class="read-more">Read More →</a>
  <div class="post-tags">
    <span class="tag-small">Tag1</span>
  </div>
</article>
```

### Color Scheme

Edit colors in [styles.css](styles.css#L9-L17):

```css
:root {
  --primary-color: #2563eb;
  --accent-color: #0ea5e9;
  /* ... more colors */
}
```

## 🚀 Deployment

This site is ready for GitHub Pages:

1. Push to your GitHub repository
2. Go to Settings → Pages
3. Set source to main branch
4. Your site will be live at `https://yourusername.github.io`

## 📝 Next Steps

1. Replace placeholder content with your actual information
2. Add your real projects with descriptions and links
3. Update contact information and social links
4. Write your first blog posts
5. Customize colors to match your personal brand
6. Add your professional photo/headshot (optional)

## 🔧 Technical Details

- Pure HTML/CSS (no build process required)
- Responsive design with CSS Grid and Flexbox
- Smooth scroll navigation
- Optimized for performance
- Works on all modern browsers

## 📞 Support

For questions or issues, refer to GitHub Pages documentation or web development resources.

---

Built with ❤️ for professional portfolio and personal expression
