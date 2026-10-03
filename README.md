# Global Scholarship Finder

An open-source, multilingual-first scholarship discovery platform for students worldwide.

## Current MVP

- Search and filter official-source-linked prototype opportunities
- Filter by degree, destination, funding, and field of study
- Save opportunities locally in the browser
- Build a private student profile for matching
- Link directly to official scholarship sources
- Responsive, accessible, low-dependency frontend

## Run locally

This MVP is a static site. Open `index.html` in a browser, or serve the folder with any static web server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Data trust rules

The current eight records are prototype listings for interface testing. They are not presented as a complete or currently verified database. Users should confirm eligibility, deadlines, and application requirements on each official provider website before applying.

The planned data workflow is documented in [`data/README.md`](data/README.md), with a machine-readable schema in [`data/scholarships.schema.json`](data/scholarships.schema.json). A listing must have an official source, a verification status, and a reviewer/date before it can be marked verified.

## Roadmap

1. Import structured records into the app from the data directory.
2. Add a verification dashboard and reviewer audit history.
3. Add country-specific eligibility rules and translations.
4. Add email/calendar deadline reminders.
5. Add a backend API and production deployment.

## License

MIT
