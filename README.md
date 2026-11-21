# BlushCheck — product name + photo update

## Product identification workflow
1. The user can enter a product name, upload a front photo, or provide both. At least one is required to search.
2. If a front photo is supplied, browser OCR reads visible text. When both name and photo are supplied, the typed name is used for the database search and the OCR text is compared with the returned candidate.
3. If the entered name or photo text appears inconsistent with the candidate, BlushCheck displays a wrong-product warning and shows the candidate's correct database name. Analysis is blocked until the user corrects/rechecks the product identity.
4. If no candidate with an ingredient list is found, the user can upload a back-label photo. They should review and correct OCR text before using it.
5. The user can also use the ingredient text fallback if database and OCR options do not work.

## Limitations
- This is browser OCR + text search, not advanced visual AI product recognition. OCR can misread stylized packaging and token matching can flag uncertain cases; always compare the candidate image/name with the actual packaging.
- Open Beauty Facts is community-contributed and may be incomplete or outdated.
- Back-label OCR can make mistakes; review the extracted text.
- PubChem provides chemical identity information, not a cosmetic safety verdict.
- The score is heuristic, not a validated safety rating or regulatory determination.
- GitHub Pages can host this static site for free.

## Publish
Replace the repository-root `index.html` with this file, commit to `main`, and ensure GitHub Pages uses `main` / root.
