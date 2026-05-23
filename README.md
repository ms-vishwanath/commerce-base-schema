# Commerce Base Schema

An open-source, production-ready e-commerce database schema written in [DBML](https://dbml.dbdiagram.io/).

## Overview

This schema covers the core entities of a modern e-commerce platform:

- **Users & Auth** — users, sessions, addresses
- **Catalog** — categories, subcategories, products, variants, attributes, SEO, tags, images
- **Shopping** — cart, wishlist, cart items
- **Orders & Fulfillment** — orders, order items, payments, shipments, returns
- **Reviews** — product reviews with approval workflow
- **Coupons** — discount coupons with usage tracking
- **Inventory** — inventory change logs
- **Notifications** — user notification system
- **Configuration** — COD settings, tax rates, shipping rates

## Files

| File | Description |
|------|-------------|
| `dev-schema.dbml` | The full database schema definition |
| `dev-schema.dbdiagram` | Visual layout for [dbdiagram.io](https://dbdiagram.io) |

## Usage

Open `dev-schema.dbml` in [dbdiagram.io](https://dbdiagram.io) or any DBML-compatible tool to view and modify the schema.

## License

MIT — see [LICENSE](LICENSE).
