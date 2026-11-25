# Vinod General Stores website

A Jekyll site for a neighbourhood store in New Alipore, Kolkata. Customers browse the shelves and send their order on WhatsApp.

## Structure
- `_config.yml`: site title, description and `baseurl`
- `_layouts/default.html`, `_includes/`: page shell, header and footer
- `_data/store.yml`: WhatsApp number, address, hours, steps and about text
- `_data/products.yml`: every product, price and stock status
- `index.html`: the home page
- `assets/`: CSS, JavaScript and images

## Update the shop
Edit `_data/products.yml` (prices, stock) and `_data/store.yml` (WhatsApp number), then commit.

## Run locally
    bundle install
    bundle exec jekyll serve

## Deploy
GitHub repo > Settings > Pages > Deploy from a branch > main, folder /(root).
Project sites also need `baseurl: "/REPO-NAME"` in `_config.yml`.
