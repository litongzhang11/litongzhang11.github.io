# litongzhang11.github.io

Academic personal website for Litong Zhang (USC Marshall, Finance and Business Economics).

Static single-page site: no build step, no dependencies. `index.html` contains the markup, styles, and scripts.

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Updating content

| What | Where |
| --- | --- |
| Papers, abstracts | `#research` section in `index.html` |
| Teaching, service | `#teaching` / `#service` sections |
| CV | replace `assets/files/cv.pdf` |
| Portrait | add `assets/img/profile.jpg`, then swap the `.portrait-ph` placeholder block for `<img src="/assets/img/profile.jpg" alt="Portrait of Litong Zhang" />` |

## Deployment

Pushing to the `main` branch of the `litongzhang11.github.io` repository publishes to https://litongzhang11.github.io (GitHub Pages, source = `main` branch, root folder).
