# 👻 Ghost Ads

Deploy to Render in 3 steps:

1. Push this repo to GitHub
2. Go to render.com → New → Web Service → connect your repo
3. Set these environment variables in Render dashboard:
   - JWT_SECRET = (generate with: node -e "console.log(require('crypto').randomBytes(48).toString('hex'))")
   - ANTHROPIC_API_KEY = your key from console.anthropic.com
   - NODE_ENV = production
4. Build Command: `npm install`
5. Start Command: `npm start`

Done. Your site is live with real accounts and AI ad generation.
