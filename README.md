<img src="icon-512.png" width="128" alt="Rowbook icon">

# Rowbook

Read spreadsheets like a book. Open a CSV or Excel file (Google Forms responses, applications, sign-ups) and each row becomes a page. Group by any column, search by name or ID, colour-mark the people you like, and save everything back out as PDFs, Excel or CSV.

**Open it:** https://nanadotam.github.io/rowbook/

- **Private:** everything runs in your browser tab. Nothing is uploaded or stored, and closing the tab clears it.
- **Nothing to install:** use the link, or download this folder and double-click `index.html` (it works offline).

## Using it

1. Drop a `.csv` / `.xlsx` on the page (or paste a Google Sheets link shared as "anyone with the link").
2. Pick **Group by**, for example the committee column, and click a chip to see only that group.
3. Click a card to read it in a side panel (**F** for full page). **← →** moves between people, **Esc** or the browser Back button closes it.
4. **Colour-mark** someone with the dots at the top of the reader, or keys **1–8** (**0** clears). The page turns that colour. Agree among yourselves what each colour means. Filter by colour in the toolbar.
5. **Save…** opens the save dialog. Pick a style (Apple, Notion, GitHub, Minimal, Amoako, ported from [mdpdf](https://github.com/nanadotam/mdpdf-cli)) and watch the live preview, then save as:
   - **One PDF**: everyone in one file, with an optional summary page of counts
   - **Separate PDFs**, or **Separate PDFs in a ZIP**
   - **Text file (.md)**: for any editor, or for mdpdf
   - **Excel (.xlsx)**: the whole file, with marked rows filled in their colour
   - **CSV**: the whole file, with colours in a `Highlight` column

### Passing files around

The Excel and CSV exports include a `Highlight` column. When anyone opens that file in Rowbook again, their colours come back, so a team can pass one file back and forth.

`sample.csv` is made-up data to try it with.

## Credits

[SheetJS](https://sheetjs.com) (Apache-2.0) reads spreadsheets, [pdfmake](https://pdfmake.github.io) (MIT) makes the PDFs, [Inter](https://rsms.me/inter) (SIL OFL 1.1, see `vendor/Inter-OFL.txt`) is the PDF typeface, and [Phosphor Icons](https://phosphoricons.com) (MIT) provides the icons. All are bundled in `vendor/`.
