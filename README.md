# Daily Departure

A daily aviation trivia game. Seven questions, check-in to chocks on: the rarer your answer, the better your seat.

- `index.html` is the whole game (one self-contained file).
- Results are recorded to Supabase with the public publishable key; row level security allows inserts only.
- `.github/workflows/keepalive.yml` pings the database every 3 days so the free project never pauses.

All rights reserved.
