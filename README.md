# BloomBuffer

BloomBuffer is a small yard inventory app.

Use it to list yard areas, plants, trees, fences, gates, bins, furniture, mulch, measurements, and notes before trying to reason about defensible-space work.

Current build:

`Build: Phase 5 clearer tools v62`

## What It Does

- Saves your areas and objects in your own browser.
- Lets you add measurements and risk clues.
- Shows rule-of-thumb planning feedback.
- Saves and imports BloomBuffer JSON backup files.
- Exports and imports CSV tables for spreadsheet testing.
- Includes built-in test samples under `Rules` > `Table tools`.

## What The Bottom Buttons Mean

- `Save JSON` makes a BloomBuffer backup file.
- `Import JSON` only imports a BloomBuffer JSON backup.
- `CSV tools` opens the Rules table tools for CSV export, CSV import, and test samples.
- `Log` opens the local debug log.

If you choose a CSV file with `Import JSON`, the app will reject it and keep your current data unchanged. Use `CSV tools` for CSV files.

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
2. Confirm the top says `Build: Phase 5 clearer tools v62`.
3. Tap `Areas`, `Objects`, and `Rules` to make sure buttons respond.
4. Add one test object.
5. Close and reopen the same browser.
6. Confirm the object is still there.
7. Tap `CSV tools` if you want table export/import or built-in sample data.

If buttons do not respond, you are probably opening an older broken build. Use v62 or newer.
