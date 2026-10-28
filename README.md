# SchemeSathi — Premium full-stack prototype

## Requirements
- Node.js 18+
- Internet connection only if you want Google Fonts; system fallbacks are included.

## Run locally
1. Extract the ZIP.
2. Open a terminal in the `SchemeSathi` folder.
3. Run `npm install` once.
4. Run `npm start`.
5. Open `http://localhost:3000`.

## Backend API
- `GET /api/health` — service health
- `GET /api/meta` — catalogue metadata
- `GET /api/schemes?q=&category=&beneficiary=&page=1&limit=9` — search/filter schemes
- `GET /api/schemes/:id` — full scheme detail
- `POST /api/eligibility` — profile-based preliminary suggestions

## Project structure
- `server.js` — Express backend and API routes
- `public/index.html` — responsive frontend and client-side API integration
- `data/schemes.json` — 150 scheme/programme records with preliminary eligibility rules and official portal links

## Important data note
The 100 records are a student-project discovery catalogue, not a government-certified eligibility database. Several programmes are public services, infrastructure initiatives, financial products or legacy products rather than direct cash benefits. Rules, income ceilings, age limits, documents and application windows can change. The matching endpoint is intentionally labelled as preliminary and does not query government beneficiary databases. Review each record against the linked official guidelines before presenting it as verified.


## CEP project credits
Contributors: Gayatri Sanjay Suryawanshi, Sharayu Parmeshwar Shinde, Vaishali Ojha, Samiksha Sankad.

Scheme icons in this prototype are category illustrations rather than official government logos. Benefits and eligibility are concise preliminary summaries; always confirm current rules on the linked official portal.
