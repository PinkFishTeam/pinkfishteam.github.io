# How to make the site work?

## Installation

1. Install `Jekyll` and `Bundler`: https://jekyllrb.com/docs/installation/ubuntu/
2. Clone the current repository directory.
3. Install missing gems
```bash
bundle install
```
4. Deploy the site by running:
```bash
bundle exec jekyll serve
```
in a terminal.

The site should be available at `http://127.0.0.1:4000`, which allows you to test
locally anything you want.

## Modifying the site

### Adding content

Most of the time you have to create a new file (markdown) that you will place in
the suitable directory.      

Concretely, a new portfolio entry will consist of a file located in the directly
`_posts`. Some examples are already available.

It is also possible to add new pages, but that's not needed now.

### Changing the style

The are different ways to change the style, depending on what one wants to do.
- `_config.yml` contains the colors and other global settings. The effect of changes
applied in this file will only be seen after re-running the `bundle exec jekyll serve`
command.
- `_includes/css/main.css` contains all the style settings, probably we should agree
before touching stuff there.

### Uploading the changes

Just commit the changes on GitHub, the effect will be almost directly visible
on the site.
