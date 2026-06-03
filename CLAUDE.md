# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Landing page for **Alluri** — a Nexus client project. This directory is currently being set up; see the parent `../CLAUDE.md` for shared conventions (HTML structure, CSS patterns, WhatsApp button, Portuguese content, color variable conventions).

## Client Context

- **Client:** Alluri
- **Agency:** Nexus (Brazilian digital marketing agency)
- **Format:** Single self-contained HTML file, same architecture as sibling projects

## When Files Are Added

Follow the pattern from the most complete sibling project (`../fisioterapia-v2.html`):

- Define all brand colors as CSS custom properties at `:root`
- Section order: nav → hero → services/about → process/timeline → footer
- Include a floating WhatsApp button (`.whatsapp-float`) with `https://wa.me/55...` format
- Use `clamp()` for fluid typography — no hardcoded `px` font sizes
- All copy in Brazilian Portuguese (`lang="pt-BR"`)
