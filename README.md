# ipapadop.github.io

Source for [ipapadop.github.io](https://ipapadop.github.io), built with
[Jekyll](https://jekyllrb.com/) and the [Minima](https://github.com/jekyll/minima)
theme (pinned via `remote_theme` in `_config.yml`) on GitHub Pages.

## Writing a post

Add a Markdown file to `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
title: "My post"
tags: [c++, hpc]
---
Post content…
```

Posts get the `post` layout and Disqus comments by default; set `comments: false`
in the front matter to turn them off for one post.

## Local preview

```sh
bundle install
bundle exec jekyll serve --livereload
```

Then open http://localhost:4000.
