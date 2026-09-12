# How to add a new blog post (no coding required)

You never need to install anything or touch a terminal. Everything below
happens in your browser on github.com.

## 1. Go to the `_posts` folder

Open this repository on github.com and click into the `_posts` folder.

## 2. Create a new file

Click **Add file → Create new file**.

Name the file exactly like this:

```
YYYY-MM-DD-a-short-title.md
```

For example: `2026-09-12-my-weekend-trip.md`

- The date must come first, in `YYYY-MM-DD` format.
- After the date, use lowercase words separated by dashes.
- The file must end in `.md`.

## 3. Paste this template in and edit it

```
---
layout: post
title:  "My Weekend Trip"
date:   2026-09-12 09:00:00 -0000
---

Write your post here! You can use plain text, or **bold**, *italic*,
and [links](https://example.com) using Markdown.
```

- Change `title` to your post's title.
- Change `date` to match the date in the filename (the time and `-0000` can
  stay as-is, or you can leave them out).
- Keep the three dashes (`---`) exactly as shown — that section is called
  "front matter" and tells the site how to display your post. If it's
  missing or the dashes are wrong, the automated check described below will
  fail and tell you so.
- Everything below the second `---` is your actual post content.

## 4. Commit the file

Scroll down, and click **Commit changes...**. GitHub will ask if you want to
commit directly to `main` or open a pull request:

- **Fastest:** commit directly to `main`. Your post goes live automatically
  within a minute or two.
- **Safer (recommended if you want a chance to preview/undo):** choose
  "Create a new branch and start a pull request." This runs the automated
  checks first and lets you see if anything looks wrong before it goes
  live. When you're happy, click **Merge pull request**.

## What happens automatically

- Every pull request automatically runs a check that builds the site and
  looks for broken links or images, so you'll get a warning before
  publishing if something's off.
- Every time `main` is updated (directly, or by merging a pull request),
  the site automatically rebuilds and publishes to
  https://SteveSWilson.github.io within a couple of minutes.

## Editing or removing a post

Open the file in `_posts`, click the pencil icon to edit it (or the trash
icon to delete it), make your change, and commit — same as above.

## Editing the About page or homepage text

The About page lives in `about.md` at the root of the repository, and can
be edited the same way.
