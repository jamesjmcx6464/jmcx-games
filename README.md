# JMCX Games

A static hub for James Murray's classroom games. Open `index.html` — there is no build step.

Play links open each game on Cloudflare Pages. Where a game has an itch.io page, **More on itch.io** is the place to download a copy if one is offered.

## Deploy

This folder is the site root. Create a GitHub repo and point Cloudflare Pages at it (framework preset: None, build command empty, output directory `/` or empty).

After the Pages URL is live, you may want to change the `og:image` and `twitter:image` tags in `index.html` to absolute URLs so link previews work everywhere.
