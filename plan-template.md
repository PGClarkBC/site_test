---
title: [Short descriptive title of the feature]
version: [optional version number]
date_created: [YYYY-MM-DD]
last_updated: [YYYY-MM-DD]
---

# Implementation Plan: [Feature Name]
Briefly describe the feature, its purpose, and how it supports product goals.

## Overview
- Goal: Describe the primary objective of the feature.
- Context: Explain how this feature fits into the project and which existing pages or components it impacts.
- Alignment: Reference project guidance from `ARCHITECTURE.md`, `contributing.md`, and `PRODUCT.md`.

## Scope
### In scope
- List the concrete deliverables for this work.

### Out of scope
- Clarify what is intentionally excluded to reduce ambiguity.

## Architecture and design
- Describe the high-level design and structure for the feature.
- Note any architectural constraints, navigation flow, and design principles to follow.
- If applicable, identify which pages or files will be updated.

## Tasks
- [ ] Gather requirements and confirm acceptance criteria.
- [ ] Design page structure and content layout.
- [ ] Implement HTML markup and page navigation.
- [ ] Update or add stylesheet rules to follow visual guidelines.
- [ ] Add content and verify all required fields are present.
- [ ] Review for accessibility, typography, and contrast compliance.
- [ ] Test navigation and page presentation on multiple screen sizes.
- [ ] Final review and merge.

## Acceptance criteria
- [ ] The feature is implemented using the agreed page structure and content.
- [ ] Text and navigation styling follow `contributing.md` guidelines for fonts, contrast, and buttons.
- [ ] The site remains consistent with the flat landing-page architecture in `ARCHITECTURE.md`.
- [ ] The feature supports the product goals described in `PRODUCT.md`.
- [ ] All required instrument sale criteria are explicitly documented and easy to read.

## Dependencies
- `index.html`
- `styles.css`
- `ARCHITECTURE.md`
- `contributing.md`
- `PRODUCT.md`
- Local assets inside `site-graphics/`

## Risks and mitigation
- Risk: New content may diverge from the site’s existing style.
  - Mitigation: Reuse the same font and button styles from existing pages and validate against `contributing.md`.
- Risk: Acceptance criteria may be incomplete or unclear.
  - Mitigation: Include a detailed itemized checklist and review against the provided requirements.

## Open questions
- Are there any existing pages that should contain this new content instead of creating a new page?
- Should we add a dedicated navigation button to the landing page or place this feature under an existing product section?
- Are there any preferred local images or diagrams to illustrate the acceptance process?

---

# Example Plan: Rare Instrument Acceptance Criteria Page
This example shows how to use the template for a specific feature request.

## Overview
- Goal: Add a new subordinate page that documents the instrument acceptance criteria for sale.
- Context: The page will support trust and provenance claims from `PRODUCT.md` and maintain the simple flat site architecture from `ARCHITECTURE.md`.
- Alignment: The page will use `Times New Roman` headings, `Courier` body text, strong contrast, and rounded button links as required by `contributing.md`.

## Scope
### In scope
- Create a new page describing acceptance criteria.
- Add a link from `index.html` to the new page.
- Ensure styling follows the existing site and contribution guidelines.

### Out of scope
- No backend ownership verification or form submission.
- No external asset downloads beyond the local `site-graphics/` folder.

## Architecture and design
- Add a new subordinate HTML page such as `instrument-acceptance.html`.
- Keep the page structure consistent with the other subordinate pages: header, content sections, back-to-home button.
- Use shared styles from `styles.css` and avoid adding new font families.

## Tasks
- [ ] Create the new acceptance criteria page.
- [ ] Add required content sections: manufacture details, ownership history, seller requirements.
- [ ] Add navigation from `index.html`.
- [ ] Update `styles.css` if necessary for button or typography support.
- [ ] Validate content against acceptance criteria.
- [ ] Review page for responsiveness and accessibility.

## Acceptance criteria
- [ ] The new page details manufacturer name, manufacturer address, and date of manufacture.
- [ ] Ownership history includes dates and locations for each owner, supporting documents, reasons for transfer, price paid, and proof of ownership requirements.
- [ ] Seller agreement terms require a written inspection approval and define inspection cost liability.
- [ ] The page is reachable from the landing page and includes a home link.
- [ ] The page styling matches the site’s established design.

## Dependencies
- `index.html`
- `styles.css`
- `site-graphics/` (if images are used)

## Risks and mitigation
- Risk: Content may not be clearly organized.
  - Mitigation: Use well-labeled sections and bullet lists for required criteria.
- Risk: New navigation may break the flat site structure.
  - Mitigation: Only add a direct link from the landing page and a back link from the new page.

## Open questions
- Should the new page be named `instrument-acceptance.html` or `seller-guidelines.html`?
- Should this page be linked from all subordinate pages in addition to the landing page?
- Does the product owner want the acceptance criteria page to include sample document types or only requirements?
