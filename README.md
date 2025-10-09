# gdputra.github.io

A personal website using Github pages, maintained also with @gtrdp.

## 🚀 Getting Started

This is a Jekyll-based website hosted on GitHub Pages. Follow these steps to run it locally for development.

### Prerequisites

Before you begin, make sure you have the following installed:

1. **Ruby** (version 2.7 or higher)

   ```bash
   ruby --version
   ```

2. **Bundler** (Ruby package manager)

   ```bash
   gem install bundler jekyll --user-install
   ```

3. **Git** (for version control)
   ```bash
   git --version
   ```

### 📦 Installation

1. **Clone the repository** (if you haven't already):

   ```bash
   git clone https://github.com/gdputra/gdputra.github.io.git
   cd gdputra.github.io
   ```

2. **Install dependencies** (equivalent to `npm install`):
   ```bash
   bundle config set path 'vendor/bundle'
   bundle install
   ```

### 🏃‍♂️ Running the Development Server

1. **Start the Jekyll server** (equivalent to `npm start`):

   ```bash
   bundle exec jekyll serve
   ```

2. **With custom port** (if port 4000 is busy):

   ```bash
   bundle exec jekyll serve --port 4001
   ```

3. **With live reload** (auto-refresh browser on changes):

   ```bash
   bundle exec jekyll serve --livereload
   ```

4. **Open your browser** and navigate to:

   ```
   http://localhost:4000
   ```

   (or `http://localhost:4001` if using custom port)

5. **If you want to make a push** please delete the folder .bundle and vendor:
   ```bash
   rm -rf .bundle
   rm -rf vendor
   ```

### 🔨 Building for Production

To build the site for production (equivalent to `npm run build`):

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

### 🧹 Cleaning Build Cache

If you encounter issues, clean the build cache:

```bash
bundle exec jekyll clean
```

Then rebuild:

```bash
bundle exec jekyll build
```

### 📁 Project Structure

```
├── _config.yml          # Main configuration file
├── _pages/             # Website pages (about, teams, etc.)
├── _posts/             # Blog posts (if any)
├── _includes/          # Reusable components
├── _layouts/           # Page templates
├── _sass/              # SCSS stylesheets
├── assets/             # CSS, JS, images
├── images/             # Image files
├── Gemfile             # Ruby dependencies (like package.json)
├── Gemfile.lock        # Locked dependency versions
└── _site/              # Generated site (auto-created)
```

### 🔧 Common Commands

| Task                   | Command                        |
| ---------------------- | ------------------------------ |
| Install dependencies   | `bundle install`               |
| Run development server | `bundle exec jekyll serve`     |
| Build for production   | `bundle exec jekyll build`     |
| Clean cache            | `bundle exec jekyll clean`     |
| Update dependencies    | `bundle update`                |
| Check Jekyll version   | `bundle exec jekyll --version` |

### 🐛 Troubleshooting

**Port already in use?**

```bash
bundle exec jekyll serve --port 4001
```

**Dependencies issues?**

```bash
bundle clean --force
bundle install
```

**Permission errors?**

```bash
sudo bundle install
```

**Site not updating?**

- Hard refresh browser (Cmd+Shift+R on Mac, Ctrl+F5 on Windows)
- Clear browser cache
- Stop and restart Jekyll server

### 📝 Making Changes

1. **Edit files** in `_pages/`, `_posts/`, or other directories
2. **Save changes** - Jekyll will automatically rebuild (in development mode)
3. **Refresh browser** to see changes
4. **Commit and push** to deploy to GitHub Pages:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

### 🌐 Deployment

This site automatically deploys to GitHub Pages when you push to the `main` branch. No additional deployment steps needed!

**Live site**: https://gdputra.github.io

### 📚 Useful Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Liquid Template Language](https://shopify.github.io/liquid/)
- [Markdown Guide](https://www.markdownguide.org/)
