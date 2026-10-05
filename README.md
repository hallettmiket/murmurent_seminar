# murmurent_seminar

Seminar talks about [murmurent](https://github.com/hallettmiket/murmurent) —
shared agentic-AI infrastructure for a research centre — and the Pin1 work
built on top of it.

Each talk is a **single self-contained HTML file**. Images are embedded, so a
deck can be opened straight from disk with no server, no network and no build
step. Open it in a browser and press `F` for full screen.

## Talks

| Deck | Venue | Date |
|---|---|---|
| [`slides/slides_physiology_pharmacology_october_2026.html`](slides/slides_physiology_pharmacology_october_2026.html) | Department of Physiology and Pharmacology, Western University | 26 October 2026 |
| [`slides/slides_biochemistry_april_2026.html`](slides/slides_biochemistry_april_2026.html) | Department of Biochemistry, Western University | April 2026 |

The October deck descends from the April one. It changes the scientific framing
from finding Pin1 **inhibitors** to finding Pin1 **activators**, which is the
direction that matters in neurodegeneration, and adds two slides introducing
murmurent itself.

## Navigating a deck

| Key | Action |
|---|---|
| `→` `↓` `Space` | next slide |
| `←` `↑` | previous slide |
| `Home` / `End` | first / last slide |

Clicking the right or left half of the window also advances or goes back.

## Layout

- `slides/` — one self-contained HTML file per talk.
- `assets/` — source images, figures and documents the decks draw on, plus the
  small Python scripts that generated some of the figures. Assets are the
  originals; the decks carry their own embedded copies. One oversized working
  file, `assets/bbb-background.tiff`, is deliberately kept out of git and lives
  only on the author's machine.

## Related repositories

| Repo | What it holds |
|---|---|
| [`hallettmiket/murmurent`](https://github.com/hallettmiket/murmurent) | the system itself: agents, rules, hooks, MCP servers, CLI |
| [`hallettmiket/murmurent_public`](https://github.com/hallettmiket/murmurent_public) | onboarding hub and institution directory |

Figures in the murmurent slides are drawn from the murmurent manuscript.
