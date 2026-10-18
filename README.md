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



## Personal profile and interactive CV

The homepage retains the Learn / Explore / Research sitemap and continues into
Abdi Timer’s career timeline. Native HTML disclosure controls let readers open
individual chapters without JavaScript. NVIDIA and Legal & General start open.
The timeline covers NVIDIA, IBM, BrainStation, Capco, Legal & General and the MSc,
with public links to MCompare, Visuali and earlier data projects.

NVIDIA role: Technical AI Instructor, March 2026–present. Other employment dates
come from the existing personal website; role descriptions follow Abdi’s supplied
career history. BrainStation overlaps IBM. NVIDIA interview materials are excluded.
The L&G diagram is a high-level account of the work, not a deployed demo or client code.

MAIT, VAT SomCom, Omnia and Nudging have public descriptions; their repositories
remain private. AI Factories & Islands is marked in development instead of sending
visitors to a private repository. Nudging remains research in progress / coming soon.

## Parallel research stream and illustrative labs

A parallel timeline shows the PhD from March 2025 alongside IBM, BrainStation
and NVIDIA. Career entries include four accessible native-dialog demos:

- Retirement-income present value with annual income, horizon and discount controls.
- Synthetic longevity curve with a configurable median remaining lifetime.
- Additive decision-tree price index with visible rule contributions.
- Spark-style healthcare workload simulation with worker partitions, serial work
  and coordination overhead. Spark is not executed in the browser.

These independently authored examples use synthetic inputs and explicit toy
formulas. They do not reproduce company models, datasets, code or performance.
Ownership notes credit Legal & General, and Capco and its client, for the original
work. Native dialogs support Escape, modal focus and return to the launch button.

Checked in Chrome at 1440, 390 and 320px: dialogs open and close without horizontal
overflow; the zero-discount pricing calculation and slower parallel-overhead case
behave as intended; no JavaScript errors were observed.

### Research branch and portrait

The PhD is now a lane within the career timeline itself. A curved connector at
March 2025 branches from the career spine; the research lane spans the IBM,
BrainStation and NVIDIA entries and resizes with disclosure panels. Both lanes
remain visible on narrow screens. The separate overlap table has been removed.

The portrait in `assets/abdi-timer.jpeg` was downloaded from Abdi's public LinkedIn
profile at his request on 18 October 2026. GitHub Pages now includes the assets
folder. LinkedIn's public view hid employment and education dates behind sign-in;
existing dates were retained from the previous personal website and PhD records,
not represented as newly verified on LinkedIn.

Checked branch continuity after expanding IBM, portrait loading, and absence of
horizontal overflow at desktop, 390px and 320px widths.
