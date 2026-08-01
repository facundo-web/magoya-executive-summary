# Magoya — Our Work (client-facing case documents)

Static case documents published at https://work.magoya.com/

## Cases

- **Experto Bayer — Executive Closing Report**: https://work.magoya.com/experto-bayer-closing-report/
- **Experto Bayer → FieldView migration**: https://work.magoya.com/migration-experto-to-fieldview/
  - [Video on Google Drive](https://drive.google.com/file/d/1wcKRhktGsqPBqJOUSX3j4TM-RW6mLTtF/view)

## Structure

- `index.html` — landing page listing all cases
- `<case-slug>/index.html` — each case document (letter-sized pages, print-ready)
- `<case-slug>/doc-page.js` / `support.js` — page layout runtime
- Every page of every case carries a subtle "Bayer Confidential" footer mark (`.page::after`)

## Conventions

- New cases go in their own lowercase folder: `work.magoya.com/<case-slug>/`
- Slugs: lowercase, full product names (no abbreviations)
- Add the case to the root `index.html` list
