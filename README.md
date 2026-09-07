# RIVA — Real Estate Friend

A polished, fully offline real-estate chatbot for RIVA Real Estate.

## What it does

- Works entirely in the browser with no API key or backend
- Understands common typos, messy wording and short questions
- Handles buying, renting, investing and general real-estate concepts
- Covers Dubai/UAE topics such as freehold, leasehold, off-plan, service charges, mortgages, ROI and buying costs
- Uses friendly fallbacks for nonsense or unclear questions instead of breaking
- Includes quick-start questions and a responsive mobile layout
- Keeps the current conversation in the page while it is open

## Important limitation

This first version is a local knowledge-based assistant. It does **not** have an online LLM, live property listings, live prices, live availability or live market data. It should never be presented as a source of live property facts or legal/financial advice.

## Run it

Open `index.html` directly in a browser. Because it has no external dependencies, it works offline.

## GitHub Pages

In the repository settings, open **Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. GitHub will provide the public Pages URL.

## Roadmap

1. Expand the local RIVA knowledge base.
2. Add a structured property-search conversation flow.
3. Add RIVA's real listing database when one is available.
4. Add optional online AI mode separately from the offline mode.
5. Add WhatsApp/inquiry integrations without exposing secrets in the frontend.

Built for RIVA Real Estate.
