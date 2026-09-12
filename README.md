# SteveSWilson.github.io

My personal website and blog, published at
[SteveSWilson.github.io](https://SteveSWilson.github.io).

**Want to add a blog post?** See [HOW_TO_ADD_A_POST.md](HOW_TO_ADD_A_POST.md)
— no coding needed, everything is done in the browser on github.com.

## How this site works

- Built with [Jekyll](https://jekyllrb.com/) using the `minima` theme.
- Blog posts live in the [`_posts`](_posts) folder as Markdown files.
- The [About page](about.md) and other site settings
  ([`_config.yml`](_config.yml)) can be edited the same way.
- Every pull request automatically builds the site and checks for broken
  links/images (see [`.github/workflows/ci.yml`](.github/workflows/ci.yml)).
- Every push to `main` automatically rebuilds and publishes the live site
  (see [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml)).
