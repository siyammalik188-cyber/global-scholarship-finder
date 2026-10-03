# Global Scholarship Finder

An open-source, multilingual-first scholarship discovery platform for students worldwide.

## Current MVP

- Search and filter verified scholarship opportunities
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

Scholarship records should link to official sources and include a last-verified date before production use. The current sample data is a prototype dataset for interface testing; users should confirm deadlines and eligibility on each official provider website.

## Roadmap

1. Add a structured scholarship database and verification dashboard.
2. Add country-specific eligibility rules and translations.
3. Add email/calendar deadline reminders.
4. Add contributor workflows and audit history.
5. Add a backend API and production deployment.

## License

MIT
