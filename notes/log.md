# Log

**Summary**: Append-only record of all operations on the notes.
**Last updated**: 2026-11-18

---

- **2026-11-18** | Source: setup | Created folder structure: `raw/`, `processed/`, `notes/`; added `notes/index.md`, `notes/log.md`, and empty `raw/New_Notes.md`.
- **2026-11-18** | Source: `raw/New_Notes.md` (3 URL notes) | Ingested 3 notes:
  - Added "The Technical Debt of Earth Embedding Products" to new page `Remote_Sensing.md` (related: Embeddings, Data).
  - Added "agribound" to new page `Agriculture.md` (related: Python, Remote Sensing, Deep Learning, Embeddings).
  - Added "Groundsource: A Dataset of Flood Events from News" to new page `Climate_Change.md` (related: Data).
  - Created related pages with back-links: `Embeddings.md`, `Data.md`, `Python.md`, `Deep_Learning.md`.
  - Updated `index.md` with 7 new pages. Moved source to `processed/2026-11-18_New_Notes.md` and created a new empty `raw/New_Notes.md`.
- **2026-11-18** | Source: `raw/First thermal images from Sentinel-3C radiometer.md` (web clipping) | Ingested 1 note:
  - Added "First thermal images from Sentinel-3C radiometer" to the top of `Remote_Sensing.md` (related: Climate Change).
  - Added a back-link section to `Climate_Change.md`.
  - `raw/New_Notes.md` was empty; left in place. Moved the clipping to `processed/2026-11-18_First thermal images from Sentinel-3C radiometer.md`.
- **2026-11-18** | Source: spatialthoughts/personal-notes-website-template | Set up MkDocs website publishing:
  - Added `mkdocs.yml` (site/repo set to elagoudakis/personal-notes, nav set to the 7 existing topic pages), `hooks.py`, `requirements.txt`, `.github/workflows/deploy.yml`, `.gitignore`.
  - Changed `hooks.py` so nav counts skip wiki back-link lines and files are read as UTF-8.
  - Restructured `index.md`: new "Latest Finds" section above, existing content moved under "Topics".
  - Merged the "Update the Website" section into `CLAUDE.md`.
- **2026-11-18** | Source: setup | Added Obsidian workspace state files (`.obsidian/workspace.json`, `.obsidian/workspace-mobile.json`) to `.gitignore`.
- **2026-11-18** | Source: setup | Published the vault to github.com/elagoudakis/personal-notes (GitHub Pages via Actions). Set `site_url` in `mkdocs.yml` to https://dscape.gr/personal-notes/ to match the account custom domain.
- **2026-11-18** | Source: `raw/New_Notes.md` (1 URL note) | Ingested 1 note:
  - Added "PostGIS spatial joins, translated to DuckDB" to new page `SQL.md` (related: Data).
  - Added a back-link to `Data.md`. Added `SQL.md` to `index.md` and to the `mkdocs.yml` nav.
  - Updated Latest Finds (SQL, Remote Sensing, Agriculture).
  - Moved source to `processed/2026-11-18_New_Notes_2.md` and created a new empty `raw/New_Notes.md`.
