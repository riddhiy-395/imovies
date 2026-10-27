# IMovies — Movie ticket booking made simple

A full-stack starter project using React + Vite, Express, MongoDB, and JWT. Includes movie browsing, registration/login, showtime selection, seat selection, booking history, and a demo seed endpoint.

## Requirements
- Node.js 20+ and npm
- MongoDB running locally, or a MongoDB Atlas connection string

## Run on macOS
1. Unzip the project and open Terminal.
2. Enter the project folder: `cd ~/Downloads/imovies` (adjust path if you saved it elsewhere).
3. Install dependencies: `npm install && npm run install:all`
4. Create server environment file: `cp server/.env.example server/.env`
5. Start MongoDB if using local MongoDB: `brew services start mongodb-community@8.0`
6. Start both apps: `npm run dev`
7. Open `http://localhost:5173` in Chrome. API runs at `http://localhost:5001`.

If the brew service name differs, check `brew services list`. For MongoDB Atlas, put your connection string in `server/.env` as `MONGO_URI=...`.

## Demo data
Once the server is running, seed demo movies by opening `http://localhost:5001/api/seed` in your browser (or run `curl http://localhost:5001/api/seed`). Then refresh the frontend.

## GitHub and demo links
These links do not exist until you publish the project. Create a GitHub repository, push this folder, then deploy the frontend (e.g. Vercel) and backend (e.g. Render) and configure `VITE_API_URL` to the deployed API URL. Do not submit placeholder URLs as real links.
