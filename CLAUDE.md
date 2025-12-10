# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **Teacher Prompt Bank** - a collection of AI prompt templates for UK educators. It contains no executable code, build systems, or tests.

## Repository Structure

- `prompts/` - Eight categories of prompt templates (lesson-planning, resources, assessment, differentiation, feedback, explanation, questions, communication)
- `config/parameters.json` - Defines all customisation parameters with descriptions and examples

## Prompt Template Format

Each prompt file follows this structure:
1. **Purpose** - Brief description
2. **Prompt** - Main template with `[PLACEHOLDER]` variables
3. **Neurodivergent Adaptation** - Inclusive version with accommodations
4. **Example Usage** - Concrete example
5. **Tags** - Categorisation tags

## Placeholder Conventions

All parameters use `[UPPERCASE_BRACKETS]` format:
- `[SUBJECT]`, `[YEAR_GROUP]`, `[EXAM_BOARD]`, `[ABILITY_LEVEL]`
- `[TARGET_GRADE]`, `[NEURODIVERGENCE]`, `[TOPIC]`, `[TIME_AVAILABLE]`

See `config/parameters.json` for the complete list with examples.

## UK Education Context

Prompts are designed for the UK system:
- GCSE (9-1) and A-Level grade references
- UK exam boards: AQA, Edexcel, OCR, WJEC, Eduqas
- Key Stage terminology (KS3, KS4, KS5)
- British English spelling

## Contributing New Prompts

1. Follow the existing file naming: `XX-descriptive-name.md`
2. Include all five sections (Purpose, Prompt, Neurodivergent Adaptation, Example Usage, Tags)
3. Use consistent `[PLACEHOLDER]` format
4. Add neurodivergent-friendly variations where appropriate
