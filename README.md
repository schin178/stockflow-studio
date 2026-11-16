# StockFlow Studio

Service website for Google Sheets inventory systems and purchase-order tracking, with a working in-browser demo.

**Live site:** https://schin178.github.io/stockflow-studio/

## Features
- Inventory demo: live stock balance, stock in/out, reorder and out-of-stock alerts (sample tile-shop data)
- Purchase-order demo: 5-step flow (Request → Approval → PO sent → Dispatched → Received); received stock is added automatically
- Demo login `demo` / `demo123`. Data is fake and kept in your browser (localStorage); the Reset button restores it
- Light/dark theme, mobile layout, scroll and View Transition animations
- SEO: meta tags, Open Graph, JSON-LD, sitemap.xml, robots.txt, llms.txt

## Tech
Plain HTML, CSS and JavaScript in a single `index.html`. No framework or build step. Fonts come from Google Fonts.

## AI disclosure
Built with help from Claude (Anthropic's AI assistant) for the code and layout.

## Run locally
Open `index.html` in a browser, or run `python -m http.server`.

Made by Sachin, India. Orders: https://www.fiverr.com/skhero178
