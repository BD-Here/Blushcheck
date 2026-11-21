# BlushCheck — Made Just For Nandu

Founder: BD

A responsive, free-to-host static website for preliminary makeup ingredient screening.

## Live sources currently connected

- **Open Beauty Facts**: live community-maintained cosmetic product search and ingredient-label data. Coverage depends on volunteer submissions and may be incomplete or inaccurate.
- **PubChem PUG REST**: live chemical identity lookup for up to 12 ingredient names per analysis. PubChem is not a cosmetic safety verdict.
- **Official / scientific research links**: direct links to EU CosIng, India CDSCO, US FDA and searches for SCCS/CIR assessments, product reports and adverse reactions.

## Important limitations

- The score is a transparent heuristic demo, not a validated toxicity model or medical assessment.
- Regulatory status is not automatically certified by this site. Check the exact ingredient, concentration, product type and applicable local rules.
- Customer reviews and adverse-event reports are not automatically aggregated from Google. This project opens targeted search links instead of pretending to have collected verified reports.
- Unknown ingredients are marked unassessed, never automatically safe.
- Product records from Open Beauty Facts are contributor supplied. Verify them against the packaging.
- Photo OCR is loaded from the Tesseract.js CDN when the user chooses image upload.

## Deploy free with GitHub Pages

1. Create a **public** GitHub repository named `blushcheck` (GitHub Free supports Pages for public repositories).
2. Upload `index.html` to the repository root. You can also upload this README.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for the deployment check to finish. Your site will be at:

   `https://YOUR-GITHUB-USERNAME.github.io/blushcheck/`

7. If you change the site later, edit `index.html` and commit the changes. Pages republishes automatically.

## Upload from a phone

1. Open your repository in Chrome and sign in to GitHub.
2. Tap **Add file → Upload files**.
3. Choose `index.html` from your phone's Downloads.
4. Scroll down and tap **Commit changes**.
5. Follow the GitHub Pages settings above.

## No paid API key required for included lookups

This version uses public endpoints without an account key. Free public services can change limits, availability or terms; if a provider changes access, the site will show a lookup error and manual ingredient entry will still work.

## Licensing / attribution

Open Beauty Facts data is community-contributed open data. If you redistribute or build on its product dataset, follow its ODbL terms and attribution requirements. PubChem data is provided by the US National Library of Medicine. Review each source's current terms before commercial use.
