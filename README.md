# public-sites

Privacy policies and support pages for my apps, served with GitHub Pages at
https://jsecker-debug.github.io/public-sites/

## Layout

- `index.html` lists every app.
- `<app>/index.html` is that app's privacy policy (`#privacy`) and support page (`#support`).

| App | Privacy Policy URL | Support URL |
| --- | --- | --- |
| Haunts | https://jsecker-debug.github.io/public-sites/haunts/#privacy | https://jsecker-debug.github.io/public-sites/haunts/#support |
| Yomi | https://jsecker-debug.github.io/public-sites/yomi/#privacy | https://jsecker-debug.github.io/public-sites/yomi/#support |

Yomi also has its terms of use at https://jsecker-debug.github.io/public-sites/yomi/#terms.

## Adding an app

1. Copy `haunts/` to a new folder named after the app and rewrite the content.
2. Add the app to the list in `index.html` and to the table above.
3. Use the new URLs in App Store Connect and in the app.

The App Store URLs for an app must keep working for as long as it's on sale, so
don't rename or move an app's folder once it has shipped.

`.nojekyll` makes GitHub Pages serve the files as they are.
