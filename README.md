# BloomBuffer GitHub Pages Package

This folder is the publish-ready static app for GitHub Pages.

Current build:

- `Build: Phase 2 picker title UI v52`
- Phase 2 Risk clues only.
- No PASS/FAIL/REVIEW rule screening is connected.

## Files To Upload

Upload only these files to a GitHub repository:

- `index.html`
- `404.html`
- `.nojekyll`
- `README.md`
- `DO_NOT_UPLOAD_PRIVATE_DATA.txt`

## Privacy

Do not upload BloomBuffer JSON backups, photos, addresses, yard notes, debug logs, or any file containing real home/property details.

The app saves yard data locally in the browser with IndexedDB. GitHub Pages hosts the app code only; it should not store your yard data.

## GitHub Pages Setup

1. Create a new GitHub repository, for example `bloombuffer`.
2. Upload the files from this folder to the repository root.
3. In GitHub, open `Settings` > `Pages`.
4. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. Wait a minute or two for GitHub to publish.
7. Open the Pages URL on your phone.

Expected URL shape:

`https://YOUR-GITHUB-USERNAME.github.io/bloombuffer/`

## Phone Test

On the phone:

1. Confirm the top bar says `Build: Phase 2 picker title UI v52`.
2. Add one test object.
3. Close and reopen the same phone browser.
4. Confirm the object is still there.
5. Go to `Rules` > `Phone diagnostics` if buttons or storage fail.

Computer and phone data are separate unless moved by JSON backup/import.

## Sharing The App

After GitHub Pages is enabled, the app link should look like:

`https://YOUR-GITHUB-USERNAME.github.io/bloombuffer/`

For this repository, the likely link is:

`https://pyxelwhiz.github.io/bloombuffer/`

You can send that link to someone else. They will open the same app code, but their saved yard objects will be stored locally in their own browser/device. They will not see your phone data unless you separately send them a JSON backup or upload private data to GitHub.

If someone forks or copies the project, they should publish their own GitHub Pages link from their own repository.
