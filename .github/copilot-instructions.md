---
applyTo: "**"
---

# Rare Musical Instruments Online Store Guidelines

This project is a simple website for an online store specializing in rare musical instruments and restoration services. The site connects collectors, musicians, and enthusiasts with unique vintage instruments and expert restoration expertise.

## Project Context
* [Product Vision and Goals](../PRODUCT.md): High-level overview of the store's offerings, including rare instruments inventory and restoration services, to ensure alignment with business objectives.
* [System Architecture and Design Principles](../ARCHITECTURE.md): Simple hierarchical website structure with a central landing page (index.html) and three subordinate pages. Emphasizes simplicity, user-centric navigation, consistency, and accessibility.
* [Contributing Guidelines](../contributing.md): Typography standards (Times New Roman for headlines, Courier for body text), color scheme (white text on dark backgrounds), and interactive elements (rounded button-style links with hover animations).

## Key Architectural Notes
- **Structure**: Flat hierarchy with bidirectional navigation—users start at the landing page and can access three content pages, each linking back to the home page.
- **Design Principles**: Prioritize simplicity, consistency, and accessibility. Avoid complex navigation; ensure all pages share unified styling.
- **Navigation Flow**: No direct links between subordinate pages; always route through the landing page for clarity.

## Development Guidelines
- Follow the specified typography and color schemes for visual consistency.
- Implement links as rounded buttons with hover effects.
- Maintain high contrast for readability (white text on dark backgrounds).
- Test on multiple devices to ensure accessibility and responsiveness.

# Project general coding standards

## Naming Conventions
- Use PascalCase for component names, interfaces, and type aliases
- Use camelCase for variables, functions, and methods
- Prefix private class members with underscore (_)
- Use ALL_CAPS for constants

## Error Handling
- Use try/catch blocks for async operations
- Implement proper error boundaries in React components
- Always log errors with contextual information
