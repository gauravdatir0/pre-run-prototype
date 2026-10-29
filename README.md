# Pre-Run Prototype Evaluation - GitHub Pages

This folder contains a mobile-friendly HTML transformation of the PowerPoint prototype.

## Files

- `index.html` - complete prototype; no build tools or dependencies required

## Add your Microsoft Forms link

Open `index.html`, locate this line near the beginning of the script:

```js
const FORM_URL = 'PASTE_MICROSOFT_FORMS_RESPONSE_LINK_HERE';
```

Replace the placeholder with the Microsoft Forms **Collect responses** link.

## Publish with GitHub Pages

1. Create a public GitHub repository, for example `pre-run-prototype`.
2. Upload `index.html` to the repository root.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`.
6. Save and wait for the published URL.

The URL will look like:

`https://YOUR-USERNAME.github.io/pre-run-prototype/`

## Test before sharing

- Open the published link on iPhone and Android.
- Test all three prototype paths.
- Confirm that the center tap, Start Run, Skip, and Resume buttons work.
- Confirm the final Microsoft Forms button opens the correct response form.

## Privacy

The prototype runs entirely in the browser and does not transmit or store responses. Use Microsoft Forms to collect consent and evaluation responses.
