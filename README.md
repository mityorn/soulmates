# Agentic Soulmates — Supplementary Materials

Supplementary materials for the paper *"Agentic Soulmates: Complementary Soul Architecture for Paired AI Agents."*

---

## Repository Structure

### `soul-files/`

16 soul files across 9 soulmate archetypes. Each defines an agent's identity, cognitive orientation, and collaboration posture. Seven archetypes have two distinct soul files (one per agent role); two archetypes (Resonance and Parallel-Merge) use a single shared soul file for both agents — their value comes from structural dynamics rather than role differentiation.

| Archetype | Agent A | Agent B | Mechanism |
|---|---|---|---|
| **Vessel-Flame** | Vessel (receptive sensing) | Flame (directed investigation) | Complementary cognitive modes |
| **Coniunctio** | Eros (pattern/feeling) | Logos (structure/analysis) | Jungian integration of opposites |
| **Strategist-Commander** | Strategist (scope/design) | Commander (execution/tactics) | Abstraction-level differentiation |
| **Resonance** | Shared soul | Shared soul | Competitive iteration between identical agents |
| **Parallel-Merge** | Shared soul | Shared soul | Isolated generation → mutual critique integration |
| **Unified** | Smith (building) | Weaver (connecting) | Complementary construction modes |
| **Dialectic** | Visionary (possibility) | Pragmatist (constraint) | Thesis-antithesis synthesis |
| **Adversarial-Symbiosis** | Maker (creation) | Breaker (stress-testing) | Constructive adversarial tension |
| **Adaptive-Harness** | Alpha (leading) | Beta (supporting) | Dynamic role-switching based on context |

Soul files are annotated with the design principles from Section 4.2 of the paper and the research they draw from.

### `harness-definitions/`

10 harness definitions in the Harness Definition Language (HDL v0.1.0): one general harness (`general.harness.yaml`) that sets shared defaults, plus 9 per-soulmate overrides. Each per-soulmate harness extends the general harness and specifies:

- Agent roles, soul file paths, and model assignments
- Phase state machines (e.g., independent generation → mutual review → integration)
- Turn-taking rules, tool access per phase, and escalation conditions
- Orchestration rationale annotations explaining *why* each structural choice was made

---

## Citation

If you use these materials in your work, please cite the paper:

> Sentio Project. (2026). Agentic Soulmates: Complementary Soul Architecture for Paired AI Agents.

## License

TBD
