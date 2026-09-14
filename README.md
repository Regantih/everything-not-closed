# Everything Not Closed, web edition

Single-file book. `index.html` is the complete text with the interactive model; `Everything-Not-Closed.pdf` is the print edition; `cover.png` is the social preview.

Before first deploy, replace `SITE_URL` in `index.html` with the real host (e.g. `regantih.github.io/everything-not-closed` or your domain) so link previews resolve:

    sed -i 's#SITE_URL#regantih.github.io/everything-not-closed#g' index.html
