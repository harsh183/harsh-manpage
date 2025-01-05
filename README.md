# 📇 Jekyll Theme Manpage

> This theme is in development and not ready to use yet! 

[![Netlify Status](https://api.netlify.com/api/v1/badges/d2497628-6688-4ba9-909c-4680a22f2a72/deploy-status)](https://app.netlify.com/sites/jekyll-theme-manpage/deploys)

A minimalist Jekyll theme inspired by Linux man pages. Perfect for personal websites, portfolios, and blogs with a technical focus.

![Preview](assets/readme/preview.png)

## Features

- 🖥️ Linux man page inspired design
- 📱 Fully responsive layout
- 🌙 Automatic dark mode support
- ✍️ Blog/writing section with:
  - Full-text search
  - Tag filtering
  - Table of contents
- 📐 LaTeX support for mathematical expressions
- 🎨 Multiple color themes
- 🚀 Fast and lightweight
- 📱 Mobile-first approach

## Installation

### Local Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-theme-manpage"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-theme-manpage
```

Then run

```bash
bundle install
```

### GitHub Pages Installation

For GitHub Pages, add this to your site's `_config.yml`:

```yaml
remote_theme: drshika/jekyll-theme-manpage
plugins:
  - jekyll-remote-theme
```

Add `jekyll-remote-theme` to the Gemfile:

```ruby:Gemfile
gem 'jekyll-remote-theme'
```

## Usage

### Basic Setup

1. Create your site structure following Jekyll conventions
2. Configure `_config.yml` with your settings
3. Add content to `index.md` using the provided template

### Writing Posts

Create posts in `_posts` directory following this format:

```markdown
---
layout: post
title: Your Post Title
description: Brief description
tags: [tag1, tag2]
toc: true # Optional table of contents
---
Your content here...
```

Make sure to name the file with the `YYYY-MM-DD-Title.md`. 


### Customization

#### Color Themes

The theme comes with several preset color schemes. Currently changing the theme is only supported for local development. 

### Light Themes
| Theme | Preview |
|-------|---------|
| Purple | ![Purple Theme](assets/themes/purple.png) |
| Tomorrow | ![Tomorrow Theme](assets/themes/tomorrow.png) |
| GitHub | ![GitHub Theme](assets/themes/github.png) |
| Dracula | ![Dracula Theme](assets/themes/dracula.png) |
| Nord | ![Nord Theme](assets/themes/nord.png) |
| Monokai | ![Monokai Theme](assets/themes/monokai.png) |

### Dark Themes
| Theme | Preview |
|-------|---------|
| Purple | ![Purple Dark Theme](assets/themes/purple_dark.png) |
| Tomorrow | ![Tomorrow Dark Theme](assets/themes/tomorrow_dark.png) |
| GitHub | ![GitHub Dark Theme](assets/themes/github_dark.png) |
| Dracula | ![Dracula Dark Theme](assets/themes/dracula_dark.png) |
| Nord | ![Nord Dark Theme](assets/themes/nord_dark.png) |
| Monokai | ![Monokai Dark Theme](assets/themes/monokai_dark.png) |


To use any of these themes, update your `_sass/variables.scss`:

```scss
// Theme selection
$default-theme: 'nord';
$default-mode: 'light';
```

#### Typography

This theme uses Nitti as its default font. You can purchase Nitti from [Adobe Fonts](https://fonts.adobe.com/fonts/nitti). If you don't have Nitti, the theme will fallback to Fira Code.

## Development

(For local use only!) To set up your environment to develop this theme:

1. Clone this repo
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Visit `http://localhost:4000`

## Optional Features

Enable optional features in your `_config.yml`:

```yaml
features:
  comments: false  # Enable Giscus comments
  rss_feed: false  # Enable RSS feed
```

### Comments

To enable comments:

1. Set `features.comments: true` in your `_config.yml`
2. Get your Giscus script from [giscus.app](https://giscus.app)
3. Paste the generated script into `_includes/comments.html`

Disable comments for specific posts by adding `comments: false` to the post's front matter.

### RSS Feed

To enable RSS feed:

1. Set `features.rss_feed: true` in your `_config.yml`

Your feed will be available at `/feed.xml`. See [Jekyll Feed documentation](https://github.com/jekyll/jekyll-feed) for additional configuration options.

## Contributing

Bug reports and pull requests are welcome on GitHub. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](https://www.contributor-covenant.org/) code of conduct.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Credits

Created with ❤️ by Drshika Asher
