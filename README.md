# The Watch Patent Archive

Editorial-first storefront for 427 finished works of collectible watch patent art.

The concept is intentionally closer to a museum reading room or auction catalogue than a conventional ecommerce grid. Patent drawings are presented as artifacts with context, story, collection logic, and a clear path to purchase.

## Included in the storefront

- Editorial homepage and archive navigation
- Brand browsing and filtering
- Curated thematic collections
- Searchable and filterable catalog of all finished artwork
- Real patent artwork and verified catalog metadata
- Patent story / product detail views with related works
- Interactive “build around your watch box” matcher
- Watch + art pairing section
- Collector wall submission experience
- Responsive mobile navigation
- Zero-dependency static build for easy GitHub Pages hosting

## Catalog architecture

`catalog.json` is the storefront source of truth. It contains only records whose production status is Ready for Sale; source patents still in development are intentionally excluded. Product images live in `assets/products/`, keyed to the archive's stable WPA identifiers. The data layer can later move into Shopify, a CMS, or another commerce backend without redesigning the front end.

## Preview locally

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.
