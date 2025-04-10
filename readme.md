# PhotoBlog
<!-- Badges (Optional) -->
[![GitHub License](https://img.shields.io/github/license/<your-username>/<repo-name>)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-blue)](https://<your-username>.github.io/<repo-name>)

# 📸 PhotoBlog - Capturing Moments

A modern, responsive photography blog website designed to showcase stunning visuals and creative content. Built with HTML, CSS, and JavaScript, and deployed via GitHub Pages.

![Blog Screenshot](assets/images/screenshot.png) <!-- Add a screenshot -->

## ✨ Features
- **Responsive Design**: Works seamlessly on mobile, tablet, and desktop devices.
- **Smooth Animations**: Scroll-triggered effects and CSS transitions for a polished user experience.
- **SEO Optimized**: Includes meta tags, alt text, and semantic HTML for better search engine visibility.
- **Photography-Focused Layout**: Designed to highlight images and visual content.
- **Dynamic Navigation**: Smooth scrolling and responsive menu for easy navigation.

## 🚀 Quick Start
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. **Install Dependencies** (if using a static site generator):
   ```bash
   npm install  # or `bundle install` for Jekyll
   ```
3. **Run Locally**:
   ```bash
   npm start    # or `bundle exec jekyll serve`
   ```

## 📂 Project Structure
```
.
├── assets/          # Static files
│   ├── css/         # Stylesheets
│   ├── js/          # JavaScript files
│   └── images/      # Blog post images
├── posts/           # Markdown blog posts
├── _config.yml      # Static site config (if using Jekyll/Hugo)
├── index.html       # Homepage
└── package.json     # Node.js dependencies (if applicable)
```

## 🔧 Configuration
1. **Add New Posts**:
   - Create `.md` files in `/posts` with this front matter:
     ```markdown
     ---
     title: "My First Post"
     date: 2024-05-20
     tags: [Tech, Web Development]
     ---
     ```

2. **Customize Styles**:
   Modify CSS variables in `assets/css/styles.css`:
   ```css
   :root {
     --primary-color: #2c3e50;
     --accent-color: #3498db;
   }
   ```

## 🌐 Deployment
Automatically deployed to **GitHub Pages** on every `git push`.  
Live URL: https://<your-username>.github.io/<repo-name>

## 🤝 Contributing
1. Fork the repository
2. Create a branch (`git checkout -b feature/your-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## 📜 License
Distributed under the MIT License. See [LICENSE](LICENSE) for details.

---

Made with ❤️ by [Anirban Dey](https://github.com/<KEYGAMER>)

<article class="post-card">
    <div class="post-image" style="background-image: url('images/new-photo.jpg')">
        <div class="post-date">March 24, 2025</div>
    </div>
    <div class="post-content">
        <span class="post-tag">Nature</span>
        <h3>Title of the Post</h3>
        <p>Short description of the post...</p>
        <button class="read-more">Read More →</button>
    </div>
</article>
