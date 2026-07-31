# Continuum Learning Portal

A single-file, interactive learning portal that teaches non-technical stakeholders how Continuum (Mission Planner) works — orbital mechanics basics, spacecraft/payload design, targets and ground assets, trajectory and sizing tools, and a deep dive into the real stakeholders and use cases behind the product.

Built as one self-contained HTML file (`continuum-learning-portal.html`) — no build step, no dependencies to install. Open it directly in any browser, or view it as a live Cowork artifact.

## What's inside

- Modules 1-5: mission basics, orbital mechanics, spacecraft anatomy, targets/ground assets, trajectories and sizing — each with plain-language explanations, inline diagrams, and charts.
- Module 6: a deep dive into the five real Mission Planner stakeholders (Business Manager, Technical Expert, Procurement Officer, DC Operator, Press & Influencer) — their world, likely tools, relationships, and best-fit use cases, sourced from the project's stakeholder map.
- Reference: use cases/stakeholders/phases overview, a searchable glossary, and a "how it all fits together" summary.

Content sourced directly from project documentation is marked as confirmed fact; reasoned inferences (e.g. "what tool this persona probably uses today") are visibly tagged as inferred, not documented.

## Updating this portal

This repo is set up for a simple edit-commit-push loop:

1. Changes are made to `continuum-learning-portal.html` and committed locally.
2. Run `git push` to publish the update to this repo.

No build tooling required — the file is deployment-ready as-is.
