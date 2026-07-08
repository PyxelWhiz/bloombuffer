# BloomBuffer

BloomBuffer is a small yard inventory app.

Use it to list yard areas, plants, trees, fences, gates, bins, furniture, mulch, measurements, and notes before trying to reason about defensible-space work.

Current build:

`Build: Phase 5 compact dock v68`

## What It Does

- Saves your areas and objects in your own browser.
- Lets you add measurements and risk clues.
- Shows rule-of-thumb planning feedback.
- Shows a grouped yard report for testing and planning.
- Keeps object cards compact, with notes and longer feedback details collapsed.
- Uses the bottom dock for JSON and CSV import/export.
- Saves and imports BloomBuffer JSON backup files.
- Exports and imports CSV tables for spreadsheet testing.
- Includes built-in test samples.

## File Tools

BloomBuffer has two file formats:

| Format | Export | Import | Use it for |
|---|---|---|---|
| JSON backup | `Save JSON` or `Save JSON backup` | `Import JSON` or `Import JSON backup` | A normal BloomBuffer backup. |
| CSV table | `Export CSV table` | `Import CSV table` | Spreadsheet-style testing, comparison, or careful table editing. |

CSV import/export is in the bottom dock and in `Rules` under `CSV files`.

If you choose a CSV file with `Import JSON`, the app will reject it and keep your current data unchanged. Use `Import CSV table` for CSV files.

## Yard Report

`Rules` includes `Yard report`.

The report groups saved objects into practical planning buckets:

- Change or check next
- Need more information
- Needs person review
- Temporary-only notes
- Mapped checks look okay
- Outside scope or not checked

You can also save the report as a `.txt` file. The report is rule-of-thumb planning help, not City sign-off.

## Reset For Testing

`Rules` includes `Reset testing data`.

That button clears the local areas and objects in the current browser only. It asks you to type `RESET` before anything is deleted. Save a JSON backup first if you want to keep the current test data.

## Privacy

BloomBuffer is local-first. Your yard data is stored in the browser/device where you enter it.

- Data saved on your phone stays in that phone browser.
- Data saved on your computer stays in that computer browser.
- Other people who open the app link get their own blank local copy.
- They will not see your yard data unless you send them a backup, CSV, photo, or private notes.

GitHub Pages hosts the app code only. Do not upload real yard data to this repository.

## Files To Upload

Upload only these five files to GitHub Pages:

- `index.html`
- `404.html`
- `.nojekyll`
- `README.md`
- `DO_NOT_UPLOAD_PRIVATE_DATA.txt`

Do not upload JSON backups, CSV exports with real notes, photos, debug logs, addresses, or private property details.

## GitHub Pages Link

After GitHub Pages is enabled, the app link should look like:

```text
https://YOUR-GITHUB-USERNAME.github.io/bloombuffer/
```

For this repository, the likely link is:

```text
https://pyxelwhiz.github.io/bloombuffer/
```

You can send that link to someone else. They will open the same app code, but their saved yard objects will be stored locally in their own browser/device.

If someone forks or copies the project, they should publish their own GitHub Pages link from their own repository.

## Quick Test

1. Open the app.
2. Confirm the top says `Build: Phase 5 compact dock v68`.
3. Tap `Areas`, `Objects`, and `Rules` to make sure buttons respond.
4. Use the bottom dock to try JSON export/import or CSV export/import.
5. Add one test object.
6. Close and reopen the same browser.
7. Confirm the object is still there.
8. Open `Rules` > `Yard report` and confirm objects appear in grouped planning buckets.
9. Use `Reset testing data` only when you want to clear this browser and start over.

If buttons do not respond, you are probably opening an older broken build. Use v68 or newer.
