# My Hugo Site

This is a static website built with [Hugo](https://gohugo.io/) and using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod/) theme.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Hugo Extended](https://gohugo.io/installation/) (v0.110.0 or later)
- Git

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/yourusername/my-hugo-site.git
cd my-hugo-site
```

2. Initialize and update the theme submodule:

```bash
git submodule update --init --recursive
```

3. Start the development server:

```bash
hugo server -D
```

Your site should now be running at [http://localhost:1313/](http://localhost:1313/)

## Creating New Content

To create a new blog post:

```bash
hugo new content/posts/my-new-post.md
```

## Building for Production

To build the site for production:

```bash
hugo --minify
```

The generated site will be in the `public` directory.

## Project Structure

```
.
├── archetypes/        # Content template files
├── assets/            # Files that need to be processed by Hugo Pipes
├── content/           # The actual content of the site
├── data/             # Configuration files
├── layouts/          # Template files
├── static/           # Static files
├── themes/           # Theme files
├── config.toml       # Site configuration
└── README.md         # This file
```

## Customization

- Site configuration can be modified in `hugo.toml`
- Theme settings can be adjusted in `hugo.toml`
- Custom layouts can be added to the `layouts` directory

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Hugo](https://gohugo.io/) for the amazing static site generator
- [PaperMod Theme](https://github.com/adityatelange/hugo-PaperMod/) for the beautiful theme
