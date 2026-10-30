# Sổ lúa Pickleball — GitHub Pages

## Upload the PWA

1. Extract the ZIP.
2. Upload **all files and folders inside the extracted directory** to the root of the `soluapick/pickscore` repository's Pages publishing branch. Keep the files at repository root; the built app is configured for the `/pickscore/` base path.
3. Wait for GitHub Pages to finish publishing, then open `https://soluapick.github.io/pickscore/`.
4. The archive includes the static Google OAuth return page, privacy policy, app install files, and the Google Drive setup note.

## Google Drive sync

GitHub Pages hosts static frontend files only; the API routes and encrypted OAuth-token storage must also be published from the Sổ lúa WebDev project. Use `README-GOOGLE-DRIVE.md` for the required Google Cloud OAuth settings. The exact redirect URI is:

`https://soluapick.github.io/pickscore/oauth/drive-callback.html`

Do not upload OAuth client secrets to this repository.
