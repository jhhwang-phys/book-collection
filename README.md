# Book Collection Tracker

A lightweight, browser-based tool for managing academic book collections with real-time currency conversion and multi-store market search.

## Features

- **Collection & Wishlist management** — Track owned books and future purchases separately
- **Real-time currency conversion** — Live exchange rates across KRW, USD, EUR, GBP, JPY
- **Market Search** — Search Open Library for any book, browse editions/ISBNs, and find listings across 6 stores (Kyobo, Aladin, AbeBooks, Amazon, eBay)
- **Inline editing** — Click any entry to edit, delete, or move between Collection and Wishlist
- **Export/Import** — Save and restore data as Excel (.xlsx) or JSON (.json)
- **Zero server dependency** — All data stored in your browser's localStorage. No account needed.

## Usage

Visit **[https://hakuunnorei.github.io/book-collection/](https://hakuunnorei.github.io/book-collection/)** and start adding books.

Or download `index.html` and open it directly in any browser.

## Data & Privacy

All book data is stored exclusively in your browser's localStorage. Nothing is sent to any server. Each user's collection is completely private and independent.

## Data Portability

- **Export** your collection anytime as Excel or JSON via the Export dropdown
- **Import** previously exported files to restore or migrate data
- Data persists across sessions in the same browser via localStorage

## Tech Stack

- Single HTML file, no build step
- Vanilla JavaScript (no frameworks)
- [SheetJS](https://sheetjs.com/) for Excel import/export (loaded from CDN)
- [Open Library API](https://openlibrary.org/developers/api) for market search
- [ExchangeRate-API](https://www.exchangerate-api.com/) for live currency rates

## License

MIT
