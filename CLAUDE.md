# CLAUDE.md - AI Assistant Guide

This document provides guidance for AI assistants working with this recipe collection repository.

## Project Overview

This is a personal recipe collection stored as markdown files. The repository contains food recipes with ingredients and instructions in a consistent, readable format.

## Repository Structure

```
recipes/
├── CLAUDE.md           # This file - AI assistant guidance
├── README.md           # Project overview
├── .gitignore          # Ignores image files (*.jpg, *.jpeg, *.png)
├── ButtermilkSyrup.md  # Recipe files
├── FryBread.md
├── FryBreadMeat.md
└── OrangeOliveOilCake.md
```

All recipe files are stored at the root level as markdown files.

## Recipe Format Convention

Each recipe follows this structure:

```markdown
# Recipe Name

Optional: Source attribution link

## Ingredients

Optional: MAKES X (yield information)

- ingredient 1
- ingredient 2
- ...

## Instructions

- step 1
- step 2
- ...

### Notes (optional)

- additional tips or storage instructions
```

### Key formatting rules:

1. **Title**: Use H1 (`#`) for the recipe name
2. **Source**: If adapted from another source, include a link directly below the title
3. **Sections**: Use H2 (`##`) for main sections (Ingredients, Instructions)
4. **Subsections**: Use H3 (`###`) for optional subsections (Notes)
5. **Lists**: Use bulleted lists (`-`) for both ingredients and instructions
6. **Yield**: Place serving/yield info (e.g., "MAKES 16") directly under Ingredients header

## File Naming Convention

- Use **PascalCase** for file names (e.g., `FryBread.md`, `ButtermilkSyrup.md`)
- No spaces in file names
- All recipe files use `.md` extension
- Name should clearly reflect the recipe (e.g., `OrangeOliveOilCake.md`)

## Measurement Conventions

- Use **decimal notation** for fractions: `0.5` instead of `1/2`, `1.5` instead of `1 1/2`
- Abbreviations:
  - `Tsp` = teaspoon
  - `Tbsp` = tablespoon
  - `oz` = ounces
  - `g` = grams (used in parentheses for precision)
- Include both volume and weight when helpful: `.25 cup (46g)`
- Standard formats: `1 cup`, `2-3 Tbsp`, `15 oz.`

## Git Workflow

- Commit messages should briefly describe what was added/changed
- Examples from history:
  - `add buttermilk syrup and orange olive oil cake`
  - `Fry Bread`
- Image files are not tracked (see `.gitignore`)

## Guidelines for AI Assistants

When working with this repository:

1. **Adding new recipes**: Follow the established format exactly - use the existing recipes as templates
2. **Editing recipes**: Preserve the formatting conventions (decimal measurements, bullet lists, section headers)
3. **File naming**: Always use PascalCase with no spaces
4. **Keep it simple**: This is a flat structure - all recipes go in the root directory
5. **No images**: Image files are gitignored; recipes should be text-only
6. **Source attribution**: When a recipe is adapted from elsewhere, include a link to the original source
7. **Consistency**: Match the style of existing recipes (measurement format, list style, etc.)
