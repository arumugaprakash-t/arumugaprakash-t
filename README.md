# Prakash's Portfolio

A clean, minimal Jekyll portfolio website featuring a white background, black text, red accents, and blue links.

## Features

- **Clean Design**: Minimal, professional layout inspired by modern developer portfolios
- **Responsive**: Mobile-first design that works on all devices
- **Fast Loading**: Optimized for performance and quick loading times
- **SEO Friendly**: Built-in SEO optimization with Jekyll plugins
- **GitHub Pages Ready**: Fully compatible with GitHub Pages deployment

## Color Scheme

- Background: White (#ffffff)
- Primary Text: Black (#000000)
- Accent/Highlights: Red (#dc2626)
- Links: Blue (#3b82f6)

## Local Development

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler gem

### Setup

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

### Making Changes

- Edit content in `index.html` or create new pages
- Modify styling in `assets/css/main.css`
- Update site configuration in `_config.yml`
- Add blog posts in the `_posts` directory (create it when needed)

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select "Deploy from a branch" and choose your main branch
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Custom Domain (Optional)

1. Add a `CNAME` file with your domain name
2. Configure DNS settings with your domain provider
3. Update the `url` in `_config.yml`

## Customization

### Personal Information

Update the following in `_config.yml`:
- `title`: Your name
- `email`: Your email address
- `description`: Brief bio
- `url`: Your site URL
- `github_username`: Your GitHub username
- `linkedin_username`: Your LinkedIn username

### Navigation

Modify navigation links in `_includes/header.html`. The current structure supports:
- Home
- About (prepare to create `about.html`)
- Projects (prepare to create `projects.html`)
- Blog (prepare to create a `blog.html` and `_posts` directory)

### Content

- **Home page**: Edit `index.html`
- **About page**: Create `about.html` with layout: default
- **Projects**: Create `projects.html` to showcase your work
- **Blog**: Create `_posts` directory and add markdown files

## Structure

```
├── _config.yml           # Site configuration
├── _includes/            # Reusable components
│   ├── header.html       # Site header/navigation
│   └── footer.html       # Site footer
├── _layouts/             # Page layouts
│   └── default.html      # Base layout template
├── assets/
│   └── css/
│       └── main.css      # Main stylesheet
├── index.html            # Home page
├── Gemfile              # Ruby dependencies
├── .gitignore           # Git ignore rules
└── README.md            # This file
```

## Future Enhancements

The site is structured to easily add:
- About page with detailed bio
- Projects showcase with GitHub integration
- Blog section with posts
- Contact form
- Dark mode toggle
- Analytics integration

## Technologies Used

- **Jekyll**: Static site generator
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **GitHub Pages**: Hosting platform
- **SEO**: Jekyll SEO Tag plugin

## License

This project is open source and available under the [MIT License](LICENSE).