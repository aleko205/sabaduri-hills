# Typography restoration notes

Reference: Web Features' 2024 Sabaduri Hills project mockups: https://webfeatures.ge/en/projects/sabaduri-hills/

- Original screenshot: hero title is upright, centered, heavy Georgian sans-serif (not an italicized serif).
- Our initial reconstruction used a serif accent on a portion of the hero title; that was inconsistent with the original design.
- Fix: typography.css loaded after style.css. All headings use upright Noto Sans Georgian, weight 800, with centered hero typography and mobile responsive scaling.
- Limitation: the exact original font family/weights are **unverified** because the original font and CSS assets are missing. Noto Sans Georgian is a visually similar substitute; do not call it the original font.
- Follow up: if a Wayback raw CSS, Google Fonts stylesheet URL, Web Features' source design file, or original font family name is recovered, replace --display-font and tune headline weight/letter spacing.

Do not confuse the restaurant's separate bilingual menu with the original site's language editions.
