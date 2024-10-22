# Simple Github Page

View at [https://christophera.github.io/simplest-github-page/](https://christophera.github.io/simplest-github-page/)

## Goals

* Without using Jekyll, Ruby or Gem, leverage the various files that allow you to use markdown directly within github pages.
* Pages should largely look the same when rendered from the GitHub repo page and from the git
* Leverage the default [Jekyll Primer](https://github.com/pages-themes/primer) theme's CSS without the using the full theme.
* Support internal anchor link tags

## Using This
* [ ]  Edit the `_config.yml` with your own info
* [ ]  Edit the `/_layouts/default.html` file to change default html template.
* [ ]  Add to `/_layouts/default.html` template any inline styles you wish to override.

### Displays correctly both Web View and in GitHub View

### Displays correctly both Web View and in GitHub View, but requires proper formatting
* Github will render raw URLs as links, but you must use proper markdown construction `[linkname](link)` for URLs to display propery in the Web View.
* If you do a relative link to a markdown file without the extension, it will be rendered in html correctly, for example relative [./sample](./sample). Unfortunately, when rendered in Github the relative link will give a 404 error. To preserve compatiblity of both, if use use the `.md` extension in the relative link — it will render correctly in both html and gihub and both will function as links to the correct place, for example see [./sample.md](./sample.md). You do not need to do this with `/` which will render `README.md` as `index.html`



