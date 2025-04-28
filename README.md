# Anime Blog Template

A personal blog template specifically designed for anime enthusiasts, built with modern frontend technology stack. This project inherits design concepts from [hexo-theme-redefine](https://github.com/EvanNotFound/hexo-theme-redefine), providing anime culture enthusiasts with a beautiful and practical blog solution. It features interactive Live2D character animations and dynamic particle background effects using particles.js, creating an immersive anime-style experience.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Node Version](https://img.shields.io/badge/node-%3E%3D16.0.0-brightgreen.svg)
![Yarn Version](https://img.shields.io/badge/yarn-%3E%3D1.22.0-blue.svg)

## ✨ Features

- 🎨 Carefully designed anime-style UI, perfectly matching ACG culture
- 📱 Responsive design, supporting various devices
- 🚀 Built with modern frontend technology stack, excellent performance
- 📝 Markdown writing support, similar content management to Hexo
- 🎯 Built-in SEO optimization, improving search engine rankings
- 🌈 Rich theme customization options
- 💬 Support for multiple comment systems (Gitalk, Valine)
- 📊 Built-in visitor statistics
- 🎭 Interactive Live2D character animations
- ✨ Dynamic particle background effects using particles.js

## ⚠️ Important Notice

This project is intended for **private deployment only**. For commercial use, please refer to the license terms of:
- [hexo-theme-redefine](https://github.com/EvanNotFound/hexo-theme-redefine)
- [Live2D](https://www.live2d.com/en/terms/)

## 🚀 Quick Start

### Requirements

- Node.js >= 16.0.0
- Yarn >= 1.22.0

### Installation Steps

1. Clone the project
```bash
git clone https://github.com/your-username/anime-blog-template.git
cd anime-blog-template
```

2. Install dependencies
```bash
yarn install
```

3. Start development server
```bash
yarn dev
```

4. Build for production
```bash
yarn build
```

## 📝 Content Management

### Writing Posts

Create Markdown files in the `source/_posts` directory using the following format:

```markdown
---
title: Post Title
date: 2024-03-21 12:00:00
tags:
  - tag1
  - tag2
categories:
  - category1
---

Post content...
```

### Draft Management

- Place unfinished posts in the `source/_drafts` directory
- Use `yarn draft` command to preview drafts

## ⚙️ Configuration

### Site Configuration

Configure in `config/site.yml`:

```yaml
title: My Anime Blog
subtitle: Sharing Anime Culture
description: A personal blog about anime culture
keywords: anime,ACG,culture
author: Your Name
language: en-US
timezone: UTC
```

### Theme Configuration

Configure in `config/theme.yml`:

```yaml
# Theme color
theme_color: "#FF69B4"

# Navigation menu
menu:
  - name: Home
    path: /
  - name: Archives
    path: /archives
  - name: Tags
    path: /tags
  - name: About
    path: /about
```

## 📦 Project Structure

```
.
├── public/          # Build output directory
├── source/          # Blog source files
│   ├── _posts/     # Blog posts
│   ├── _drafts/    # Draft posts
│   └── assets/     # Static assets
├── themes/         # Theme files
└── config/         # Configuration files
```

## 🚀 Deployment

Supports multiple deployment methods:

- **GitHub Pages**
  - Push `public` directory contents to `gh-pages` branch
  - Enable GitHub Pages in repository settings

- **Vercel**
  - Connect Vercel account
  - Select `public` as output directory
  - Automatic deployment

- **EdgeOne**
  - Upload static files to EdgeOne
  - Configure CDN acceleration

## ❓ FAQ

### 1. How to modify theme styles?
Theme style files are located in `themes/default/assets/css/` directory, you can modify the corresponding CSS files directly.

### 2. How to add new pages?
Create corresponding Markdown files in the `source` directory and add menu items in the `menu` configuration in `config/theme.yml`.

### 3. How to add comment system?
Configure Gitalk or Valine comment system parameters in `config/theme.yml`.

## 🤝 Contributing

Pull requests are welcome to improve this project. Before submitting, please ensure:

1. Code follows project coding standards
2. Add necessary tests
3. Update relevant documentation

## 📄 License

This project is licensed under [MIT](LICENSE).

## 🙏 Acknowledgments

- [hexo-theme-redefine](https://github.com/EvanNotFound/hexo-theme-redefine) - Theme design reference
- All developers who have contributed to this project

## 📞 Contact

For questions or suggestions, please contact us through:

- Submit an Issue
- Send email to: tomcomtang@gmail.com