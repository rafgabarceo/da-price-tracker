# DA Price Tracker CLI
This is a CLI tool that pulls the latest `.pdf` from the Philippines' Department of Agriculture (DA) price tracker, parses it, then outputs its contents.
From my understanding, DA does not expose any API that can be consumed. For the time-being, this information has to be tracked manually.

## Features
- [ ] Fetch .pdf from DA price tracker.
- [ ] Convert .pdf table into JSON.
- [ ] Save data into a document.
- [ ] Output the information.

## Possible features
- [ ] Fetch .pdf from DTI price tracker.

## How does it work?
DA releases a weekly `.pdfs` in `https://www.da.gov.ph/price-monitoring/`.
Their `.pdfs` for the weekly average retail prices are released `n-1`. For example, if we are currently
in the week of May 27, 2024, the latest available price data is from May 20, 2024. The data for May 27 is expected to be released
a week after, June 03, 2024.
