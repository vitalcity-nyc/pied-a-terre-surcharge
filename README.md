# Pied-à-terre surcharge — explainer infographics

Three embeddable infographics in Vital City style, built to accompany Martha E. Stark's
essay "Before You Surcharge the Penthouse, Fix the Foundation."

| File | Box | What it shows |
|---|---|---|
| `box1.html` | Box 1 | How the surcharge works, and who has to do what — a 5-step timeline with actors and deadlines |
| `box2.html` | Box 2 | Five questions the rules still have to answer |
| `box3.html` | Box 3 | What clear primary-residence rules should look like |
| `uneven-base.html` | Companion | How the underlying NYC property tax system works — four classes, four valuation logics, and the inequities they produce. Every figure tracked to a primary source. |

## Design

- Follows the [Vital City design system](https://github.com/Vital-City-NYC/vital-city-design-system):
  Halyard (Typekit `qqk2vto`) for all type, Gascogne reserved for large display numerals only,
  white card on a 1px black border, brand palette (chartreuse date chips, orange accents,
  magenta co-op aside).
- No kicker, sentence-case headlines set in Halyard Black — consistent with the infographic
  rules in the brand skill.

## Embedding in Ghost

Each file supports `?embed=1`, which strips the outer card border/padding and posts its content
height to the parent window (canonical Vital City embed pattern). Paste one HTML card per box into
a Ghost HTML card. Replace the `src` host once deployed (expected: `https://vitalcity-nyc.github.io/pied-a-terre-surcharge/`).

See `ghost-embeds.html` for the three ready-to-paste snippets.

## Source

Boxes 1–3 are drawn from Martha E. Stark, "Before You Surcharge the Penthouse, Fix the Foundation,"
Vital City — specifically Boxes 1, 2 and 3 of the piece. No independent data analysis; these are
faithful visual restatements of the article's explanatory boxes. The placeholder `href="#"` in each
source line should be set to the published article URL before going live.

`uneven-base.html` is a companion explainer on the underlying property tax system. Every assertion is
tracked to a primary source, cited in the graphic's own footer:

- Tax classes, assessment ratios (Class 1 = 6%; Classes 2/3/4 = 45%), and the capped-value example:
  [NYC DOF — Determining Your Assessed Value](https://www.nyc.gov/site/finance/property/property-determining-your-assessed-value.page)
  and [Determining Your Market Value](https://www.nyc.gov/site/finance/property/property-determining-your-market-value.page).
- Assessment-increase caps (Class 1 = 6%/yr, 20%/5yr; small Class 2 = 8%/yr, 30%/5yr):
  [N.Y. Real Property Tax Law § 1805](https://www.nysenate.gov/legislation/laws/RPT/1805).
- Income-approach mandate for co-ops/condos: [RPTL § 581](https://www.nysenate.gov/legislation/laws/RPT/581).
- All ratios, effective tax rates, and class-share figures (Tables 4, 6, 9, 10, 13; DOF data):
  [NYC Advisory Commission on Property Tax Reform, "The Road to Reform," Dec. 29, 2021](https://www.nyc.gov/assets/propertytaxreform/downloads/pdf/final-report.pdf).
- Litigation: [Tax Equity Now NY LLC v. City of New York, N.Y. Court of Appeals (Mar. 19, 2024)](https://www.nycourts.gov/ctapps/Decisions/2024/Mar24/1opn24-Decision.pdf).

Effective tax rates are medians per $100 of sales-based market value (FY2021). "Assessed at" for Class 1
is the statutory 6% target before caps; the report shows realized ratios run well below it.
