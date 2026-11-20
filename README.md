# Personal website

Source of my academic homepage, served by GitHub Pages.

Layout based on [Jon Barron's website template](https://github.com/jonbarron/jonbarron.github.io).

## Editing

- Everything lives in `index.html`. Each publication is one `<tr class="pub">` block; add `selected` to its class to show it under "Selected Publications".
- Put paper assets in `pubs/<year>.<ShortName>/` (teaser image / gif / mp4, `bibtex.txt`).
- Replace `images/portrait.svg` with your photo and update the `src` in `index.html`.
- Preview locally: `python3 -m http.server 8000`, then open http://localhost:8000
