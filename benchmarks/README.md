# Benchmarks

This directory contains the official benchmark suite for the AI Evaluation Framework.

Each benchmark provides a standardized evaluation package for comparing AI model responses across one or more domains using a consistent, evidence-based methodology.

---

## Benchmark Structure

Every benchmark should contain the following files:

| File | Purpose |
|------|---------|
| `README.md` | Benchmark overview and documentation |
| `metadata.yml` | Machine-readable benchmark metadata |
| `prompt.md` | Original benchmark prompt |
| `responses.md` | Raw responses from the evaluated models |
| `evaluation.md` | Complete evaluation report |

---

## Benchmark Template

Use the `benchmark-template/` directory as the starting point for creating a new benchmark.

The template ensures that every benchmark follows the same structure, methodology, and documentation standards defined by the AI Evaluation Framework.

---

## Repository Standards

All benchmarks should:

- Follow the AI Evaluation Framework methodology.
- Apply the appropriate domain-specific rubrics.
- Use evidence-based evaluations.
- Document evaluation decisions transparently.
- Include reproducible prompts and model responses.
- Maintain a consistent reporting structure across the repository.
