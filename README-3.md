# TRACE Companions

Interactive companion pieces to *Shame as Resource in Indian Education: A Handbook for Teachers, Researchers, and Policy-Makers* (Yadav, Vanderheiden & Varshney, 2026). Hosted via GitHub Pages at `research2026-collab.github.io/trace`.

## What this is

Each file is a single, self-contained HTML file, no build process, no dependencies outside the file itself. Opening it is enough, there is nothing to install and nothing to compile. `index.html` is the overview page linking to every companion, each companion in turn links only back to `index.html`.

## Files

| File | Chapter | Content |
|---|---|---|
| `index.html` | – | Overview page with a card grid linking to every companion |
| `reflection_tool.html` | 12.3 | Six-domain reflection instrument for teachers, entries stay in the browser, can be saved to and reopened from a file |
| `companion_neural_cascade.html` | 3.6 | Five steps of the neural shame response, with a brain schematic |
| `companion_three_dimensions_of_shame.html` | 4 | Cognitive, performative and relational dimension of shame, plus a Cross-Dimensional View and the Triadic Self-Threat Model |
| `companion_cultural_shame_concepts.html` | 5 | Four culturally grounded shame concepts, lajjā, vṛīḍā, apatrāpya, izzat, each with an Inhibiting and a Resource dimension |
| `companion_bodymap_shame.html` | 6 | Body silhouette for marking shame-related sensations, includes data collection |
| `companion_capital_dimensions.html` | 7 | Six capital dimensions read through a single composite student vignette |
| `companion_teacher_interpersonal_behaviours.html` | 7.3 | Eight teacher behaviour categories, grouped into Burdensome and Supportive |
| `companion_shame_as_resource.html` | 10 | Five conditions under which shame can become a resource for learning, plus a closing tab reflecting on the limits of the framework |
| `companion_teaching_shame_sensitive_moments.html` | 12.1 | Eight shame-sensitive teaching moments within a single laboratory scene, plus an overview tab |
| `companion_caste_institutional_governance.html` | – | No longer linked, see Open Items below |

## Design

All files follow `TRACE_STYLE_GUIDE.md`, which sets out base colours, typography, the dimension-colour principle, chapter badges, layout components, image policy and technical constants. Before adding or revising a file, check that guide first, in particular section 4 on which colour goes with which dimension, and whether an existing colour already carries a meaning worth preserving, such as red for shame or danger, or grey for a closing overview tab, both of which override the usual six-colour rotation.

## Privacy and external requests

Most companions send nothing anywhere. Two exceptions exist by design.

- `reflection_tool.html` never stores anything automatically. It only offers local download and re-import of a file, never `localStorage` or a server connection.
- `companion_bodymap_shame.html` sends the drawing and demographic fields via `fetch` to a Google Apps Script. This is not an inconsistency with the otherwise restrained approach, it is the stated purpose of this companion, which collects research data.

## Open items

- `companion_caste_institutional_governance.html` still sits in the repository but is no longer linked from `index.html` or from any other companion. Whether it is eventually deleted or revised and reinstated is not yet decided.
- The style guide does not yet state the exception for content-driven colours explicitly, for instance the recurring red for shame or danger that several companions keep unchanged from an earlier version. The rule already applies in practice but has not yet been written into the guide itself.

## Adding a new companion

Create the new file, take base colours, typography and layout components from `TRACE_STYLE_GUIDE.md`, add the full citation to the footer, keep only the single link back to `index.html` in the navigation strip, and finally add a card to `index.html` with chapter number, title, a short description and the link.
