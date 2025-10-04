# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages portfolio website showcasing data science projects by Aleem Kirk. The site is a static website featuring three main projects:
- Wildfire Prediction (ML/Python)
- UK Political Donations RFM Analysis (Analytics/Tableau)
- IESO Power Analysis (Data Analysis/Azure ML)

## Project Structure

- `index.html` - Main portfolio page with hero section, about, projects showcase, and contact
- `styles.css` - Responsive CSS with mobile-first design, modern color scheme, and smooth transitions

## Development Environment

- IDE: PyCharm
- Platform: Windows (win32)
- Deployment: GitHub Pages (static site)

## Deployment

To deploy to GitHub Pages:
1. Initialize git repository: `git init`
2. Add files: `git add .`
3. Commit: `git commit -m "Initial commit"`
4. Create GitHub repository named `<username>.github.io` or enable Pages in repo settings
5. Push to GitHub: `git remote add origin <url> && git push -u origin main`
6. Enable GitHub Pages in repository settings (Settings → Pages → Source: main branch)

## Design System

- Primary color: #2563eb (blue)
- Secondary color: #1e40af (darker blue)
- Responsive breakpoints: 768px (tablet), 480px (mobile)
- Grid layout for project cards with auto-fit and minmax(350px, 1fr)