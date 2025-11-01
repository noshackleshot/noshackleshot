# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub profile repository (noshackleshot/noshackleshot) that displays on the user's GitHub profile page. The repository contains a single README.md file with a modern landing page design.

## Key Files

- **README.md** - The main profile page displayed on GitHub, styled as a modern minimalist profile
- **header.svg** - Custom SVG header with INFATIUM-style design (black background, white text, subtle effects)

## Development

This repository has no build process, tests, or compilation steps. The README.md is designed to render properly on GitHub using supported features only.

### Editing the README

**IMPORTANT:** GitHub strips `<style>` tags and most inline CSS. Use only GitHub-compatible features:

- **Custom styling** → Use SVG files with internal CSS (like header.svg)
- **Technology badges** → Use Shields.io badges (https://shields.io)
- **Layout** → Use HTML tables with `align` attributes
- **Statistics** → Use GitHub Stats API (github-readme-stats.vercel.app)
- **Icons** → Use Shields.io logos or inline SVG
- **Centering** → Use `<p align="center">` or `<table align="center">`

**What DOESN'T work on GitHub:**
- `<style>` tags (always stripped)
- Most inline `style` attributes (removed by sanitizer)
- CSS hover effects in HTML
- JavaScript
- Custom fonts via CSS (except in SVG)

### Editing the Header

The header.svg file contains:
- Full CSS styling (works inside SVG)
- INFATIUM aesthetic with black background (#0a0a0a)
- Ultra-subtle dot grid pattern
- Typography with proper spacing and weights
- Size: 1200x400px

To edit the header, modify header.svg directly. The SVG can include `<style>` tags internally.

## Design System

The profile follows a minimalist black/white aesthetic inspired by INFATIUM:
- **Colors**: Black background (#0a0a0a), white text (#ededed)
- **Header**: Custom SVG with full styling control
- **Badges**: Shields.io for-the-badge style with technology logos
- **Structure**: Clean Markdown with HTML tables for layout
- **Statistics**: GitHub Stats with dark theme matching color scheme
- **Language**: Russian
