# Organization profile guidance

Scope: `profile/README.md`, the public Tinder GitHub organization profile.

## Presentation

- Use a branded mission banner followed by GitHub's native Markdown styling:
  emoji-prefixed level-three sections, short paragraphs and descriptive links.
  The README itself is the rendered reference for these patterns.
- Keep the profile concise and focused on engineering, the tech blog, open source
  and careers. Use a single-column layout that reads naturally on mobile.
- Make the mission the dominant headline below the wordmark. Use white text on
  Flame red (#CD130A) in `assets/mission.svg`, with `mission-mobile.svg` selected
  below 600px through a picture element. Keep the exact mission in the image alt
  text and SVG title. Use a compact two-line desktop and three-line mobile layout.
  This supersedes the gray blockquote and the competing "Engineering real
  connections" heading; do not restore either.
- Do not use em dashes. Separate headings, descriptions and links with paragraph
  breaks instead. Avoid decorative badges, wide tables and oversized banners.
- Keep the engineering blog near the top in its own section. Use the supplied
  description and a clear link without tracking parameters.
- Use the original 2026 rebrand wordmark in `assets/tinder-wordmark.svg`, at a
  compact width of 220 pixels. Preserve its proportions and color; do not redraw
  it or substitute the old lowercase wordmark or gradient flame.
- GitHub supplies body typography, spacing, link colors and light/dark themes.
  The mission SVG is the only custom text-color treatment; it uses standard
  sans-serif fonts and the verified wordmark's Flame red. Do not add page CSS
  or custom font dependencies.

## Content and validation

- Use the publicly stated mission: "Tinder is the most fun way to spark something
  new with someone new." This replaces the older "power and inspire real
  connections" mission copy. Source: Match Group's
  [Q3 2025 prepared remarks, page 3](https://s203.q4cdn.com/993464185/files/doc_financials/2025/q3/MTCH-3Q-2025-Prepared-Remarks-vFinal.pdf#page=3).
- Capitalize team and discipline names consistently in prose and list labels:
  Product Innovation, Mobile, Backend, Infrastructure, Recommendations,
  Machine Learning, and Trust and Safety.
  Keep connecting words such as "and" lowercase.
- Represent both member-facing and enabling engineering work. The overview
  should cover Product Innovation, Mobile, Backend and Infrastructure,
  Recommendations and Machine Learning, and Trust and Safety. These are areas
  of work, not an exhaustive organizational chart. Keep Backend explicit rather
  than implying it under Infrastructure. Do not include a Developer Experience
  and Delivery Tools bullet in this profile; the owner's latest editorial
  direction supersedes the earlier request to include that area.
- Describe enduring engineering challenges. Avoid dated launch roundups, rollout
  promises, product-status claims and performance statistics unless their current
  accuracy and public suitability have been verified. Link to the blog for stories.
- Check the rendered README at desktop and narrow mobile widths, in light and
  dark themes, after layout edits. Confirm the logo loads and links are usable.
- Keep changes in a pull request for owner review. Do not merge without approval.

## Brand source

The SVG is an unmodified copy of the wordmark served by the official
[Life at Tinder website](https://www.lifeattinder.com), verified November 13, 2026:

https://cdn.prod.website-files.com/63c58849a05fd52eeca11844/6a8c7eae6fcd8801f3ad7c10_%24fill%3Dprimary.svg

The [PORTO ROCHA case study](https://www.portorocha.com/tinder) documents the
2026 identity, including the all-caps wordmark and Flame red. These instructions
supersede the earlier full-width raster banner and product launch roundup.
