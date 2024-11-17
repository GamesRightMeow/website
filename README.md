# Run locally

`npm run serve`

# Tag guide

- `page` = one off web pages (about, consulting, etc)
- `project` = project pages
- `featured-project` = projects that are featured on consulting page
- `garden` = garden posts
- `hide-recently-tended` = hides post from recently planted widgets
- `hide-recently-planted` = hides post from recently tended widgets

# Dates
`tended` and `planted` dates must be in ISO UTC format `YYYY-MM-DD[T]HH:mm:ss.SSS[Z]`, or `iso` if `Insert Date String (jsynowiec.vscode-insertdatestring)` extension.

Googling `date in iso utc` will return the current date in the correct format (UTC).

This website is also handy https://www.timestamp-converter.com/

# Notes
- Regen favicon files at https://realfavicongenerator.net/
- Debug build time via `set DEBUG=Eleventy:Benchmark* & npm run serve`