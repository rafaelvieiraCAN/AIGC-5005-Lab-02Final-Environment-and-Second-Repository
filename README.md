# AIGC-5005-Lab-02Final-Environment-and-Second-Repository
# TVMaze Show Aggregator

This program downloads TV show records from the TVMaze API and produces summary statistics. The summaries help identify trends in genres, ratings, and premiere dates across a large collection of television shows.

## Data source

URL:
https://api.tvmaze.com/shows?page=0

Each record represents one television show.

The endpoint returns approximately 250 show records.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
# Windows:
# .venv\Scripts\activate

pip install -r requirements.txt
