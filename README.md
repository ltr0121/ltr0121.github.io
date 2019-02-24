# Tale
Tale is a minimal Jekyll theme curated for storytellers. Checkout the demo here.

## Features
- Easy installation
- Compatible with GitHub Pages
- Responsive design (looks just as good on mobile)
- Syntax highlighting, with the help of Pygments
- Markdown and HTML text formatting
- Pagination of posts

## Installation
There are 3 ways to install this theme

1. Install it as a Ruby Gem (For self-hosted sites)
2. Install it with the `jekyll-remote-theme` plugin (for GitHub Pages hosted sites)
3. Fork the project directly

### Ruby Gem method

1. Add this line to your `Gemfile`:
  gem "tale"
2. Install the theme's gems and dependencies:
  $ bundle
3. In `_config.yml` add these lines:

  theme:       tale
  
  permalink:   /:year-:month-:day/:title
  paginate:    5
  
Remove any other `theme:` lines.

4. Rename `index.md` to `index.html`. Without this, the `jekyll-paginate` gem will not work.
5. In `about.md`, change the `layout:` field to `post`:
  layout: post
 
### GitHub Pages method
