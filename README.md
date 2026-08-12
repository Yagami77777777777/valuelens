# ValueLens V3 — Smartphone Intelligence

This V3 focuses on the AI Finder rather than simple keyword matching.

## AI Finder
- Parses natural-language requests.
- Detects Indian budgets such as `50k`, `₹50,000`, `50000`, `50 thousand`, `1.2 lakh`.
- Separates phone model numbers from budget numbers.
- Fuzzy-matches the user's current phone.
- Understands multiple priorities: camera, gaming/BGMI, performance, battery, display, charging, software, storage and compactness.
- Uses category-specific scoring instead of treating one specification (such as megapixels) as overall quality.
- Penalizes recommending the user's current phone.
- Rewards meaningful upgrades over the current phone.
- Produces a ranked top-5 shortlist with reasons.

## Catalogue
The site loads the public 2025 mobile dataset as CSV and correctly parses its CSV structure. It filters out tablets/oversized devices so the catalogue is phone-focused.

## Important
Current value and depreciation are estimates, not live resale prices. For a production commercial product, use licensed/current pricing and a server-side AI/LLM layer with protected API credentials.
