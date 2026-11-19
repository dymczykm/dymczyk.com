# dymczyk.com

Source of www.dymczyk.com, built by GitHub Pages (Jekyll).

## Editing

- Home page: `index.md`
- Project pages: `projects/<name>/index.md`, with web-sized images in `images/` and the original full-resolution files in `originals/`
- Each page's front matter sets its title and its `description` (shown in Google results).

Edit a file on github.com (press `.` or the pencil icon), commit, and the site updates in a minute or two.

To add a project, copy one of the `projects/<name>/` folders, change the front matter (`title`, `description`, `permalink`), and link it from `index.md`.

## Preview locally (optional)

    bundle install
    bundle exec jekyll serve
