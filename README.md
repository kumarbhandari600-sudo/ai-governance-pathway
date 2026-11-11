# AI Governance Implementation Pathway

**A four-checkpoint governance pathway for agentic AI in Australian IT project management.**

## The problem

Australian IT project managers are deploying AI agents faster than they can govern them. Gartner forecasts that more than 40% of agentic AI projects will be canceled by 2027 due to escalating costs, unclear business value, or inadequate risk controls (Gartner, 2025). Only 21% of companies surveyed globally have a mature governance model for AI agents (Deloitte, 2026).

## The evidence

- No standard reference architecture exists for governing enterprise AI agents (Venkiteela, 2026).
- Existing governance frameworks are structurally insufficient for agentic AI (Venkiteela, 2026).
- Abstract guidelines lack operational specificity (Kladko et al., 2026).

## The solution

A four-checkpoint pathway aligned to NIST AI RMF:

1. **Govern** — accountability roles defined
2. **Map** — decision points documented
3. **Measure** — bias and accuracy metrics
4. **Manage** — review and correction process

## Project plan

See the [Project Board](https://github.com/kumarbhandari600-sudo/ai-governance-pathway/projects).

**Part B milestones:**
- Week 8: Four checkpoints defined
- Week 10: Bias-audit protocol documented and validation complete

## Ethics, privacy and responsible AI

This project is bound by the ACS Code of Professional Conduct, Australia's AI Ethics Principles, and the NIST AI RMF. The key ethical dilemma is algorithmic bias in AI-assisted prioritisation. The Measure checkpoint requires a bias-audit protocol with measurable fairness indicators.

## Sustainability

AI inference has an environmental cost. Li et al. (2025) model a scenario where GPT-3 consumes a 500ml bottle of water for roughly 10–50 medium-length responses. The pathway includes an environmental impact assessment as part of the Measure checkpoint.

## Team

- **Kumar Jung Bhandari** (shea26023) — evidence review, gap analysis, methodology, project plan, risk register
- **Reejan Khadka** (shea26024) — ethics, sustainability, stakeholder plan, bias-audit protocol

## Documents

- [Risk Register](docs/risk-register.md)
- [RACI Matrix](docs/raci.md)
- [Methodology](docs/methodology.md)

## Acknowledgements

Academic Mentor. AI Use Statement: Claude used for structure critique and grammar checking.
``` gantt
    title Part B Project Plan
    dateFormat  X
    axisFormat %s
    section Discovery
    1.1 Review evidence (Kumar) :a1, 1, 1w
    1.2 Draft checkpoints (Reejan) :a2, after a1, 2w
    1.3 Design protocol (Reejan) :a3, 4, 2w
    section Build
    2.1 Build templates (Kumar) :a4, 6, 2w
    2.2 Build protocol (Reejan) :a5, 6, 2w
    2.3 Build framework (Kumar) :a6, 8, 1w
    section Validate
    3.1 Ethics application (Reejan) :a7, 6, 1w
    3.2 Internal review (Kumar) :a8, 9, 1w
    3.3 External review 1 (Reejan) :a9, 9, 2w
    3.4 External review 2 (Kumar) :a10, 9, 2w
    section Document
    4.1 Evaluation report (Kumar) :a11, 10, 1w
    4.2 Handover document (Reejan) :a12, 10, 1w
    4.3 Final submission (Kumar) :a13, 10, 1w ```
