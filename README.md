# Brill Python Prototype (Archived)

> **Status: Archived.** This was an early Python prototype exploring bridge bidding concepts. The project has been superseded by [BrillSolution](https://github.com/ThorvaldAagaard/BrillSolution), a full C#/.NET implementation with 170,000+ bidding rules, multiple cardplay engines, and cross-platform support.

**Brill** was an early concept for an intelligent bridge-playing robot that combines rule-based logic with AI-driven strategy. The ideas explored here — a DSL for bidding rules, JSON-based bidding system definitions, and rule evaluation engines — have been carried forward into the production implementation.

## What Was Explored Here

- **Bidding System DSL** — A custom domain-specific language for defining bridge bidding rules with priorities, auction contexts, and hand requirements.
- **JSON Bidding System** — A structured JSON format (with JSON Schema) for representing bidding rules, definitions, and rule sets.
- **Rule Evaluation Engine** — Converting DSL conditions like `HCP >= 15 AND IsHandType("Balanced")` into evaluable Python expressions.
- **Hand Analysis GUI** — A Kivy-based interface for evaluating hands against custom rules and generating hands matching criteria.
- **Bridge System Editor** — An HTML-based editor for creating and editing bidding system JSON files.

## Technologies

- **Python** with Kivy (GUI), asteval (expression evaluation), redeal (hand generation)

## See Also

The production version of Brill is at [github.com/ThorvaldAagaard/BrillSolution](https://github.com/ThorvaldAagaard/BrillSolution).
