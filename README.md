### iframe-sandbox-bootstrap

[`iframe-sandbox`](https://github.com/kumavis/iframe-sandbox) creates an iframe via a `blob:` url.
Blob urls can't use a hash location or query params.
If you don't want to use blob urls, you can point it at this bootstrapped html.
This html contains everything that `iframe-sandbox` normally injects.
It is comprised only of static assets.

### build

You may want to host your own. To build the static assets:
```
npm install
npm start
```

Now host `index.html` and `bundle.js` somewhere.