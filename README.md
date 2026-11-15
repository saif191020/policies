# App policies

Privacy policies and terms for apps by SBA Developer, served with GitHub Pages at
**https://saif191020.github.io/policies/**.

| App | Page | Address |
|---|---|---|
| Zipped | Privacy policy | https://saif191020.github.io/policies/zipped/privacy.html |
| Sastra Home | Privacy policy | https://saif191020.github.io/policies/sastra-home/privacy.html |
| Sastra Home | Terms and conditions | https://saif191020.github.io/policies/sastra-home/terms.html |

The Sastra Home pages moved here from Flycricket (`pages.flycricket.io/sastra-home/`) with their
wording unchanged; only Flycricket's ad and generator credit were left out.

## Add an app

1. Make a folder named after the app, in lowercase with dashes: `my-app/`.
2. Copy `zipped/privacy.html` into it and rewrite the text for that app. Keep the
   `../assets/style.css` link and the "App policies" link at the top.
3. Add a terms page (`my-app/terms.html`) only if the app needs one: accounts, purchases,
   subscriptions or content people post. Google Play requires only the privacy policy.
4. Add the app to the list in `index.html` and to the table above.
5. Push to `main`. GitHub Pages publishes in a minute or two. Paste the page's address into the
   app's Play Console listing (Policy > App content > Privacy policy).

Keep each address stable once it is in Play Console: Play checks that the link works, and a
broken policy link can get an app suspended. When a policy changes, update the page and its
date in place instead of moving it.

## Layout

    index.html             list of apps
    assets/style.css       shared look, light and dark
    <app>/privacy.html     one folder per app
    <app>/terms.html       optional
    .nojekyll              serve the files as they are, without Jekyll
