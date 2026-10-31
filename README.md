# Grade 8 Maths: interactive lessons

Student-facing interactive lesson pages, served with GitHub Pages so they can be embedded in Canvas.

- Site: https://jonnywoodsgh.github.io/School/
- The index page has an **Open lesson** link and a **Copy embed code** button for every lesson.

This repository is **public**. Only put student-facing lesson pages here. Teaching files, worksheets,
mark schemes, student work and textbooks stay in the private `EDU` repository.

## Layout

```
year8-maths/week-11/lesson-1-dividing-fractions.html
year8-maths/week-11/lesson-2-dividing-in-context-unit-8-review.html
year8-maths/week-11/lesson-3-calculating-angles.html
```

Use lowercase file names with hyphens and no spaces, so the web addresses stay simple.

## Adding next week's lessons

1. Make a folder such as `year8-maths/week-12/` and upload the `(Interactive).html` files, renamed as above.
   On github.com you can do this with **Add file → Upload files**.
2. Remove the speaker notes first. Anyone can read them with the **S** key on a public page.
   The publishing copies have every `data-say="..."` attribute removed.
3. Add the lessons to the `LESSONS` list in `index.html`.

## Embed code (Canvas: Edit → HTML editor → paste → Save)

```html
<div style="position: relative; width: 100%; padding-top: 56.25%;"><iframe src="https://jonnywoodsgh.github.io/School/year8-maths/week-11/lesson-1-dividing-fractions.html" title="Lesson 1" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" allow="fullscreen" allowfullscreen="allowfullscreen"></iframe></div>
```
