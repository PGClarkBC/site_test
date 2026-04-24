# Architecture

## Site Structure

- `index.html` — The magazine home page with the masthead, featured article cards, and footer.
- `article1.html` through `article5.html` — Five dedicated article pages for the full text experience.
- `PRODUCT.md` — Product description and user experience summary.
- `ARCHITECTURE.md` — Structural overview and design rationale.
- `CONTRIBUTING.md` — Contribution and publishing guidance.
- `README.md` — Repository summary and usage notes.

## Design Principles

- **Static-first**: The website uses only HTML, inline CSS, and inline SVG elements.
- **No external assets**: There are no external style sheets, scripts, or image files.
- **Responsive layout**: The landing page card grid adapts to available width using CSS grid semantics.
- **Consistent branding**: Each page includes the same header and footer treatment.

## Layout Approach

- Page layout is built with inline style attributes on container elements.
- The header uses a large serif font (`Times New Roman`) to evoke a magazine masthead.
- Article cards and pages use subtle blue backgrounds, white panels, and modern spacing.
- The footer provides contact details and social media links on every page.

## Navigation Flow

1. User arrives at `index.html`.
2. User clicks one of the five article cards.
3. Browser navigates to the selected `articleN.html` page.
4. The article page includes a return link to the landing page.

## Tech Notes

- The site is ready for GitHub Pages or any static file hosting.
- Inline SVG is used for placeholder imagery, ensuring all graphics are embedded directly in HTML.
- The document structure is simple and easy to extend with additional articles.
