# Using the templates

Copy the files into your own notes. Delete the CSV's `PLACEHOLDER-DELETE-ME` row before entering real observations. Do not mix placeholder and observed records in analysis. No real results are included.

## CSV field dictionary

| Field | Meaning |
| --- | --- |
| `record_id` | Your unique, non-personal record identifier |
| `record_status` | `placeholder`, `observed`, `needs-review`, or `superseded` |
| `observed_on_utc` | Actual observation date as YYYY-MM-DD; `unknown` if unavailable |
| `reviewed_on_utc` | Date you reviewed the evidence, separately from observation date |
| `game_build` | Exact visible version label; otherwise `unknown` |
| `mode`, `difficulty` | Labels from the recorded context; otherwise `unknown` |
| `ui_language` | Language of the original visible interface |
| `character` | Displayed character name, without guessing identity |
| `screen_context` | For example, selection, upgrade offer, shop, or result |
| `displayed_label` | Exact visible name; mark a translation explicitly |
| `displayed_effect` | Full effect wording, including conditions and units |
| `value`, `unit` | Optional single transcribed measurement and unit; otherwise `unknown` |
| `source_url` | Public evidence URL; `unknown` for an unpublished note |
| `source_locator` | Section, timestamp, or other precise location |
| `evidence_type` | For example, `game-ui`, `gameplay`, `guide-report`, or `translation` |
| `interpretation` | Your inference, kept separate from visible wording |
| `limitations` | Unknown modifiers, uncertain translation, or other missing context |

Use one row per observation. For multiple unrelated measurements, use separate linked record IDs or preserve the full wording in `displayed_effect`; do not force unrelated values into a single numeric field. Do not aggregate records across different contexts without explaining the grouping.

Quote CSV fields containing commas or line breaks, and double any quotation marks inside a quoted field. When opening untrusted CSV contributions in a spreadsheet, import text as text and review cells beginning with formula characters before use.

`unknown` means missing information. `0` means an observed zero. Keep those meanings distinct. A review date never substitutes for a build number or observation date.

The [run-note template](run-note.md) is better for long explanations, persistent modifiers, or comparisons that need more context. Public contributions still require traceable evidence and rights review under [CONTRIBUTING.md](../CONTRIBUTING.md).
