# Contributing to PromptForge

Thank you for your interest in contributing to PromptForge! This document outlines the process for submitting new skills and improvements.

## How to Contribute a Skill

### Skill File Structure

Each skill must be submitted as a SKILL.md file in the appropriate folder under /skills/. Use this template:

---
name: your-skill-name
description: One or two sentence description. Explain when to use this skill.
---

# Skill Title

Brief description of what this skill does.

## When to use

- Bullet point use case 1
- Bullet point use case 2

## Workflow

Step-by-step instructions for the skill.

## Output format

Description of what the skill outputs.

## Notes

Any important caveats or dependencies.

## Submission Checklist

Before submitting a PR, ensure:

- [ ] SKILL.md follows the template above
- [ ] Frontmatter includes name and description fields
- [ ] Skill name uses kebab-case (e.g., concept-generator)
- [ ] Skill has been tested with at least 3 different inputs
- [ ] Output format is compatible with downstream skills in the chain
- [ ] No proprietary or copyrighted content included

## Pull Request Process

1. Fork the repository
2. Create a branch: git checkout -b feat/your-skill-name
3. Add your SKILL.md file to the appropriate folder
4. Submit a PR with a clear description of what the skill does
5. Wait for review — we aim to respond within 48 hours

## Code of Conduct

Be respectful, constructive, and collaborative. We are building tools for creators.

## Questions?

Open an issue or reach out via the Discussions tab.
