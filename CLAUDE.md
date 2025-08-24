# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for the TRIPLE (TPB-driven Profiling with LLM rEfinement) research framework. The website showcases research on externalizing social-cognitive structures for user modeling using Theory of Planned Behavior (TPB) and large language models.

**Live Website**: https://triple-cikm25.github.io/triple

## Architecture

This is a static HTML website using the Bulma CSS framework with minimal JavaScript interactions:

- **Frontend Framework**: Pure HTML/CSS/JS with Bulma CSS framework
- **Structure**: Single-page application with sections for abstract, methodology, datasets, results, and analysis
- **Styling**: Based on Bulma framework with custom CSS overrides in `static/css/index.css`
- **JavaScript**: Minimal interactivity using jQuery for navigation and image interpolation features
- **Images**: Research figures and diagrams stored in `static/images/`

## Key Files

- `index.html` - Main website content and structure
- `static/css/index.css` - Custom styling overrides
- `static/js/index.js` - Interactive features (navbar, image interpolation)
- `static/images/` - Research figures, tables, and diagrams
- `README.md` - Project documentation and citation information

## Development

Since this is a static website, development is straightforward:

1. **Local Development**: Open `index.html` directly in a browser or serve via any static file server
2. **Content Updates**: Edit `index.html` directly for text content changes
3. **Styling**: Modify `static/css/index.css` for visual changes
4. **Assets**: Add new images to `static/images/` and reference them in HTML

## Deployment

The website is deployed via GitHub Pages at https://triple-cikm25.github.io/triple. Any changes pushed to the main branch will automatically update the live site.

## Content Structure

The website follows an academic paper presentation format:
- Hero section with title and authors
- Abstract and key contributions
- Methodology overview with TRIPLE framework diagram
- Dataset descriptions (LaMP benchmark)
- Experimental results with performance tables and figures
- Error analysis and refinement process explanation

## Citation Format

The website is licensed under Creative Commons Attribution-ShareAlike 4.0 and is adapted from the Nerfies project template.