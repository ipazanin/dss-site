# domain-software-solutions.hr

The company site of Domain Software Solutions d.o.o. It is plain HTML and CSS with no build step, served by GitHub Pages at https://domain-software-solutions.hr.

`index.html` is the English page and `hr/index.html` the Croatian one. Change both together. Fonts are self-hosted in `assets/fonts`, so the site makes no third-party requests.

Preview locally with `python3 -m http.server 8000` and open http://localhost:8000.

`kuna/`, `tipsy/` and `shunt/` only redirect to the apps on `ipazanin.github.io`, keeping the query and hash. The apps stay on their own origin because their saved data lives in that origin's browser storage. Cloudflare redirect rules send `kuna.`, `tipsy.` and `shunt.domain-software-solutions.hr` to the same places.
