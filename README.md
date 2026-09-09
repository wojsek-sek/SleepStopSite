# SleepStop — website

The public website for **SleepStop**, an app that pauses whatever you're listening to the moment
you fall asleep, and puts you back exactly where you left off.

Three static pages: a home page introducing the product, the privacy policy, and a support page.

## Stack

Plain HTML and CSS. No framework, no build step, no JavaScript beyond native `<details>`.

```
index.html      Home
privacy.html    Privacy policy
support.html    Contact card and FAQ
styles.css      Shared styles
assets/         Brand mark, link-preview cover, screenshots, self-hosted fonts
```

## Design

"Nokturn" — a deep ink gradient, moon-gold accent, Cormorant Garamond for display type. Dark theme
only, by decision.

## Previewing locally

No build step — serve the folder:

```sh
python -m http.server 8137 --bind 127.0.0.1
# then open http://127.0.0.1:8137/index.html
```
