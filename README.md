# Banana Detail — website

One static page, no build step, no dependencies.

**Live:** https://reflex08.github.io/banana-detail/

## Before sending it to anyone

Set the phone number. Every Call and Text link is generated from one value near the
bottom of `index.html`:

```js
var PHONE="";          // e.g. "416 555 0123"
```

While it is empty the buttons scroll to the services instead of opening a dead dialler.

## SEO notes

- `<title>` 57 chars, keyword front-loaded, brand last. `<meta name="description">` 154 chars.
- One `<h1>`; every `<h2>` is phrased as a question with a 40–60 word direct answer beneath
  it, which is the structure answer engines extract.
- JSON-LD in `<head>`: LocalBusiness/AutoWash with a nine-item offer catalogue, WebSite,
  HowTo (the booking steps) and FAQPage (eight questions). Every claim in the markup also
  appears in the visible copy.
- `robots.txt` allows GPTBot, ClaudeBot and PerplexityBot. `sitemap.xml` and a canonical
  tag are in place.
- `llms.txt` is published. It is a community proposal, not a search standard, and no engine
  is known to require it.

### Still to do, and it needs the owner

1. **Google Business Profile.** For a local service business this outranks everything on
   this page. Free, and it is what puts the business in the map pack.
2. **A service area.** The copy and schema deliberately name no city, because inventing one
   would be a false claim. Adding the real one to the `<h1>`, the FAQ and `areaServed` is
   the single biggest local-search win available here.
3. **Google Search Console.** Verify the domain and submit the sitemap, or there is no
   indexing data to work from.
4. **Reviews.** Review schema is omitted on purpose: marking up reviews that do not exist
   is the kind of thing that earns a manual penalty.
