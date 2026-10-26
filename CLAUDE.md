# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Personal one-page site for `linkedlist.cz`, served by GitHub Pages from `master`. It is plain static HTML: no build step, no JavaScript and no external dependencies. `.nojekyll` stops GitHub Pages from running Jekyll.

- `index.html` is the whole site. Its CSS is inline in a `<style>` block.
- `404.html` is what GitHub Pages serves for unknown paths, including the URLs of the old blog posts.
- `CNAME` holds the custom domain. Don't remove it.

`404.html` repeats the inline CSS from `index.html`, so keep the two in sync.

Preview by opening `index.html` in a browser (`open index.html`). There is nothing to build or test.

Keep the page minimal: no frameworks, web fonts, scripts, analytics or third-party embeds.

The old Jekyll blog (Type Theme, posts from 2014–2018) was removed. It is still in git history up to commit `a63c7a2`.
