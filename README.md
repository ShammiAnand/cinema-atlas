# Cinema Atlas

An editorial, explorable knowledge graph for films, actors, directors, and time.

## Data provenance
The app ships with a curated local JSON catalog of real films and credits. The intended source is IMDb's official non-commercial datasets (`title.basics`, `title.crew`, `title.principals`, and `name.basics`), available at `datasets.imdbws.com`. The catalog is stored locally so the visualization works offline and requires no API key. IMDb data is used for non-commercial purposes and is attributed in the app footer.

## Run

```bash
python3 -m http.server 4173 --directory .
```

Then open `http://localhost:4173`. For a Vite install, use `npm run dev` after installing Vite.
