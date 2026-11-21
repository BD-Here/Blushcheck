# BlushCheck — photo-first update

## Workflow
1. Upload the front of the makeup product.
2. Browser OCR attempts to read visible brand/product text.
3. Search Open Beauty Facts for candidate records containing ingredients.
4. If no candidate with ingredients is found, upload a photo of the back ingredient label.
5. Review/correct OCR text, then run the preliminary ingredient screen.

## Limitations
- This is OCR + text search, not visual AI product recognition. Stylized packaging or products absent from Open Beauty Facts may not match.
- A product match is a candidate; compare it with the actual packaging.
- Open Beauty Facts data is community-contributed and may be incomplete or outdated.
- Back-label OCR can make mistakes; review the extracted text.
- PubChem provides chemical identity information, not a cosmetic safety verdict.
- The score is heuristic, not a validated safety rating or regulatory determination.
- GitHub Pages can host this static site for free.

## Publish
Replace the repository-root `index.html` with this file, commit to `main`, and ensure GitHub Pages uses `main` / root.
