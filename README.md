# libretouch pages

This repository contains the static GitHub Pages site for libretouch. It is
deliberately independent of the Yocto build repository and has no generated
assets or JavaScript dependencies.

## Local preview

From this directory, run:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000> in a browser.

## GitHub Pages

Configure GitHub Pages to publish from the repository’s `main` branch and the
repository root. The site entrypoint is `index.html`.

