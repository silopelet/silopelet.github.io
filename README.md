# Jekyll Website

This is a Jekyll-powered website using the [Minimal Mistakes Theme](https://github.com/mmistakes/minimal-mistakes).

## Setup

### Prerequisites

- Ruby (version 3.0 or higher)
- Bundler

### Installation

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Build the site:
   ```bash
   bundle exec jekyll build
   ```

3. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser

## Project Structure

- `_config.yml` - Jekyll configuration file
- `index.md` - Homepage
- `hello-world.md` - Sample "Hello World" page
- `Gemfile` - Ruby dependencies

## Adding Content

To add a new page:

1. Create a new `.md` file in the root directory
2. Add front matter:
   ```yaml
   ---
   layout: page
   title: "Your Page Title"
   permalink: /your-page-url/
   ---
   ```
3. Write your content in Markdown

## GitHub Pages Deployment

This site is configured to work with GitHub Pages. Simply push your changes to the repository and GitHub Pages will automatically build and deploy your site.

## Customization

Edit `_config.yml` to customize:
- Site title and description
- Author information
- URL settings
- Theme options

For more theme customization options, see the [Minimal Mistakes Theme documentation](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).
