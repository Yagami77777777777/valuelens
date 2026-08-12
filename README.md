# ValueLens V2 Final Homepage

The first page directly contains the 30-phone catalogue. Cards include:
- phone visual
- brand/model
- current price
- launch price
- depreciation
- value score
- popularity score
- dynamic sorting

Default order is a prototype popularity score. Replace `demandScore`/`popularityScore` with live analytics and market signals in production.

Run locally:
`python -m http.server 8000`
Then open `http://localhost:8000`.

Important: all prices and popularity signals are illustrative. Use verified/licensed data before public launch.
