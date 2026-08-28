# Personal Website

Welcome to your personal website repository! This is a beautiful, modern, and fully customizable personal portfolio site.

## 🚀 Getting Started

Your website is live at: `https://reneegoodman.github.io`

GitHub Pages automatically deploys your site whenever you push changes to the `main` branch. No additional configuration needed!

## 📝 How to Customize Your Website

### 1. **Update Personal Information**

Edit `index.html` and update:
- **Name & Title**: Change "Renee Goodman" and "Developer • Designer • Creator" in the hero section
- **Email**: Update the email link in the Contact section
- **Social Links**: Replace placeholder GitHub, LinkedIn, and Twitter URLs with your actual profiles

### 2. **Customize Content Sections**

#### Hero Section (First Impression)
- Location: `<section id="home" class="hero">` in index.html
- Change the title, tagline, and introduction text
- Modify button text and links

#### About Section
- Location: `<section id="about" class="about">` in index.html
- Replace the about text with your bio
- Update the skills tags to match your expertise
- Add or remove skill tags as needed

#### Projects Section
- Location: `<section id="projects" class="projects">` in index.html
- Edit the three project cards to showcase your work
- For each project:
  - Update the project title
  - Write a description of what you built
  - Add relevant technology tags
  - Update the "Learn More" link to point to your project

#### Contact Section
- Location: `<section id="contact" class="contact">` in index.html
- Update all contact links with your actual information
- Add or remove social media links as needed

### 3. **Modify Colors & Styling**

Edit `styles.css` to change the appearance:

**Primary Color Scheme** (look for `--primary-color`):
```css
--primary-color: #6366f1;      /* Main accent color */
--secondary-color: #ec4899;    /* Secondary accent */
```

**Common Customizations**:
- Change hero gradient: Look for `.hero` background property
- Modify fonts: Update the `font-family` in the `body` selector
- Adjust spacing: Modify `padding` and `margin` values
- Change text colors: Update CSS color variables

### 4. **Navigation Menu**

The navigation links in the header correspond to sections in your page:
- Home → `#home`
- About → `#about`
- Projects → `#projects`
- Contact → `#contact`

Edit the `<ul class="nav-links">` in the header to add/remove navigation items.

## 📂 File Structure

```
reneegoodman.github.io/
├── index.html          # Main HTML file (content & structure)
├── styles.css          # CSS file (design & styling)
├── README.md           # This file
└── _config.yml         # GitHub Pages configuration (optional)
```

## 🎨 Template Features

✅ **Fully Responsive**: Works perfectly on desktop, tablet, and mobile  
✅ **Modern Design**: Clean, professional aesthetic with smooth animations  
✅ **Easy to Customize**: Simple HTML/CSS structure  
✅ **SEO Ready**: Proper meta tags and semantic HTML  
✅ **Performance**: Lightweight, no external dependencies  
✅ **Accessibility**: Semantic HTML and proper contrast ratios  

## 🔧 Making Your First Changes

1. **Edit Files**: Use GitHub's web editor (click the pencil icon) or clone locally
   ```bash
   git clone https://github.com/reneegoodman/reneegoodman.github.io.git
   cd reneegoodman.github.io
   ```

2. **Make Changes**: Edit `index.html` and `styles.css` with your information

3. **Commit & Push**: 
   ```bash
   git add .
   git commit -m "Update website content"
   git push origin main
   ```

4. **See Changes**: Wait 1-2 minutes, then visit your site (refresh if needed)

## 💡 Tips for Content

- **Projects**: Link to live demos or GitHub repositories
- **Skills**: Be honest about your expertise level
- **Bio**: Tell a story, not just a list of facts
- **Contact**: Make it easy for people to reach you
- **Keep it Fresh**: Update your site regularly with new projects and accomplishments

## 🌐 Advanced Customization

Want to add more features? Consider:
- Adding a blog section with multiple pages
- Implementing a contact form backend
- Adding more detailed project showcase pages
- Creating a separate `/projects` directory with project-specific pages
- Adding animation effects with JavaScript

## 📚 Resources

- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [GitHub Pages Docs](https://docs.github.com/en/pages)

## 🎯 Next Steps

1. ✏️ Update your name, bio, and contact information
2. 📝 Add your real projects and descriptions
3. 🎨 Customize colors to match your personal brand
4. 🔗 Add links to your social profiles and projects
5. 📱 Test on mobile to ensure everything looks great

Happy building! 🚀