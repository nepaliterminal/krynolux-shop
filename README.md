# Krynolux

Static storefront by abhinav. No dependencies, build step, or JavaScript.

Run `python3 -m http.server 8000 --bind 127.0.0.1` from this directory.

## GitHub Pages

After creating `nepaliterminal/krynolux-shop`, push `main` and select **Settings > Pages > Deploy from a branch > main / (root)**. Add a DNS CNAME record `shop` pointing to `nepaliterminal.github.io`, then set **Settings > Pages > Custom domain** to `shop.krynolux.work` and enable HTTPS when available. `CNAME` and `.nojekyll` are included.

## Content and design

Website terms come from `local-shop-sites/outreach/replies.md` and `local-shop-sites/outreach/outreach.md`. Actor titles and descriptions come from `apify-actors/*/.actor/actor.json`; Shopify review pricing is in `apify-actors/scripts/publish.mjs`. The flashcard is a labeled illustrative example, not a screenshot or customer claim.

Design read: printed-catalog storefront for students, local businesses, and data buyers. ENERGY 2 / RHYTHM 3 / MOTION 1. Warm paper and dark green ink give the mixed catalog a coherent, physical-shop character; rust marks the headline and interactive emphasis. Georgia supplies an editorial voice without font downloads; Arial keeps dense descriptions readable. Numbered catalog sections repeat as an index motif. A featured study panel, service estimate, and compact data list reflect the different buying decisions. The tilted flashcard illustrates the actual study format; it is not an interactive control. No decorative icons, stock imagery, gradients, or animation. All content is static, so there are no asynchronous loading, empty, or form-error states.
