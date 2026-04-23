# Mingsong Li Personal Website

This repository contains the source for <https://mingsongli.com>.

The site is built with Jekyll using the Academic Pages theme. Main content lives in `_pages/`, profile and research images live in `images/`, and downloadable files live in `files/`.

## Local Preview

Use Ruby 3.1 for the current Academic Pages dependency set:

```bash
export PATH="/usr/local/opt/ruby@3.1/bin:/usr/local/lib/ruby/gems/3.1.0/bin:$PATH"
bundle exec jekyll serve -l -H localhost --port 4000
```

Then open <http://localhost:4000>.

## Custom Domain

The `CNAME` file sets the GitHub Pages custom domain to `mingsongli.com`.
