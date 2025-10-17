# Personal Portfolio Website

A clean, minimalist portfolio website inspired by OpenAI's design aesthetic. Built for GitHub Pages to showcase your coding and machine learning projects.

## 🎨 Features

- **Minimalist Design**: Clean, modern UI with smooth animations
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile
- **Easy to Customize**: Clear placeholders and comments for quick editing
- **Smooth Navigation**: Scroll animations and interactive elements
- **GitHub Pages Ready**: Static HTML/CSS/JS - no build process needed

## 📝 How to Customize

All sections are marked with `<!-- EDIT -->` comments to make customization easy.

### 1. Basic Information (index.html)

Search for these comments and update:

- `<!-- EDIT: Add your name below -->` - Update your name and title
- `<!-- EDIT: Add your bio below -->` - Write your personal bio
- `<!-- EDIT: Update your social links below -->` - Add your GitHub, LinkedIn, email, etc.
- `<!-- EDIT: Replace with your photo -->` - Add your profile picture

### 2. Projects Section

Each project card looks like this:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Project Name</h3>
        <div class="project-links">
            <a href="your-github-repo" target="_blank">...</a>
            <a href="your-live-demo" target="_blank">...</a>
        </div>
    </div>
    <p class="project-description">Your description here...</p>
    <div class="tech-tags">
        <span class="tag">Python</span>
        <span class="tag">TensorFlow</span>
    </div>
</div>
```

**To add more projects**: Copy any `<div class="project-card">...</div>` block and paste it below the existing ones.

### 3. Research/Blog Posts

Update the date, title, and description:

```html
<article class="blog-card">
    <div class="blog-date">October 2024</div>
    <h3>Your Article Title</h3>
    <p>Your article description...</p>
    <a href="#" class="read-more">Read more →</a>
</article>
```

**To add more posts**: Copy and paste the entire `<article class="blog-card">...</article>` block.

### 4. Interactive Demos

Add your demo apps and visualizations:

```html
<div class="demo-card">
    <div class="demo-preview">
        <!-- Add a screenshot here -->
    </div>
    <div class="demo-content">
        <h3>Demo Name</h3>
        <p>Description...</p>
        <a href="demo-link" class="demo-btn">Launch Demo →</a>
    </div>
</div>
```

### 5. Goals & Roadmap

Update the three sections:
- **Current Focus**: What you're working on now
- **Next 3-6 Months**: Short-term goals
- **Long Term**: Future aspirations

Add or remove `<li>` items as needed:

```html
<ul class="roadmap-list">
    <li>Your goal here</li>
    <li>Another goal</li>
</ul>
```

### 6. Technologies You're Learning

Update the tech grid:

```html
<div class="tech-item">Python</div>
<div class="tech-item">PyTorch</div>
<!-- Add more tech-item divs -->
```

### 7. Contact Information

Update all contact cards with your actual links and information.

## 🎨 Customizing Colors & Style

All colors are defined in `styles.css` at the top:

```css
:root {
    --primary-bg: #ffffff;
    --secondary-bg: #f7f7f8;
    --text-primary: #1a1a1a;
    --text-secondary: #6e6e80;
    --accent-color: #10a37f;  /* Change this for your brand color */
    --accent-hover: #0d8c6a;
    --border-color: #e5e5e7;
}
```

Simply change these values to customize your color scheme!

## 🚀 Deploying to GitHub Pages

1. Create a new repository named `yourusername.github.io`
2. Upload these files: `index.html`, `styles.css`, `script.js`
3. Go to Settings → Pages
4. Select "Deploy from main branch"
5. Your site will be live at `https://yourusername.github.io`

## 📁 File Structure

```
portfolio/
├── index.html      # Main HTML file with all content
├── styles.css      # All styling (OpenAI-inspired design)
├── script.js       # Smooth scrolling and animations
└── README.md       # This file
```

## 💡 Tips

- **Images**: Place your profile photo in the same directory and update the `src` in the `<img>` tag
- **Demo Screenshots**: Add preview images for your demos in the `demo-preview` divs
- **Blog Links**: Link to external blog posts or create separate HTML pages
- **Resume**: Add a "Download Resume" button in the Contact section if needed

## 🛠️ Optional Features

The `script.js` file includes commented code for:
- Typing animation effect
- Dark mode toggle

Uncomment the relevant sections to enable these features.

## 📱 Responsive Design

The site automatically adjusts for:
- Desktop (1200px+)
- Tablet (768px - 1200px)
- Mobile (< 768px)

## 🤝 Need Help?

If you need help customizing:
1. Look for `<!-- EDIT -->` comments in the HTML
2. Check the README for examples
3. All sections follow the same pattern - just copy and paste to add more items

---

Built with ❤️ for developers and ML practitioners

