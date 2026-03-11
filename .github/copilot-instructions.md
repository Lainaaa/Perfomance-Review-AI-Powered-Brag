# Copilot Instructions

## About This Repository

**Performance Review AI Powered Brag** is a personal system for generating compelling, data-driven brag sheets for performance reviews — powered by AI.

The goal is to help collect, structure, and articulate professional achievements in a way that clearly communicates impact, aligns with company expectations, and saves time during review cycles.

## What This Repo Contains

- `my-review-context/` — personal context files: competency matrices, KPIs, grading frameworks, role expectations, and company-specific templates. These files give the AI the context it needs to generate relevant, accurate brag content.
- `.github/instructions/` — instructions and guidelines for the AI assistant behavior within this project.
- `.github/skills/` — skill definitions used by the assistant.

## How to Use

1. Drop your company's performance review materials into `my-review-context/`
2. Describe your achievements, projects, and contributions in natural language
3. Let the AI transform them into polished, impact-focused brag sheet entries aligned with your grade and expectations

## Assistant Behavior

- Always reference files in `my-review-context/` when generating brag content
- Align achievements with the competency levels and KPIs found in the context files
- Output should be concise, specific, and impact-driven (prefer metrics over vague statements)
- Default language for brag output: English
- Tone: professional, confident, and results-oriented
