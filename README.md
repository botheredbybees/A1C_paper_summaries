# UTAS Creative Arts and Health — Research Wiki

A personal research knowledge base built from weekly readings for the
[Diploma of Creative Arts and Health](https://www.utas.edu.au/) at the
University of Tasmania. Pages are generated automatically from academic
papers, textbook chapters, lesson pages, and video transcripts across
eight units.

---

## What's in here

| Folder | Contents |
|---|---|
| [`sources/`](sources/) | One page per source — summary, APA 7 citation, DOI, key concepts, tags |
| [`topics/`](topics/) | Cross-source synthesis pages — one per recurring theme or concept |
| [`tags/`](tags/) | Tag index pages — list every source tagged with a given term |
| [`index.md`](index.md) | Entry point — links to all sources and topics |

---

## Browsing on GitHub

All internal links use standard Markdown and resolve correctly in the
GitHub file browser. The best starting points:

- **[index.md](index.md)** — full list of sources and topics
- **[topics/](topics/)** — browse synthesised concept pages
- **[tags/](tags/)** — find sources by theme (e.g. [`dementia-therapy`](tags/dementia-therapy.md), [`music-therapy`](tags/music-therapy.md))

Click any link on a source page to follow it to a related topic or tag,
and click source links on topic/tag pages to navigate back.

---

## Using in Obsidian

The vault uses standard Markdown links (`[text](path.md)`) throughout,
so it works in Obsidian without any special settings.

### Desktop (Mac / Windows / Linux)

1. Clone the repository:
   ```bash
   git clone https://github.com/botheredbybees/A1C_paper_summaries.git
   ```
2. Open Obsidian → **Open folder as vault** → select the cloned folder.
3. Links, backlinks, and graph view all work out of the box.

To pull updates when new sources are added:
```bash
cd A1C_paper_summaries
git pull
```

### Mobile (iPhone / iPad / Android)

The **Obsidian Git** community plugin handles cloning and syncing
directly inside Obsidian Mobile. Setup takes about five minutes:

1. Install [Obsidian](https://obsidian.md/) on your device.
2. Create a new empty vault.
3. Inside the vault, go to **Settings → Community plugins → Browse**,
   search for **Obsidian Git**, and install it.
4. Open the Obsidian Git plugin settings and tap **Clone an existing
   remote repo**.
5. Enter the repository URL:
   ```
   https://github.com/botheredbybees/A1C_paper_summaries.git
   ```
6. Set the clone destination to your vault folder and tap **Clone**.
7. Restart Obsidian — the vault is ready.

To pull future updates: open the command palette (swipe down or tap the
ribbon icon) and run **Obsidian Git: Pull**.

> **Note:** Obsidian Git on iOS requires no additional apps. On Android
> it works the same way. If you hit authentication issues, generate a
> [GitHub personal access token](https://github.com/settings/tokens)
> (scope: `repo`) and enter it as your password when prompted.

### Recommended Obsidian settings for this vault

- **Files & Links → Use [[Wikilinks]]** — turn **off** (links are
  standard Markdown)
- **Files & Links → Default location for new notes** — set to `sources/`
  if you want to add your own notes alongside the generated pages

---

## Units covered

| Code | Unit |
|---|---|
| FXA100 | The Arts and Dementia Care |
| FXA101 | Creativity for Life |
| FXA202 | The Photo Essay: Storytelling with Image and Text |
| FXA300 | Music, Mind and Body |
| FXA301 | Arts in the Community |
| FXA302 | Perspectives of the Arts on Health and Wellbeing |
| FXA303 | Creative Arts, Play and Mental Wellbeing |
| PSY214 | Stress, Self-Care and Mindfulness |

---

## Source types

Each source page includes a `source_type` field in its frontmatter:

| Type | Description |
|---|---|
| `paper` | Peer-reviewed journal article |
| `book-chapter` | Individually authored textbook chapter |
| `lesson` | MyLO lesson page |
| `transcript` | YouTube video captions |
| `web-article` | Referenced web page |
