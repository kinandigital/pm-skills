# PM Skills

65 product management skills across 8 domains, based on proven PM frameworks. Compatible with Claude Code, Gemini CLI, Cursor, OpenCode, Codex CLI, Kiro, and any tool that reads the `SKILL.md` format.

Based on [phuryn/pm-skills](https://github.com/phuryn/pm-skills) by Paweł Huryn.

## Structure

```
pm-<domain>/
└── skills/
    └── <skill-name>/
        └── SKILL.md
```

## Skills by Domain

### pm-product-discovery (13 skills)

| Skill | Description |
|-------|-------------|
| brainstorm-ideas-existing | Multi-perspective ideation for existing products (PM, Designer, Engineer) |
| brainstorm-ideas-new | Ideation for new products in initial discovery |
| brainstorm-experiments-existing | Design experiments to test assumptions for existing products |
| brainstorm-experiments-new | Design lean startup pretotypes for new products |
| identify-assumptions-existing | Identify risky assumptions across Value, Usability, Viability, Feasibility |
| identify-assumptions-new | Identify risky assumptions across 8 risk categories |
| prioritize-assumptions | Prioritize assumptions using Impact x Risk matrix |
| prioritize-features | Prioritize feature backlog by impact, effort, risk, alignment |
| analyze-feature-requests | Analyze and categorize feature requests by theme and strategic fit |
| opportunity-solution-tree | Build an OST (Teresa Torres) — outcome to opportunities to solutions to experiments |
| interview-script | Structured customer interview script with JTBD probing questions |
| summarize-interview | Summarize interview transcript into JTBD, satisfaction signals, action items |
| metrics-dashboard | Design a metrics dashboard with North Star, input metrics, alert thresholds |

### pm-product-strategy (12 skills)

| Skill | Description |
|-------|-------------|
| product-strategy | 9-section Product Strategy Canvas (vision to defensibility) |
| startup-canvas | Startup Canvas combining Product Strategy + Business Model |
| product-vision | Craft an inspiring, achievable product vision |
| value-proposition | 6-part JTBD value proposition template |
| lean-canvas | Lean Canvas business model for startups |
| business-model | Business Model Canvas with all 9 building blocks |
| monetization-strategy | Brainstorm 3-5 monetization strategies with validation experiments |
| pricing-strategy | Pricing models, competitive analysis, willingness-to-pay |
| swot-analysis | SWOT analysis with actionable recommendations |
| pestle-analysis | Macro environment: Political, Economic, Social, Technological, Legal, Environmental |
| porters-five-forces | Competitive forces analysis |
| ansoff-matrix | Growth strategy across markets and products |

### pm-execution (15 skills)

| Skill | Description |
|-------|-------------|
| create-prd | 8-section PRD template |
| brainstorm-okrs | Team-level OKRs aligned with company objectives |
| outcome-roadmap | Transform feature list into outcome-focused roadmap |
| sprint-plan | Sprint planning with capacity, story selection, risks |
| retro | Structured sprint retrospective facilitation |
| release-notes | User-facing release notes from tickets or PRDs |
| pre-mortem | Risk analysis with Tigers/Paper Tigers/Elephants classification |
| stakeholder-map | Power x Interest grid with communication plan |
| summarize-meeting | Meeting transcript to decisions + action items |
| user-stories | User stories following 3 C's and INVEST criteria |
| job-stories | Job stories: When [situation], I want to [motivation], so I can [outcome] |
| wwas | Backlog items in Why-What-Acceptance format |
| test-scenarios | Happy paths, edge cases, error handling |
| dummy-dataset | Realistic dummy datasets as CSV, JSON, SQL, or Python |
| prioritization-frameworks | Reference guide to 9 frameworks (RICE, ICE, Kano, MoSCoW, etc.) |

### pm-market-research (7 skills)

| Skill | Description |
|-------|-------------|
| user-personas | Refined personas from research data with JTBD, pains, gains |
| market-segments | 3-5 customer segments with demographics and JTBD |
| user-segmentation | Segment users from feedback by behavior and needs |
| customer-journey-map | End-to-end journey with stages, touchpoints, emotions, pain points |
| market-sizing | TAM, SAM, SOM with top-down and bottom-up approaches |
| competitor-analysis | Competitor strengths, weaknesses, differentiation opportunities |
| sentiment-analysis | Sentiment analysis and theme extraction from user feedback |

### pm-data-analytics (3 skills)

| Skill | Description |
|-------|-------------|
| sql-queries | Generate SQL from natural language (BigQuery, PostgreSQL, MySQL) |
| cohort-analysis | Retention curves, feature adoption, engagement trends by cohort |
| ab-test-analysis | Statistical significance, sample size validation, ship/extend/stop recommendations |

### pm-go-to-market (6 skills)

| Skill | Description |
|-------|-------------|
| gtm-strategy | Full GTM strategy: channels, messaging, metrics, launch plan |
| beachhead-segment | Identify first beachhead market segment |
| ideal-customer-profile | ICP with demographics, behaviors, JTBD, needs |
| growth-loops | Design sustainable growth loops (flywheels) |
| gtm-motions | Evaluate GTM motions (product-led, sales-led, etc.) |
| competitive-battlecard | Sales-ready battlecard with objection handling |

### pm-marketing-growth (5 skills)

| Skill | Description |
|-------|-------------|
| marketing-ideas | Creative marketing ideas with channels and messaging |
| positioning-ideas | Product positioning differentiated from competitors |
| value-prop-statements | Value proposition statements for marketing, sales, onboarding |
| product-name | Product name brainstorming aligned to brand and audience |
| north-star-metric | North Star Metric + input metrics with business game classification |

### pm-toolkit (4 skills)

| Skill | Description |
|-------|-------------|
| review-resume | PM resume review against 10 best practices |
| draft-nda | NDA with jurisdiction-appropriate clauses |
| privacy-policy | Privacy policy covering GDPR/CCPA |
| grammar-check | Grammar, logic, and flow checking with targeted fixes |

## Usage

Each `SKILL.md` follows the universal skill format and works with any AI assistant that reads it. Copy skill folders to your tool's skills directory:

| Tool | Path |
|------|------|
| Gemini CLI | `.gemini/skills/` |
| OpenCode | `.opencode/skills/` |
| Cursor | `.cursor/skills/` |
| Codex CLI | `.codex/skills/` |
| Kiro | `.kiro/skills/` |

## License

MIT
