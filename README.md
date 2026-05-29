# UCMS - University Course Management System

## Project Overview

A comprehensive web-based prototype for managing student academic performance, grades, and reporting. This system addresses the challenges of manual spreadsheet management by providing automated grade calculation, student performance tracking, and subject analytics.

## Part 2: Visual Design & Responsive Website

This section documents the visual design implementation for the UCMS website.

## Design Philosophy

The website was designed with a professional, educational institution aesthetic in mind:
- **Color Scheme**: Deep blues (#003366, #0055aa) representing trust and professionalism, complemented by white and light gray backgrounds for readability
- **Typography**: Clean sans-serif fonts (Segoe UI, Tahoma) for optimal readability across devices
- **Layout**: Card-based design for feature presentation, with consistent spacing and visual hierarchy

# Key Visual Features

1. **Consistent Navigation**: Same navigation menu across all 4 pages (Home, About, Features, Contact)
2. **Interactive Elements**: Hover effects on buttons, navigation links, and feature cards
3. **Focus States**: All interactive elements have visible focus indicators for keyboard navigation
4. **Gradient Headers**: Professional gradient backgrounds in header and hero sections
5. **Shadow Effects**: Subtle box shadows for depth and visual interest

## Responsive Evidence

### Testing Methodology

The website was tested using Chrome DevTools device toolbar on:
- **Mobile**: iPhone SE (375px width)
- **Tablet**: iPad (768px width)
- **Desktop**: 1920×1080 (full width)

### Responsive Breakpoints

| Breakpoint | Target Device | Key Changes |
|------------|--------------|-------------|
| > 1200px | Large Desktop | Wider containers, larger cards |
| 769px - 1199px | Desktop | Standard layout |
| 481px - 768px | Tablet | Reduced padding, stacked sections |
| < 480px | Mobile | Vertical navigation, single-column layout |

### Responsive Features Implemented

1. **Viewport Meta Tag**: Included on all pages for proper scaling
2. **Flexbox Layouts**: Used flex-wrap for automatic reflow
3. **Media Queries**: Three breakpoints covering all device sizes
4. **Fluid Images**: All images scale proportionally
5. **Touch-Friendly Buttons**: Minimum 44px touch target on mobile

### Screenshot Evidence

Screenshots are stored in: `assets/screenshots/`

- **Desktop View** (1920×1080): `desktop-home.png`, `desktop-about.png`, `desktop-features.png`, `desktop-contact.png`
- **Tablet View** (768px): `tablet-home.png`, `tablet-about.png`, `tablet-features.png`, `tablet-contact.png`
- **Mobile View** (375px): `mobile-home.png`, `mobile-about.png`, `mobile-features.png`, `mobile-contact.png`

## Changelog

### Part 2 - Visual Design (Current)

- **2026-05-25**: Created initial HTML structure for 4 pages (index, about, features, contact)
- **2026-05-25**: Implemented comprehensive CSS with responsive design
- **2026-05-25**: Added semantic HTML5 elements (header, nav, main, footer)
- **2026-05-25**: Styled navigation with hover/focus states
- **2026-05-25**: Implemented responsive breakpoints for mobile, tablet, desktop
- **2026-05-25**: Added contact form with validation
- **2026-05-25**: Created feature cards with hover effects
- **2026-05-25**: Added statistics display section
- **2026-05-25**: Implemented footer with multiple sections
- **2026-05-25**: Added accessibility features (focus states, alt text)
- **2026-05-25**: Created README with comprehensive documentation
- **2026-05-25**: Added screenshot evidence for all device sizes

### Part 1 - Backend Prototype (Reference)

- Implemented Python prototype with modular functions
- Added grade calculation logic with weightings
- Implemented student search and sorting
- Added subject performance evaluation

## References

### Design Inspiration

- W3Schools. (2025). *CSS Responsive Web Design*. Available at: https://www.w3schools.com/css/css_rwd_intro.asp (Accessed: 25 May 2026)

- Mozilla Developer Network. (2025). *CSS Media Queries*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries (Accessed: 25 May 2026)

### Color Scheme

- Coolors.co. (2025). *Educational Website Color Palettes*. Available at: https://coolors.co/palettes/education (Accessed: 25 May 2026)

### Layout Techniques

- CSS-Tricks. (2025). *A Complete Guide to Flexbox*. Available at: https://css-tricks.com/snippets/css/a-guide-to-flexbox/ (Accessed: 25 May 2026)

### Accessibility Guidelines

- Web Content Accessibility Guidelines (WCAG) 2.1. (2018). *W3C Recommendation*. Available at: https://www.w3.org/TR/WCAG21/ (Accessed: 25 May 2026)

### University Course Management System Concept

- The Independent Institute of Education. (2026). *WEDE5020D Project Brief: University Course Management System*. (Unpublished project document)

### Image Placeholders

- Placeholder images used as fallbacks when custom images are not available (from placeholder service)

## Project Structure
