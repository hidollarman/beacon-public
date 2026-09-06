# Beacon

SPX 5-minute direction prediction dashboard.

## Live demo
https://hidollarman.github.io/beacon-public/

## Features
- Dark background (#0B0F14)
- Current SPX price in large bold text
- Today's open price
- Point change and percentage change
- Pacific time clock (top left)
- Intraday chart from market open to now (solid line)
- 5-minute forecast extension (dotted fluorescent line: green up, red down, gray sideways)
- Color-coded current price: solid green above open, solid red below, gray flat

## Data
- Primary: IBKR via MCP connector (https://api.ibkr.com/v1/api/mcp-public) + Cboe Streaming Market Indexes ($3.50/mo)
- Fallback: free public sources for demo/offline

## Next steps
1. Subscribe to Cboe Streaming Market Indexes in IBKR Client Portal.
2. Connect IBKR connector in Grok.
3. Deploy via Grok Build or host this repo.
4. Add Grok Bot automation for live updates.

Logo placeholder — add later.