# Overview

This is a static NFT preview card component built as a Frontend Mentor challenge. The project displays a single NFT card with an image, title, description, price information, time remaining, and creator details. It's a pure frontend implementation focusing on HTML and CSS fundamentals with responsive design and hover interactions.

## Recent Changes (September 30, 2025)

- Implemented complete NFT card component matching design specifications
- Created semantic HTML structure in `index.html`
- Built comprehensive CSS styling in `styles.css` with hover effects and responsive design
- Organized all image assets in `/images` directory
- Configured Python HTTP server workflow for local development
- Successfully tested on multiple screen sizes with all interactive elements working

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture

**Problem**: Create a visually appealing, responsive NFT card component that matches a provided design specification.

**Solution**: A component-based HTML/CSS approach with semantic markup and custom CSS properties for theming.

**Key Architectural Decisions**:

1. **Semantic HTML Structure**
   - Uses semantic elements (`<main>`, `<article>`, `<h1>`) for accessibility
   - Clear component hierarchy with BEM-like class naming (e.g., `nft-card`, `nft-image-container`)
   - Proper alt text for images to support screen readers

2. **CSS Custom Properties (CSS Variables)**
   - Centralized color system using CSS custom properties in `:root`
   - Consistent color palette: blue-500, cyan-400, blue-950, blue-900, blue-800, white
   - Enables easy theming and maintenance

3. **Layout Strategy**
   - Flexbox for centering and alignment
   - Mobile-first responsive approach with max-width constraint (350px)
   - Card-based design pattern with padding and border-radius

4. **Interactive Elements**
   - Image overlay effect (`.nft-overlay`) for hover states
   - Cursor pointer on image container indicating interactivity
   - CSS transitions for smooth hover effects

5. **Typography System**
   - Google Fonts integration (Outfit font family)
   - Font weights: 300 (light), 400 (regular), 600 (semi-bold)
   - Base font size: 18px

**Design Patterns Used**:
- Component isolation (card is self-contained)
- Utility-first spacing and layout
- State-based styling (hover effects)

**Pros**:
- Simple, maintainable codebase
- No framework dependencies
- Fast load times
- Accessible markup

**Cons**:
- Limited to static display (no dynamic data)
- Manual responsive breakpoint management
- No component reusability across projects without copying code

# External Dependencies

## Third-Party Services

1. **Google Fonts**
   - Service: Google Fonts CDN
   - Font Family: Outfit
   - Weights: 300, 400, 600
   - Preconnect optimization for performance

## Assets

All assets are local (no external APIs):
- NFT images stored in `./images/` directory
- Icons: Ethereum, clock, view icon
- Avatar images for creator
- Favicon

## No Backend/Database

This is a purely static frontend project with no:
- Backend services
- Database connections
- API integrations
- Authentication systems
- State management libraries

The application is designed to run entirely in the browser without server-side processing.
