# BondStats Global Financial Clock — Original SDK Widget

This version intentionally does not recreate the clock UI.

It embeds the production BondStats Embedded Intelligence component:

    <bondstats-financial-clock></bondstats-financial-clock>

using:

    https://botapi33.github.io/bondstats-embed-sdk/embed.js

This keeps the homepage widget on the same tested responsive implementation as the SDK component.

## Deploy

Upload `index.html` and `.nojekyll` to the homepage-widget GitHub repository and enable GitHub Pages.

Then embed the GitHub Pages URL in Google Sites.

## Important

Do not reuse v1-v4. Those were standalone recreations. This version delegates rendering and mobile behaviour to the existing BondStats SDK component.
