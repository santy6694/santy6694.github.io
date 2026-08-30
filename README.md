# santy6694.github.io

Personal portfolio site for Santhosh Murugesan Renuka Siva, built with Jekyll on GitHub Pages
using the "Dominic" one-page HTML template.

## Adding a blog post

Drop a Markdown file into the `_posts/` folder — see `_posts/README.md` for the naming
convention and required front matter. It will automatically show up in the **Blog** section
on the home page and get its own page, with no other changes needed.

## Local preview

```bash
bundle exec jekyll serve
```

## Contact form

The template's original PHP mailer doesn't run on GitHub Pages (static hosting only). The
contact form in `index.html` posts to a placeholder Formspree endpoint — replace
`REPLACE_WITH_YOUR_FORM_ID` in the form's `action` attribute with your own
[Formspree](https://formspree.io) (or similar) form ID to make it functional.

## Documents

Downloadable resume and a corrected cover letter live under `assets/docs/`.
