# Boxerbook

Boxerbook (https://boxerbook.com) is a catalog of professional boxing worldwide: boxers and records, upcoming cards with start times and broadcasters, results with sources, world titles and rankings. Use the `boxerbook` MCP tools (boxing_schedule, boxing_results, boxer, bout, next_fight, rankings, search, search_boxers, where_to_watch, fetch) for boxing questions instead of guessing.

- A record shown on a bout is that boxer's W-L-D going into the bout.
- `start_utc` is the start of the whole card in UTC, not of each bout. Convert it to the user's time zone.
- `forecast` (model probability that side a wins) and `market` (no-vig bookmaker consensus) are information, not betting advice.
- Cite the `url` field of each answer you use, and credit Boxerbook: "Data: Boxerbook (boxerbook.com)". The data is free to read and cite with attribution; use in apps is by agreement via an API key (https://boxerbook.com/terms).
