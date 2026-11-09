# nfc-tag
NFC pet tag html app to copy the link into nfc pet tags

## Files

- `index.html`: the tag page. Opened without a link it shows the owner form; opened from a tag it shows the finder's page.
- `config.json`: the page's design (inputs, text, images, colours). If it's missing, the built-in design is used.
- `editor.html`: a visual editor for `config.json`, with a live preview.

## Editing the page

1. Open `editor.html` on your hosted site (e.g. `https://<you>.github.io/nfc-tag/editor.html`).
2. **Content & inputs**: add, remove, reorder and edit inputs (short text, long text, number, date, phone, email, link, dropdown), headings, text, images, icon badges, dividers and spacers. Put `{pet}`-style short names in text to show an answer there.
3. **Colours & background**: pick a preset or set each colour for light and dark mode; use a solid colour, a gradient or an image as the background; change the font and corner roundness.
4. **Owner form**: change the form's title, intro and the browser tab title.
5. **Save & publish**: download `config.json` and upload it to the repository, or publish it straight to GitHub with a fine-grained token (Contents: read and write).

Unsaved changes are kept in your browser until you publish.

Each input has a permanent storage slot, so adding, removing or reordering inputs never breaks tags you've already written.
