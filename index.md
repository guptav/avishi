# Avishi Gupta

**High School & Graduate Journey**

---

## Overview

This GitHub Pages Markdown site tracks Avishi's journey from high school onward, with a structure that can grow into future graduate milestones.

**Current School:** [Monta Vista High School (MVHS)](https://mvhs.fuhsd.org/)  
**First day:** **August 13, 2026**

---

## v1 Scope (Now)

- Public overview profile
- Timeline with dated milestones
- School, activities, and achievements sections
- Resources and references
- Markdown-based workflow for adding milestones
- v1 media support for approved photos/documents
- Personal reflections/journal-style entries

## Later Scope

- **v1.1:** richer milestone evidence/media links
- **v2:** graduate journey expansion (college/career/reflections)

---

## Journey Timeline

> Status legend: `published`, `draft`, `archived`

| Date | Title | Category | Status | Description | Evidence |
|---|---|---|---|---|---|
| 2026-08-13 | First day at Monta Vista High School | academics | published | Beginning of high school journey at MVHS. | [First-day photo](media/photos/2026-08-13-first-day-mvhs.svg) |
| 2026-09-01 | Clubs exploration period | activities | published | Initial exploration of student clubs and interests. | [Club exploration notes](media/documents/2026-09-01-club-exploration-notes.md) |
| 2026-09-10 | Fall semester goals drafted | academics | published | Set clear academic and activity priorities for the first semester. | [Fall goals document](media/documents/2026-09-10-fall-goals.md) |
| 2026-09-15 | Campus walkthrough and schedule rhythm | personal | published | Built confidence with classroom transitions and daily planning. | [Campus walkthrough photo](media/photos/2026-09-15-campus-walkthrough.svg) |

---

## School

- **Institution:** Monta Vista High School
- **District:** Fremont Union High School District
- **Focus:** academic growth, balanced extracurricular participation, long-term graduate readiness

## Activities

- Club participation (in progress)
- School/community involvement (in progress)

## Achievements

- Milestones will be added as they become verified and publish-ready.

---

## Milestone Data Model

Use this schema for each timeline entry:

| Field | Required | Description |
|---|---|---|
| `id` | Yes | Unique slug (example: `2026-08-13-first-day-mvhs`) |
| `date` | Yes | ISO date `YYYY-MM-DD` |
| `title` | Yes | Concise milestone title |
| `category` | Yes | `academics`, `activities`, `achievements`, `graduate`, `personal` |
| `status` | Yes | `draft`, `published`, `archived` |
| `description` | Yes | One concise factual summary |
| `evidence` | No | Link(s) to approved documents/media |
| `tags` | No | Optional short labels |
| `reflection` | No | Optional short reflection text (journal tone allowed) |

See `docs/MILESTONE_TEMPLATE.md`.

---

## Editorial Standards

- **Tone:** factual, positive, respectful, concise
- **Reflections:** first-person journal voice is allowed when clearly labeled as reflection
- **Date format:** `YYYY-MM-DD`
- **Citations:** link primary source when available
- **Images/media:** use clear names and include context/caption when referenced
- **Media paths:** keep public files under `/media/photos/` and `/media/documents/`
- **Privacy:** do not publish sensitive personal details

---

## Governance and Publishing

- **Editors:** repository collaborators approved by the owner
- **Publisher of record:** repository owner (final decision authority)
- **Review rule:** each non-trivial milestone update should be reviewed before merge
- **Privacy rule:** redact or omit private details (exact addresses, sensitive IDs, personal contact data)

See:
- `docs/GOVERNANCE.md`
- `docs/PUBLISHING_CHECKLIST.md`

---

## Quality, Safety, and Durability

- Accessibility checks: heading order, meaningful link text, readable table structure
- Link integrity checks: verify all new links resolve and are trustworthy
- Content integrity checks: confirm dates/titles/source facts before publish
- Recovery: rely on git history and periodic tagged snapshots

See `docs/QUALITY_AND_ROADMAP.md`.

---

## v1 Media Library

- Photos directory: `media/photos/README.md`
- Documents directory: `media/documents/README.md`
- Naming convention: `YYYY-MM-DD-short-title.ext`
- Add only approved public-safe files

---

## Reflections Journal

Reflection entries can be brief and personal while staying respectful and privacy-safe.

| Date | Entry Type | Theme | Reflection |
|---|---|---|---|
| 2026-08-13 | reflection | first-day | I felt excited and a little nervous, but I’m proud of starting this new chapter at MVHS. |
| 2026-09-01 | reflection | activities | Exploring clubs helped me see where I can contribute and where I want to grow. |
| 2026-09-10 | reflection | goals | Writing my semester goals made everything feel more manageable and focused. |
| 2026-09-15 | reflection | routines | Once I learned the pace of each class, my confidence improved day by day. |
| 2026-09-20 | reflection | balance | I’m learning that steady habits matter more than perfect days, and that feels motivating. |

For additional entries, use `docs/REFLECTION_TEMPLATE.md`.

---

## Resources

- [Monta Vista PTSA](https://www.montavistaptsa.org/)
- [FUHS Foundation](https://fuhsfoundation.org/)
- [Google Drive Document](https://drive.google.com/file/d/1tV7igczHkD113gqRI0QlpD5tt702rdjx/view)

---

## Update Workflow (Quick)

1. Add or update milestone rows in this file using the model above.
2. Validate date format, status, and references.
3. Run through the publishing checklist.
4. Open/merge via normal repository review flow.

---

© 2026 Avishi Gupta — All rights reserved.
