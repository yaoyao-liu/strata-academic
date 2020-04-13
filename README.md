# The Strata Academic Theme

[![LICENSE](https://img.shields.io/github/license/yaoyao-liu/minimal-academic)](https://github.com/yaoyao-liu/strata-academic/blob/master/LICENSE)
[![gem](https://img.shields.io/gem/v/strata-academic)](https://rubygems.org/gems/strata-academic)
[![Jekyll](https://img.shields.io/badge/jekyll-%3E%3D%203.5-orange.svg)](https://jekyllrb.com/)

[Demo the theme](https://strata-academic.yyliu.net/)

[Try another Jekyll theme: Minimal Light](https://github.com/yaoyao-liu/minimal-light)

## Features

- Simple and elegant personal homepage theme
- Jekyll theme, deploy automatically by GitHub pages
- Mobile friendly
- Support Markdown 

## Usage

### Using on GitHub 

To use this theme, add the following to your site's `_config.yml`:

```yaml
remote_theme: yaoyao-liu/strata-academic
```

### Using with Jekyll

*You need to install [Ruby](https://www.ruby-lang.org/en/) and [Jekyll](https://jekyllrb.com/) fisrt.*

Clone this repository:

```bash
git clone https://github.com/yaoyao-liu/strata-academic.git
cd strata-academic
```
Install and run:

```bash
bundle install
bundle exec jekyll server
```
View the live page using `localhost`:
<http://localhost:4000>. You can get the html files in `_site` folder.

## Customizing

### Configuration variables

Minimal Academic theme will respect the following variables, if set in your site's `_config.yml`:

  ```yaml
title: Your Name
affiliation: Your Affiliation
email: yourname (at) example.edu
google_scholar: https://scholar.google.com/
github_link: https://github.com/yaoyao-liu/strata-academic
linkedin: https://www.linkedin.com/
avatar: ./assets/img/avatar.png
google_analytics: UA-111540567-4
favicon: ./assets/img/favicon.png
favicon_dark: ./assets/img/favicon-dark.png
description: The Minimal Light is a simple and elegant jekyll theme for academic personal homepage.
canonical: https://strata-academic.yyliu.net/
remote_theme: yaoyao-liu/strata-academic
  ```
### Editing `index.md`

Edit `index.md` and add your personal information (e.g. publications, research).

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:

    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

### Layouts

If you'd like to change the theme's HTML layout:

1. [Copy the original template](https://github.com/yaoyao-liu/strata-academic/blob/master/_layouts/homepage.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
2. Create a file called `/_layouts/homepage.html` in your site
3. Paste the default layout content copied in the first step
4. Customize the layout as you'd like

## License

This work is licensed under a [Creative Commons Zero v1.0 Universal](https://github.com/yaoyao-liu/strata-academic/blob/master/LICENSE) License.

## Acknowledgements

Our project uses the source code from the following projects:

* [pages-themes/minimal](https://github.com/pages-themes/minimal)

* [Strata-HTML5](https://html5up.net/strata)
