# PokéBonk Guide Starter Kit

A practical community resource for finding PokéBonk information, keeping useful run notes, and checking claims before sharing them.

Start with the [PokéBonk field guide](https://pokebonkgame.com/) for beginner explanations, Pokémon profiles, item observations, comparisons, and searchable answers. The linked site describes itself as an independent, unofficial guide; it does not host or develop the game. This repository is also an independent resource, with no claim of endorsement by the game developers or Pokémon rights holders.

## Start here

1. Read the [beginner guide](https://pokebonkgame.com/guide/) and choose a question to investigate.
2. Open the relevant Pokémon profile, item entry, or FAQ answer and read its source notes.
3. Check the wording in the game you are actually playing. Record its build if visible; otherwise write `unknown`.
4. Use the [player checklist](docs/player-checklist.md) to prepare a run and the [run-note template](templates/run-note.md) to record it.
5. Share a narrow observation with a source and context. Keep personal advice separate from measured results.

No installation, account, scripts, or dependencies are required to use these Markdown and CSV files.

## Resource directory

| Resource | Use it for | Keep in mind |
| --- | --- | --- |
| [Field guide home](https://pokebonkgame.com/) | Find your next topic | Independent guide, separate from the game |
| [Beginner guide](https://pokebonkgame.com/guide/) | Orient yourself before a run | Follow the prompts in your current game |
| [Pokémon profiles](https://pokebonkgame.com/wiki/) | Read documented kits and displayed traits | Current coverage is limited, not a complete roster |
| [Items and vitamins](https://pokebonkgame.com/items/) | Look up effect observations | A displayed offer is not a universal price or formula |
| [Pokémon comparison](https://pokebonkgame.com/tier-list/) | Compare documented kits | The URL says tier-list; the page does not establish a tested ranking |
| [FAQ](https://pokebonkgame.com/faq/) | Find focused explanations | Check the source and scope attached to an answer |
| [Tools](https://pokebonkgame.com/tools/) | Find comparison, filtering, and personal ordering tools | A personal order is a preference, not a performance study |
| [Sources and method](https://pokebonkgame.com/sources/) | Understand the guide's evidence categories | A review date is not a game version |
| [About the guide](https://pokebonkgame.com/about/) | Check scope and affiliation | The site identifies itself as unofficial |

Navigation reviewed on **2026-10-19** using publicly indexed page text. Direct requests from the preparation environment failed, so live HTTP availability was not independently confirmed. See the [source register](docs/sources.md) for the verification boundary.

## A useful observation workflow

1. **Ask one question.** For example: does an offered upgrade mention any move in this run's kit?
2. **Record the starting context.** Include build, mode, difficulty, language, selected character, and persistent upgrades where known.
3. **Transcribe what is visible.** Preserve units, conditions, and qualifiers. Mark translations and naming references explicitly.
4. **Separate the observation from the conclusion.** A tooltip can establish displayed wording; a claim about effectiveness needs gameplay evidence.
5. **Compare like with like.** Change one choice at a time where practical, include unsuccessful attempts, and report the number of runs.
6. **Keep the source traceable.** Record a public URL and timestamp or section. Publish only material you have permission to share.
7. **Recheck after changes.** Preserve old context and label older observations instead of silently presenting them as current.

See [evidence and comparison notes](docs/evidence-workflow.md) for a more detailed process.

## What is included

```text
docs/
  player-checklist.md       Before, during, and after a run
  evidence-workflow.md      Claims, sources, and fair comparisons
  sources.md                Public source register and verification limits
templates/
  run-note.md               Copyable notes for one run
  observation-log.csv       One explicitly fictional placeholder row
  README.md                 Field definitions and how to start a real log
CONTRIBUTING.md              Submission and review expectations
.github/ISSUE_TEMPLATE/      A structured correction report
LICENSE                     License for original repository material
```

The CSV is a **template, not a gameplay dataset**. Its placeholder row contains no real measurements. No game assets, screenshots, recordings, game implementation, or private local files are distributed here.

## Common interpretation traps

- A familiar Pokémon item name does not prove it has the same effect in this game.
- A selection preview can reflect a different context from a run. Record the screen and modifiers before comparing values.
- A single successful run cannot establish the best character, upgrade, or farming route.
- Missing values should remain `unknown`; zero is an actual measurement, not a substitute for missing evidence.
- A guide's summary is a starting point. Return to the cited evidence before repeating a precise mechanic or number.

## Contributing and reuse

Corrections, better source references, clearer instructions, and reproducible observations are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md). Please include the affected page, the relevant context, and exactly what the source supports.

Original repository text and templates are available under the [MIT License](LICENSE). That license does not grant rights to linked sites, game software, artwork, trademarks, or third-party source material. Pokémon and game names remain with their respective owners.

The source-first organization was inspired by the [SEC Form 4 Research Starter Kit](https://github.com/t7danter/sec-form4-research-starter-kit). This project applies that general approach to a separate topic with original guidance and templates.
