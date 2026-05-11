# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single HTML presentation file (`vibe-coding.html`) about "Vibe Coding" — an AI-era programming approach. The presentation is in Chinese and uses a split-pastel style with scroll-snap slides.

## Viewing the Presentation

Open `vibe-coding.html` directly in a browser. The presentation uses:
- Scroll-snap navigation (vertical scrolling between slides)
- Staggered reveal animations on scroll
- CSS custom properties for theming

## Architecture

- Single self-contained HTML file with embedded CSS and minimal JS
- Google Fonts (Outfit) loaded via CDN
- All slides, styles, and animations in one file
- Responsive design using `clamp()` for fluid sizing

## Permissions

The `.claude/settings.local.json` permits `Bash(open:*)` for opening files in the default browser.