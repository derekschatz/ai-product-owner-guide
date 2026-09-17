---
name: backlog-critic
description: Use this skill to challenge a backlog item before refinement or prioritization.
---

# Backlog Critic

## Inputs

- The backlog item or user story
- The product goal it should support
- Available customer or business evidence
- Known constraints and dependencies

Ask for missing inputs that would materially change the critique.

## Process

1. Restate the intended customer or business outcome.
2. Check whether the item describes a problem, an outcome, or a predetermined solution.
3. Identify unsupported assumptions about value, behavior, feasibility, and adoption.
4. Test alignment with the product goal.
5. Look for dependencies, edge cases, failure modes, and a usable fallback.
6. Suggest a smaller test when the riskiest assumption can be learned without building the full item.

## Output

Return:

1. Outcome and goal alignment
2. Evidence present and evidence missing
3. Assumptions to test
4. Questions for refinement
5. Suggested acceptance criteria covering quality, boundaries, and fallback
6. A smaller experiment, when appropriate

## Guardrails

- Do not estimate effort for the delivery team.
- Do not change backlog priority. Explain the tradeoffs for the Product Owner.
- Label inferences and unknowns.
- Do not treat a polished story as proof of customer value.
