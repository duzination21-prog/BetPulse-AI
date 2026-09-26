# EdgeAI - Betting Signals Backend

Backend API server and automated AI engine for fetching live sports bookmaker odds, calculating Expected Value (+EV), and serving real-time betting signals to mobile clients.

## Features
- **Live Odds Ingestion:** Fetches real-time odds data across major sports leagues.
- **AI Expected Value (+EV) Engine:** Runs statistical models to spot mispriced odds and calculated value edge.
- **Kelly Criterion Calculator:** Recommends optimal bankroll stake percentage for risk management.
- **Express API Endpoint:** Delivers structured JSON signal feeds to mobile apps.

## Tech Stack
- **Node.js & Express:** API Web Gateway
- **Python 3:** Data analysis, probability model execution, and +EV calculations
- **The Odds API:** Live sports odds data source

## API Endpoints
- `GET /api/signals`: Returns array of active high-EV AI betting signals.
 
