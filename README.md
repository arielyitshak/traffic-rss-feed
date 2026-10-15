# Optional CCISS public RSS collector

Prepared only; not installed, connected or running.

Proposed dedicated public GitHub repository: `traffic-rss-feed`.
Contains only this collector and unmodified public CCISS RSS data, plus the fetch timestamp. No trip itinerary, dates, hotel, reservations, passwords or API keys.

GitHub Actions would attempt a refresh every ten minutes. Scheduled actions can be delayed; this is not a guarantee of immediate reporting. The trip server must reject stale or invalid snapshots and preserve attribution to CCISS, rather than claim that roads are open.

Connecting the repository and its feed to the trip application requires the user's separate GitHub authorization. No repository has been created and no GitHub account has been accessed.
