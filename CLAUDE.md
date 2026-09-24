# Architects or Accelerants? — project context

## What this is
A research project on whether social media and AI *cause* radicalization or *accelerate* a process driven by pre-existing vulnerabilities. Audience: law enforcement policymakers who are not specialists in this area.

Deliverables:
- Research paper: "Architects or Accelerants? Social Media, Artificial Intelligence, and the Radicalization Process" (see `paper/`)
- Explainer video (script written separately)
- Interactive web page: `site/index.html` (main deliverable in this folder)
- Early prototype of the pathway model: `site/prototype-firebreaks.html`

## Core argument
AI and social media act as accelerants and environments, not causes. Their biggest effect is helping produce a new threat population: young, ideologically thin or mixed, violence-fixated, unaffiliated. AI companions may take the structural place of the group, supplying validation without the brakes a group provides (sorting, disillusionment, someone who notices).

Five findings: (1) acceleration, not causation; (2) generative AI is an instrument; (3) the radicalizing population has shifted; (4) AI companions may occupy the network's position; (5) the target moves faster than the evidence.

## Six cases
Pittsburgh 2018, Hanau 2020, Windsor Castle 2021, Southport 2024, Pirkkala 2025, New York 2025.

## Conventions — follow these
- Refer to attackers by place, not name (avoids feeding the copycat cycle; consistent with the video script).
- Keep uncertain claims hedged exactly as the sources do: Pirkkala ChatGPT use is "reported, plausible but unconfirmed"; New York (US v. Gann) is allegations in a criminal complaint, not findings of fact.
- Interactive models are illustrative teaching tools, not risk assessment instruments. Keep the labels saying so.
- Every factual claim on the page should trace to a file in `sources/`.
- Don't reproduce long quotations from sources; paraphrase.

## Web page technical notes
- Single self-contained HTML file: inline CSS and JS, no build step. Open it directly in a browser to preview.
- Font: Public Sans from Google Fonts, with system fallbacks.
- Colors are CSS variables on :root with light and dark variants. Palette: teal = firebreaks/barriers, ember = heat/accelerants, night = dark sections.
- All graphics are inline SVG generated in the script block. No external images.
- Sections (in order): hero + poll, six cases timeline, the debate (tabs), six numbers, pathway/firebreaks model, case scorecard, youth/age chart, companion comparison, copycat loop, TRAP-18 warning behaviors, findings, recommendations, quiz, closing, sources.
- Respects prefers-reduced-motion; responsive down to ~380px (wide charts scroll horizontally on phones).

## Sources
`sources/` holds the PDFs used for the paper. Key ones: Kunst et al. 2026 (four-stage framework), Shaw 2023, Hafez & Mullins 2015, Simi & Windisch 2017, Amman/Kupper/Meloy 2026 (TRAP-18, Tree of Life), Solea 2025 (Pirkkala), Mehra & Herbach 2026 (CTC Sentinel, youth prosecutions), Glazzard et al. 2026 (CTC Sentinel), US v. Gann complaint (1-25-cr-00331.pdf).
