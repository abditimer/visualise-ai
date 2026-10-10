<div align="center">

# visualise ai

### Abdi's visual notes on artificial intelligence.

An independent collection of visual explainers and research tools for making AI easier to see, question, and understand.

[Open the site](https://abditimer.github.io/visualise-ai/) · [Explore the projects](#the-collection)

</div>

---

## The idea

AI can feel like a black box: all output, no view of the moving parts. **Visualise AI** is a growing collection of independent projects that give difficult ideas a shape, a sequence, and room for questions.

There are two ways in:

- **Learn by looking** — visual explainers that make AI concepts easier to follow.
- **Inspect and analyse** — tools for getting closer to what AI systems and agents are doing.

The educational explainers are the centre of the collection. Reference projects add useful context, while research tools grow alongside the work.

## The collection

### Learn

| Project | What it is | Status |
| --- | --- | --- |
| [How Transformers Are Built](https://abditimer.github.io/explain_ai/) | A scroll-led journey from raw text to generated language: tokens, embeddings, attention, and training. | Live |
| How Agents Work | A visual introduction to the loops, tools, and decisions that make an AI agent. | In the works |

### Explore

| Project | What it is | Status |
| --- | --- | --- |
| [AI, in the News](https://abditimer.github.io/aggregator_ai_site/) | An editorial digest of AI updates, concise summaries, and broader trends. | Live |
| [LLM Genealogy](https://abditimer.github.io/llm-genealogy/) | An interactive timeline for tracing language model architecture choices and papers. | Live |
| [AI Factories & Islands](https://github.com/abditimer/ai-factories-islands) | An evidence-led atlas of the places, power, and uncertainty behind AI compute. | In development |

### Research

**Nudging** is my current PhD work and the first project in the analysis and agent-understanding direction. It is a larger research project, currently in progress. More details will be shared here as the work develops.

## Run locally

This is a buildless static site. It uses plain HTML, CSS, and a small amount of inline vector artwork; the typefaces load from Google Fonts.

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Publish

GitHub Actions deploys the site to GitHub Pages when changes are pushed to `main`. The workflow copies `index.html` into a clean artifact directory, so no build tool or package installation is required.

Once Pages is enabled with **GitHub Actions** as its source, future pushes deploy automatically. The expected address is [abditimer.github.io/visualise-ai](https://abditimer.github.io/visualise-ai/).

## Project structure

```text
.
├── .github/workflows/pages.yml   # GitHub Pages deployment
├── index.html                    # Complete static site
└── README.md                     # Project guide
```

## Design notes

A compact studio index by Abdi Timer: cool soft-white, lavender, alpine green, and apricot; Fraunces display type with Manrope interface text; and three distinct hand-drawn panels for Learn, Explore, and Research. The page is designed to fit in one view on common desktop and mobile screens, and respects reduced-motion preferences.

