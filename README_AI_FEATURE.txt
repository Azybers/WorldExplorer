# AI World Explorer — browser AI feature update

## What this update adds
- General image classification using TensorFlow.js MobileNet in the browser.
- Displays up to five possible labels and confidence estimates.
- Saves the image, top label, confidence and notes in this browser's local storage.
- English/Filipino text switching.
- The selected photo is not sent to a third-party AI API by this feature. The model files are downloaded from jsDelivr when needed.

## Important limitations
- This is a general image classifier, not a specialist species identifier. It may not identify exact plant or animal species.
- It requires internet access to download the AI libraries/model on first use.
- The photo and saved items remain in this browser on this device. They are not encrypted or backed up to the cloud. Clearing browser data may delete them.
- No real sign-in, password/fingerprint lock, or cloud sync is implemented.
- Never use a public GitHub Pages website to store secret API keys.
- The website can describe visible content but should not identify a person's real-world identity from a face.

## Install on GitHub using Android
1. Open your repository: https://github.com/azybers/AIWorldExplorer
2. Open `index.html`, tap the pencil/edit icon, select all, and replace its contents with the `index.html` from this package. Commit the changes.
3. In the repository root, use Add file → Create new file. Name it `app.js`.
4. Paste the entire contents of `app.js` from this package and commit.
5. Wait a minute, then open https://azybers.github.io/AIWorldExplorer/ in Chrome and refresh. Try a common object photo first.
6. If the old page remains, open Chrome menu → Settings → Site settings → Storage (or clear site data for this site), then reload. This may remove locally saved demo items, so export/keep anything important first.

This package does not replace `styles.css` or `manifest.json`.
