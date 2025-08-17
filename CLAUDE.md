# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static personal portfolio website for Lerko Araya Hernández (Electrical Engineer & Data Scientist) hosted on GitHub Pages at lerkoah.github.io. The site is built as a single-page application using pure HTML, CSS, and JavaScript with no build system or dependencies.

## Architecture

- **Modular file structure**: Separated HTML, CSS, and JavaScript files
- **css/styles.css**: All styles organized with CSS custom properties and logical sections
- **js/main.js**: Interactive functionality including scroll animations, smooth navigation, and particle effects
- **index.html**: Semantic HTML structure with SEO optimizations and structured data
- **No external dependencies**: Uses only native web technologies
- **Responsive design**: Mobile-first approach with CSS media queries
- **GitHub Pages deployment**: Automatically deployed when pushed to the main branch

## File Structure

```
├── css/
│   └── styles.css          # All CSS styles with organized sections
├── js/
│   └── main.js            # Interactive functionality and animations
├── assets/                # Directory for future images/resources
├── index.html             # Main HTML with SEO optimization
└── CLAUDE.md             # This documentation file
```

## Development Commands

```bash
# Local development server
python -m http.server 8000
# Alternative with Node.js
npx serve .

# Access locally at:
# http://localhost:8000
```

## CSS Architecture in styles.css

The CSS is organized in logical sections:
- **CSS Variables**: All color/gradient definitions in `:root`
- **Reset & Base Styles**: Fundamental styling and body setup
- **Background Effects**: Animated gradient backgrounds and geometric patterns
- **Navigation**: Fixed header with hover effects and active states
- **Hero Section**: Main banner with gradient text and animations
- **Timeline Components**: Experience/education timeline with dots and cards
- **Skills Grid**: Responsive grid with hover effects and skill tags
- **Contact Components**: Grid layout for contact information
- **Responsive Design**: Mobile-first breakpoints
- **Animations**: Keyframe definitions for all animations

## JavaScript Functionality in main.js

Interactive features implemented:
- **Scroll Animations**: IntersectionObserver for fade-in effects
- **Smooth Scrolling**: Enhanced navigation with offset calculations
- **Active Navigation**: Automatic highlighting of current section
- **Timeline Animations**: Staggered animations for timeline items
- **Language Bars**: Animated progress bars for language skills
- **Particle Background**: Dynamic floating particles effect
- **Utility Functions**: Throttling and helper functions

## Key Design System

- **Color Scheme**: Dark theme with purple (#673AB7) and cyan (#00BCD4) accents
- **Typography**: System font stack with careful letter-spacing
- **Spacing**: Consistent rem-based spacing throughout
- **Animations**: Smooth transitions with CSS and JavaScript coordination
- **Responsive**: Mobile-first approach with 768px breakpoint

## SEO & Performance Features

- **Meta Tags**: Complete SEO meta tags including Open Graph and Twitter Cards
- **Structured Data**: Schema.org Person markup for search engines
- **Preloading**: Critical CSS and JS resources preloaded
- **Performance**: Throttled scroll events and optimized animations

## Content Sections Architecture

- **Hero**: Animated gradient text with call-to-action links
- **About**: Personal introduction with styled content card
- **Experience/Education**: Timeline components with alternating layout
- **Skills**: Grid system with categorized technology tags
- **Publications**: Academic publication cards with hover effects
- **Contact**: Grid layout for contact methods