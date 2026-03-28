# Mercury Trading Dashboard

A professional trading dashboard with live market data, portfolio tracking, screener, macro indicators, and AI analysis.

## Deploy to GitHub Pages (2 minutes)

1. Create a new GitHub repository (name it anything, e.g. `mercury-trading`)
2. Upload `index.html` to the repository
3. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
4. Your dashboard is live at `https://yourusername.github.io/mercury-trading`

## Add Your Anthropic API Key

1. Open the dashboard
2. Go to **Settings → Anthropic API Key**
3. Paste your key and click **Save & Test**
4. Key is stored in your browser's localStorage — never leaves your device

## Data Sources

| Source | Data | Key Required |
|--------|------|-------------|
| Yahoo Finance | Stock prices, RSI, 200MA, Oil, Gold, DXY, VIX | No |
| FRED (St. Louis Fed) | GDP, CPI, Unemployment, Fed Funds, Yields | Built-in |
| Anthropic Claude | AI 13-factor analysis | Yes — add in Settings |
