# Personal website

## Publishing short articles in MISC

Articles live directly in `index.html`, inside `<section id="misc">`.
You can edit this file on GitHub or locally.

1. Find the commented article template in the MISC section.
2. Copy the `<article>...</article>` block outside the `<!-- ... -->` comment,
   inside `<div class="misc-articles">`. Put the newest article first.
3. Replace the title, date (both `datetime="YYYY-MM-DD"` and the visible date),
   and paragraphs with your writing. Wrap each paragraph in `<p>...</p>`.
4. When publishing your first article, remove
   `<p class="misc-empty">No articles yet.</p>`.
5. Commit the changes to `main`. GitHub Pages will publish them through the
   repository's existing deployment process.

Readers click an article title to expand or collapse it. To display an article
expanded by default, change `<details>` to `<details open>`.

Use `<a href="https://example.com">link text</a>` for links. In ordinary article
text, write `&amp;` for `&`, `&lt;` for `<`, and `&gt;` for `>`.

The MISC section can be linked directly at
https://zhuohuangai.github.io/#misc. Publishing is done by editing the repository;
there is no browser-based article editor or sign-in system on the public page.
