# Cognifyz — Level 1, Task 1

**Summit Notes** — a single-page hiking journal built as a static webpage for the
Cognifyz Web Development internship (Level 1, Task 1).

## Task requirements covered

1. **Navigation menu with at least three links** — sticky top nav with
   *Trails*, *Journal*, and *Subscribe* anchors.
2. **Heading, paragraph & image** — full-bleed hero section with a title,
   intro paragraph, and a background photo.
3. **Form with an input field and a submit button** — an email subscribe form
   with client-side validation and inline feedback.

## Tech

- Plain **HTML5** and **CSS3** (no frameworks/build step).
- A small vanilla **JavaScript** handler validates the email and shows a
  success/error message on submit.
- Google Fonts: *Playfair Display* and *Source Sans 3*.

## Run it

It's a static page — just open the file in a browser:

```
# macOS
open index.html
# Windows
start index.html
# Linux
xdg-open index.html
```

Or serve it locally:

```
python -m http.server 8000
# then visit http://localhost:8000
```

## Files

- `index.html` — the entire page (markup, styles, and script).
