# Usage Guide

## In GitHub and GitLab

### Prepare

1. push oh-wiki to GitHub or GitLab repo.
2. Enable GitHub Pages

### New pages

1. Add a new file. named `FILENAME.md`
2. Edit `config.json`. add `FILENAME.md` in array `url`, and add title of new page in array `tit`

You can use markdown and KaTeX.

KaTeX: $\sum$

### Config file

Config file is `config.json`

- `title` string(file name)   Your wiki's name
- `home`  string(file name)   Home file, language in MD
- `icon`  string(file name)   Your wiki's icon
- `url`   array(strings in it)Your article's url link(file name)
- `tit`   array(strings in it)Your article's title
- `foot`  string(use HTML)    Something in foot of pages
