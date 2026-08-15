# The Watch Patent Archive

Editorial-first storefront prototype for collectible watch patent art.

The concept is intentionally closer to a museum reading room or auction catalogue than a conventional ecommerce grid. Patent drawings are presented as artifacts with context, story, collection logic, and a clear path to purchase.

## Included in this prototype

- Editorial homepage and archive navigation
- Brand browsing and filtering
- Curated thematic collections
- Patent story / product detail modal
- Interactive “build around your watch box” matcher
- Watch + art pairing section
- Collector wall submission experience
- Responsive mobile navigation
- Zero-dependency static build for easy GitHub Pages hosting

## Important catalog note

The patent records and product copy in `app.js` are demonstration content used to establish the editorial and UX system. Before launch, replace them with the user's verified patent records, patent drawings, historical research, print sizes, pricing and inventory. The data model is intentionally simple so the catalog can later move into JSON, a CMS, Shopify, or another commerce backend without redesigning the front end.

## Preview locally

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.
