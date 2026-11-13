# nfc-tag
NFC pet tag html app to copy the link into nfc pet tags

## Files

- `index.html`: the tag page. Opened without a link it shows the owner form; opened from a tag it shows the finder's page.
- `editor.html`: a visual editor for the page, with a live preview. It works offline as a local file and doesn't connect to any service.
- `config.json` (optional): the page's design as a separate file. Only used when `index.html` has no design built in.

## Editing the page

1. Keep `editor.html` and `index.html` in the same folder and open `editor.html` in your browser (double-clicking it works). To edit a different copy of the page, click **Open index.html…** at the top and pick it. The editor shows that file's design and code in the preview, and **Download index.html** saves your changes into a copy of it. Click ✕ next to its name to go back to the `index.html` in the editor's folder.
2. **Content & inputs**: add, remove, reorder and edit inputs (short text, long text, number, date, phone, email, link, Google Maps link, dropdown), headings, text, images, icon badges, dividers and spacers. Put `{pet}`-style short names in text to show an answer there.
   - **Images** can show on the finder's page, the owner form, or both. On the owner form they sit at the top, above the title.
   - **Help footer**: a link at the bottom of both pages (for example to your Instagram). Its text, link text and link can all be edited, and it stays hidden until a link is filled in.
   - **Vet clinic**: owners fill in the clinic's name and phone, and paste its Google Maps link (Share → Copy link). The finder sees the clinic's name with a **Call clinic** button and a **Directions** button. A full Maps link starts directions straight away. A short `maps.app.goo.gl` share link opens the clinic in Google Maps, one tap from Directions.
3. **Colours & background**: pick a preset or set each colour for light and dark mode; use a solid colour, a gradient or an image as the background; change the font and corner roundness.
4. **Owner form**: change the form's title, intro and the browser tab title.
5. **Save → Download index.html**: a complete page with your design built in. Replace the old `index.html` with it and upload it to any web host.

Unsaved changes are kept in your browser until you download the new page.

Each input has a permanent storage slot, so adding, removing or reordering inputs never breaks tags you've already written. Tags hold the page's web address, so host the new page at the same address as before.
