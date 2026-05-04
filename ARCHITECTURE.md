# Architecture

## Overview

This website follows a simple hierarchical structure consisting of a central landing page that serves as the primary entry point and navigation hub, with four subordinate pages accessible from the landing page.

## Architecture Diagram

```
Landing Page (index.html)
    ├── Subordinate Page 1
    ├── Subordinate Page 2
    ├── Subordinate Page 3
    └── Subordinate Page 4

(Each subordinate page links back to Landing Page)
```

## System Structure

### Landing Page
- **Purpose**: Serves as the main entry point and navigation hub for the website
- **Responsibility**: Provides navigation links to all three subordinate pages
- **Key Elements**:
  - Navigation menu or link section directing users to each subordinate page
  - Site title/branding
  - Optional introductory content

### Subordinate Pages (Page 1, Page 2, Page 3)
- **Purpose**: Display specific content related to each respective topic
- **Responsibility**: Present content relevant to that page's purpose
- **Key Elements**:
  - Header (matching across all subordinate pages)
  - Page-specific content
  - Footer (matching across all subordinate pages)
  - "Back to Landing Page" or "Home" link for navigation return
  - Consistent styling with the landing page

### Shared Assets
- **Purpose**: Store shared image and media files that support the website's visual presentation
- **Responsibility**: Keep image assets organized in a dedicated directory so pages can reference them consistently
- **Key Directory**:
  - `site-graphics/`: holds image and asset files used by the site, including product visuals and supporting illustrations
- **Sourcing**: Use trusted public-domain or Creative Commons image repositories such as Wikipedia/Wikimedia Commons, and explicitly avoid downloading images or content from example.com.

## Navigation Flow

1. Users land on the **Landing Page**
2. From the landing page, users can navigate to any of the three **Subordinate Pages** via direct links
3. From any **Subordinate Page**, users can return to the **Landing Page** using the back/home link
4. Navigation is bidirectional but limited: subordinate pages do not link to each other directly

## Design Principles

- **Simplicity**: Flat navigation hierarchy makes the site easy to understand and traverse
- **User-Centric**: Multiple pathways to return home ensure users never feel trapped
- **Consistency**: All pages maintain a unified look and navigation pattern
- **Accessibility**: Clear navigation labels and back-links make the site navigable for all users

## Scalability Considerations

Future enhancements may include:
- Additional subordinate pages (extend the current three-page model)
- Secondary navigation between related subordinate pages
- Breadcrumb navigation for improved wayfinding on deeper hierarchies
- Dynamic navigation menus
