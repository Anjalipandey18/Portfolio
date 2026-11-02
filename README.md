# EDELPRIME – Ecommerce Website

Multi-page static website (HTML + CSS + JavaScript). No build step needed.

## Structure
```
index.html            Home
shop.html             Product listing (filters: ?c=category&s=sub&q=search&wl=1)
product.html          Product detail (?id=)
cart.html  checkout.html  track.html  account.html
contact.html  about.html  blog.html
faqs.html  terms.html  privacy.html  cookies.html  returns.html
careers.html  warranty-policy.html  disclaimer.html  caution-notice.html
pricing-payments.html  loyalty-hub.html  store-locator.html  edelprime-stores.html
assets/
  css/style.css       All styles
  js/data.js          Config, categories, products
  js/helpers.js       UI helpers, product card, cart/wishlist state
  js/pages.js         Page renderers (home, shop, product, cart, checkout ...)
  js/main.js          Menus, footer, page dispatcher
  js/faq.js           FAQ category filter
  img/                Put edelprime-logo.png here (black logo on white)
```

## Run
Open `index.html`, or host the folder on any web hosting. For local testing use
VS Code "Live Server" or `python -m http.server`.

## Notes
- Product data lives in `assets/js/data.js`. Cart, wishlist and orders are saved in the browser (localStorage) – demo mode, payment is simulated.
- Replace the dummy phone number `+91 98765 43210` in every page footer / contact page.
- Add the "Last updated" date to the policy pages (terms, privacy, cookies, returns).
