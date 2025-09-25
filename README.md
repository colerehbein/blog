# cole.press blog

This repository contains the source for the standalone **cole.press blog** site. It is built with [Quarto](https://quarto.org).

## Structure

- `index.qmd` defines the blog landing page and includes a listing of posts found in the `posts/` directory.
- `about.qmd` provides information about the blog and its author.
- `posts/` will contain your individual blog posts as Quarto markdown files. Each post should have its own `.qmd` file with appropriate frontmatter.
- `_quarto.yml` configures the site title, navigation bar, and other website options.

## Building

To render the site locally, install Quarto and run:

```bash
quarto render
```

The rendered site will appear in the `_site` directory. You can deploy the contents of `_site` to Netlify or any static hosting provider.
