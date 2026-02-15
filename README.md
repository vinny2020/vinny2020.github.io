# Vinny's Blog

A modern, responsive Jekyll blog built for GitHub Pages. This blog features a clean design, syntax highlighting, social sharing, and mobile-friendly navigation.

## 🚀 Features

- **Modern Design**: Clean, responsive layout with beautiful typography
- **Fast Loading**: Optimized for performance with minimal dependencies
- **SEO Optimized**: Built-in SEO tags and structured data
- **Social Sharing**: Easy sharing buttons for posts
- **Syntax Highlighting**: Beautiful code highlighting for technical posts
- **Mobile Responsive**: Looks great on all devices
- **GitHub Pages Ready**: Automated deployment with GitHub Actions

## 🛠️ Technologies Used

- **Jekyll 4.x**: Static site generator
- **Sass/SCSS**: For styling
- **GitHub Pages**: Hosting platform
- **GitHub Actions**: Automated deployment
- **Font Awesome**: Icons
- **Inter Font**: Typography

## 📁 Project Structure

```
├── _config.yml           # Jekyll configuration
├── _layouts/             # Page layouts
│   ├── default.html      # Base layout
│   ├── home.html         # Homepage layout
│   ├── post.html         # Blog post layout
│   └── page.html         # Static page layout
├── _includes/            # Reusable components
│   ├── header.html       # Site header
│   └── footer.html       # Site footer
├── _sass/                # Sass partials
│   ├── _variables.scss   # CSS variables
│   ├── _base.scss        # Base styles
│   ├── _layout.scss      # Layout styles
│   ├── _components.scss  # Component styles
│   └── _syntax-highlighting.scss # Code highlighting
├── _posts/               # Blog posts
├── _pages/               # Static pages
├── assets/               # Assets (CSS, JS, images)
└── .github/workflows/    # GitHub Actions
```

## 🚀 Getting Started

### Prerequisites

- Ruby 2.7 or higher
- Bundler gem

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/vinny2020/vinny2020.github.io.git
   cd vinny2020.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run the development server**
   ```bash
   bundle exec jekyll serve
   ```

4. **Open your browser**
   Navigate to `http://localhost:4000`

### Customization

1. **Update site configuration**
   Edit `_config.yml` to customize your site settings:
   ```yaml
   title: "Your Blog Title"
   description: "Your blog description"
   url: "https://vinny2020.github.io"
   author:
     name: "Your Name"
     email: "xaymaca@gmail.com"
   ```

2. **Update social links**
   ```yaml
   social:
     github: vinny2020
     linkedin: vincentstoessel
   ```

3. **Customize colors and fonts**
   Edit variables in `_sass/_variables.scss`

## 📝 Writing Posts

Create new posts in the `_posts` directory with the naming convention:
`YEAR-MONTH-DAY-title.md`

Example front matter:
```yaml
---
layout: post
title: "Your Post Title"
date: 2024-01-15 10:00:00 -0500
categories: [category1, category2]
tags: [tag1, tag2, tag3]
author: Your Name
excerpt: "A brief description of your post"
featured_image: "/assets/images/your-image.jpg" # Optional
---
```

## 🌐 Deployment

This blog is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" section
3. Under "Source", select "GitHub Actions"
4. The workflow will automatically deploy your site on every push to main

### Custom Domain (Optional)

1. Add a `CNAME` file to your repository root with your domain
2. Configure your domain's DNS to point to GitHub Pages
3. Update the `url` in `_config.yml`

## 📱 Responsive Design

The blog is fully responsive and includes:
- Mobile-first design approach
- Responsive navigation with hamburger menu
- Optimized images and typography
- Touch-friendly interactions

## 🔧 Performance

- Minimal CSS and JavaScript
- Optimized images
- Fast loading times
- Lighthouse score optimized

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙋‍♂️ Support

If you have any questions or need help with setup, feel free to:
- Open an issue on GitHub
- Reach out on social media
- Check the [Jekyll documentation](https://jekyllrb.com/docs/)

---

Built with ❤️ using Jekyll and GitHub Pages