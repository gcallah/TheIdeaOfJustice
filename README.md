# The Idea of Justice

I'll be teaching a class on this topic in spring 2027. I will outline that course here, as well as add thoughts on potential future modules.

## Editing the site

The site is plain HTML and CSS, published by GitHub Pages from `main` at
https://gcallah.github.io/TheIdeaOfJustice/.

After changing `style.css`, run `bin/bump-css-version` before committing. It
updates the `?v=` version on every page's stylesheet link, so browsers fetch the
new CSS instead of using a cached copy.

To start a new section, run `bin/new-section` with its numeral, title and
thinkers, e.g.

    bin/new-section VI "The Nineteenth Century" Hegel Marx "John Stuart Mill"

It creates the section's folder and pages, links it from the home page, and
adds a style rule per page. Background images are left for you: fill in each
`TODO` in the new style rules and page footers (see the comment at the top of
the script).
