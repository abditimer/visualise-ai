# Abdi Timer — personal studio

[Visit the site](https://abditimer.github.io/visualise-ai/)

A personal home for Abdi Timer (aka Abdikhaliq Timer): building AI systems,
teaching how they work, and researching their behaviour.

## The experience

- A compact introduction, portrait, current NVIDIA role and PhD affiliation.
- Four selected projects with subject-specific SVG previews: Transformers,
  Agent Workspace Explainer, the Legal & General case study and Nudging.
- An expandable wider collection for independent products, reference tools and
  earlier data projects.
- A career timeline with an integrated PhD branch from March 2025. Opening the
  L&G gallery entry expands and focuses its case study in the timeline.
- Contact and writing links, including Substack, LinkedIn and GitHub.

Agent Workspace Explainer links directly to its public interactive site. Nudging
opens a research note and remains in progress. Public code and demo links are
attached to the appropriate projects.

## Design

Warm ivory, deep green ink and restrained violet. Fraunces display type and
Manrope body text. Asymmetric project gallery, a fine career spine, illustrations
drawn from each project's subject, and a small amount of handwritten annotation.
The project gallery and expanded case studies use the same spacing and type scale.

## Representative examples

The L&G case study includes independently authored toy demos for present value,
synthetic longevity and additive decision-tree pricing. Capco includes a
Spark-style healthcare workload simulation. These disclose their assumptions and
state that the original company work belongs to the companies. They contain no
company code, real health data, production models or measured performance claims.
Spark does not execute in the browser.

## Content provenance

The user's career descriptions take precedence over older copy. Additional facts
were checked against the source HTML in
[the earlier personal website](https://github.com/abditimer/personal-website)
on 19 October 2026: EMEA partner teaching, BrainStation curriculum responsibilities,
the L&G HR chatbot, MSc distinction, BEng, and public contact/writing links.
Employment dates remain those recorded in that earlier website. The PhD start
is March 2025. The portrait was downloaded from Abdi's LinkedIn at his request;
LinkedIn's public page did not expose the full employment dates for verification.

## Run and deploy

```sh
python3 -m http.server 8877
```

Open http://localhost:8877/. No package install or build step is needed.
GitHub Actions publishes `index.html` and `assets/` to Pages on pushes to `main`.
The existing repository address is retained so published links keep working.

## Files

- `index.html`: semantic page, timeline, native dialogs and interactive demos.
- `assets/brand.css`: personal studio visual system and responsive styles.
- `assets/abdi-timer.jpeg`: profile portrait.
- `.github/workflows/pages.yml`: deployment.

## Validation

Browser checks cover the gallery-to-case-study path, project-note dialogs,
Escape dismissal, representative demo opening, collection expansion, portrait
loading, local anchor targets, and desktop/390px/320px overflow. The PhD connector
remains aligned when entries expand. The original toy formula checks include
zero-discount present value and the parallel-work overhead case.
