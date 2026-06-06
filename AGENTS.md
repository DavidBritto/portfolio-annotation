# portfolio-annotation — Agent context

Single-page portfolio for **David Britto** (DevOps specialist / AI engineer), oriented toward remote annotation and technical contracting roles.

## Repository layout

| Path | Role |
|------|------|
| `index.html` | Entire site: structure, typography, layout, responsive CSS, content |
| `1.png` | Favicon |
| `.sdd/` | Per-change SDD contracts (`proposal.md`, `spec.md`, …) — created by SDD workflows |
| `.atl/` | Local SDD config and skill registry (gitignored) |

## Technical constraints

- **No build step** — open `index.html` in a browser or serve as static files.
- **No JavaScript** — interactions are anchor navigation and external links only.
- **Styling** — CSS variables in `:root`, Roboto via Google Fonts, dark theme (`--black` background).
- **Editing** — prefer minimal diffs inside `index.html`; avoid splitting files unless a change explicitly requires it.

## Product intent (from content)

- Sections: Summary, Skills, Domains, Portfolio, Experience, Languages, Platforms, Contact.
- Highlights: DevOps (Docker, Terraform, K8s, CI/CD), AI engineering (agents, RAG, RLHF), finance/STEM annotation fit.
- Target platforms listed: Dataforce, Surge AI, Scale/Remotasks, Micro1, Outlier, Appen, etc.
- CTA: remote annotation, DevOps, IA implementation; bilingual ES/EN.

## SDD persistence

- **Hybrid:** Engram topic `sdd-init/portfolio-annotation` + change keys `sdd/{change-name}/*`.
- Formal files under `.sdd/` when using `sdd-new` or parallel file-backed phases.
- Config: `.atl/sdd-config.json`, registry: `.atl/skill-registry.md`.

## Quality bar for changes

- Preserve visual language (spacing, section labels `01 — …`, reveal animations).
- Keep accessibility basics: semantic sections, readable contrast, `meta viewport`.
- Do not add a bundler or framework without an approved SDD proposal.

## Git

- Remote: `git@github.com:DavidBritto/portfolio-annotation.git`
- Recent focus: portfolio project links and AWS migration notes (see git history).
