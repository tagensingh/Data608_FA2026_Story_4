# DATA 608 Fall 2026 - Story 4: What separates profitable NYC Airbnbs from the rest?

Analyst view: what underperforming hosts can change to earn more. Quarto (R) for CUNY SPS DATA 608, Data Story 4.

- `story4_slides.qmd` / `story4_slides.html` / `story4_slides.pdf` - slide deck (revealjs) and PDF export
- `story4_report.qmd` / `story4_report.pdf` - the same analysis as a PDF report (Typst)
- `data/nyc_airbnb_listings.csv` - Inside Airbnb NYC listings (course dataset)
- `data/neighborhoods.geojson` - NYC neighborhood boundaries (course dataset)

## Render

Requires R with tidyverse, ggrepel, scales, sf, patchwork and ggridges, plus Quarto.
Run `quarto render story4_report.qmd` and `quarto render story4_slides.qmd`.
For the slide PDF, open `story4_slides.html?print-pdf` in Chrome and print to PDF.
