# Pied-à-terre surcharge — explainer infographics

Three embeddable infographics in Vital City style, built to accompany Martha E. Stark's
essay "Before You Surcharge the Penthouse, Fix the Foundation."

| File | Box | What it shows |
|---|---|---|
| `box1.html` | Box 1 | How the surcharge works, and who has to do what — a 5-step timeline with actors and deadlines |
| `box2.html` | Box 2 | Five questions the rules still have to answer |
| `box3.html` | Box 3 | What clear primary-residence rules should look like |

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

All content is drawn from Martha E. Stark, "Before You Surcharge the Penthouse, Fix the Foundation,"
Vital City — specifically Boxes 1, 2 and 3 of the piece. No independent data analysis; these are
faithful visual restatements of the article's explanatory boxes. The placeholder `href="#"` in each
source line should be set to the published article URL before going live.
