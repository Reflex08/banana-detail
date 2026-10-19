# Banana Detail — website

One static page, no build step, no dependencies. `index.html` is the whole site.

**Live:** https://reflex08.github.io/banana-detail/

## Setting the phone number

Every Call and Text link is built from one value near the bottom of `index.html`:

```js
var PHONE="";          // e.g. "416 555 0123"
```

Fill it in and every button on the page works. While it is empty the buttons scroll to
the services section rather than opening a dead dialler.

## Changing prices

Prices live in the service cards in `index.html`. They are starting prices and are worded
that way on the page — the final figure is agreed with the customer before work begins.
