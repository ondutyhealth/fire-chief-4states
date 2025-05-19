# Fire Chief Scraper

This app scrapes fire department leadership contact info from major U.S. cities.

## 🚀 How to Use

### Local Setup
```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload

cd ../frontend
npm install
npm run dev
```

### Deploy
Use Vercel for frontend, Render for backend + worker.
Set environment variables from `.env.template`.
