# SteveSWilson.github.io

My personal website and blog, published at
[SteveSWilson.github.io](https://SteveSWilson.github.io).

**Want to add a blog post?** See [HOW_TO_ADD_A_POST.md](HOW_TO_ADD_A_POST.md)
— just fill out a form in the Issues tab, no coding needed.

## How this site works

- Built with [Jekyll](https://jekyllrb.com/) using a custom theme (see
  [`assets/css/style.css`](assets/css/style.css) and [`_layouts`](_layouts)).
- Blog posts live in the [`_posts`](_posts) folder as Markdown files.
- New posts are normally added via the **"📝 New Blog Post"** issue form,
  which automatically drafts a pull request for you to review and merge
  (see [`.github/ISSUE_TEMPLATE/new-blog-post.yml`](.github/ISSUE_TEMPLATE/new-blog-post.yml)
  and [`.github/workflows/new-post-from-issue.yml`](.github/workflows/new-post-from-issue.yml)).
- The [About page](about.md) and other site settings
  ([`_config.yml`](_config.yml)) can be edited directly on github.com the
  same way as any file.
- Every pull request automatically builds the site and checks for broken
  links/images (see [`.github/workflows/ci.yml`](.github/workflows/ci.yml)).
- Every push to `main` (including merging a pull request) automatically
  rebuilds and publishes the live site
  (see [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)).
