YOUFINDY SEARCH API (Serverless on Vercel)

Files:
- api/ping.js        → basic health check
- api/search.js      → reads Fashion_Affiliate_Stores.csv and returns matches
- Fashion_Affiliate_Stores.csv
- package.json

To deploy:
1. Go to https://vercel.com/new
2. Import this repo
3. Framework: Other
4. Leave all build fields blank
5. Click Deploy

Test URLs:
- /api/ping
- /api/search?q=party%20dress&region=UK
