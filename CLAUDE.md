# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Structure

This is a single-page HTML presentation about Claude Code and Test-Driven Development. The codebase consists of:

- `index.html` - Main presentation file with embedded CSS and JavaScript
- `admiral-ackbar.png` - Image asset used in the presentation

## Development Commands

This is a static HTML presentation with no build process. To view:

```bash
# Open in browser (macOS)
open index.html
```

## Architecture

The presentation is built as a single HTML file with:

- **CSS**: Embedded styles using Tailwind CSS via CDN, with custom CSS for slide transitions and mobile responsiveness
- **JavaScript**: Vanilla JavaScript for slide navigation, smooth scrolling, and URL hash management
- **Layout**: Full-screen slides using CSS scroll-snap for smooth navigation
- **Responsive Design**: Mobile-first approach with extensive media queries

### Key Features

- Slide-based navigation with keyboard arrow keys
- URL hash-based routing for direct slide access
- Smooth scroll transitions between slides
- Mobile-responsive design with landscape mode support
- Intersection Observer API for fade-in animations and navigation tracking

## Content Structure

The presentation covers:

1. Introduction to Claude Code and TDD
2. Workflow comparisons (before/after Claude Code)
3. Experiments and learning outcomes
4. Live demo section
5. Best practices and takeaways

No modifications to the existing presentation structure should be made without understanding the slide flow and navigation logic in the embedded JavaScript.