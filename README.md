# NasdaqGuru Portfolio

This repository publishes the public portfolio through GitHub Pages at `nasdaqguru.github.io`.

## Structure

- `index.html` — primary public landing page.
- `projects/` — organized project pages, including FAS CFO, Harvard schools, advancement, technology, and command-center work.
- `career/` — resume and career-focused materials.
- `portfolio/` — portfolio and navigation pages.
- `archive/` — retained experiments and legacy material.
- `assets_FASCFO/` and `docs/` — existing shared assets retained at their original URLs for compatibility.

## URL compatibility

Existing project URLs remain as small redirect pages at their original paths. Do not remove those redirect files unless external links, bookmarks, and search results using the prior address have been deliberately retired.

When adding a new page, place it in the appropriate directory and use root-relative links, such as `/projects/advancement/example.html`. Root-relative links continue to work regardless of the folder depth of the page containing the link.

## Publishing

GitHub Pages serves this repository directly. Review changes locally, then commit and push them to the publishing branch.
