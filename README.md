# Vantora Storefront Catalogue

Static regional storefront pages. Each region has two tiers:

- `catalog/<REGION>/member/` — member storefront prices (already discounted).
- `catalog/<REGION>/public/` — standard storefront list prices.

Every product page carries a schema.org Product/Offer record in embedded
JSON-LD. Regional banners advertise the maximum membership saving; actual
per-market discounts vary by product and by market.
