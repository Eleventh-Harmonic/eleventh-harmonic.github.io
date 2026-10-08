# Eleventh Harmonic – website

Privacy policies for Eleventh Harmonic's apps, served by GitHub Pages:
<https://eleventh-harmonic.github.io/>

Plain HTML and one CSS file. No build step, no scripts, no cookies, no
analytics, no external fonts.

## Pages

| Page | URL |
|---|---|
| Home | <https://eleventh-harmonic.github.io/> |
| Metronome Eleven privacy policy | <https://eleventh-harmonic.github.io/metronome/privacy/> |

## Structure

```text
index.html                    home: the brand and its apps
metronome/privacy/index.html  Metronome Eleven privacy policy
assets/style.css              shared style (light and dark)
assets/favicon.svg
.nojekyll                     serve files as they are (no Jekyll)
```

## Add an app

1. Copy `metronome/privacy/index.html` to `<app>/privacy/index.html`.
2. Rewrite the text for that app, and set its `<title>`, description,
   canonical URL, "Last updated" date and version history.
3. Add the app to the list in `index.html`.

## Change a policy

- **Never rename or move a published page.** Its URL is in the Play
  Console and inside the app.
- Edit the page in place, update "Last updated", and add a line to its
  version history.
- Keep the section ids (`#purchases`, `#rights`, …) stable: other pages
  may link to them.
- If an app's data handling changes, update its Google Play Data safety
  form at the same time.

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000/
```
