# PM Skills

65 product management skills across 8 domains, based on proven PM frameworks. Compatible with Claude Code, Gemini CLI, Cursor, OpenCode, Codex CLI, Kiro, and any tool that reads the `SKILL.md` format.

Based on [phuryn/pm-skills](https://github.com/phuryn/pm-skills) by Paweł Huryn.

## Why PM Skills?

Generic AI gives you text. PM Skills gives you structure.

Each skill encodes a proven PM framework — discovery, assumption mapping, prioritization, strategy — and walks you through it step by step. You get the rigor of Teresa Torres, Marty Cagan, and Alberto Savoia built into your daily workflow, not sitting on a bookshelf.

The result: better product decisions, not just faster documents.

## How Skills Work

Skills give AI domain knowledge, analytical frameworks, or a guided workflow for a specific PM task. They are loaded automatically when relevant to the conversation — no explicit invocation needed. If needed, you can force-load a skill with `/skill-name`.

Some skills (like `prioritization-frameworks` or `opportunity-solution-tree`) are standalone references that the AI draws on whenever relevant — no invocation needed.

## Structure

```
pm-<domain>/<skill-name>/SKILL.md
```

## Skills by Domain

### pm-product-discovery — Ideation, experiments, assumption testing, OSTs, interviews (13 skills)

| Skill | Description |
|-------|-------------|
| brainstorm-ideas-existing | Brainstorm product ideas for an existing product using multi-perspective ideation from PM, Designer, and Engineer viewpoints. Use when generating new feature ideas, brainstorming solutions for an identified opportunity, or ideating with a product trio. |
| brainstorm-ideas-new | Brainstorm feature ideas for a new product in initial discovery from PM, Designer, and Engineer perspectives. Use when starting product discovery for a new product, exploring features for a startup idea, or doing initial ideation. |
| brainstorm-experiments-existing | Design experiments to test assumptions for an existing product — prototypes, A/B tests, spikes, and other low-effort validation methods. Use when validating assumptions, testing feature ideas cheaply, or planning product experiments. |
| brainstorm-experiments-new | Design lean startup experiments (pretotypes) for a new product. Creates XYZ hypotheses and suggests low-effort validation methods like landing pages, explainer videos, and pre-orders. Use when validating a new product idea, creating pretotypes, or testing market demand. |
| identify-assumptions-existing | Identify risky assumptions for a feature idea in an existing product across Value, Usability, Viability, and Feasibility. Uses multi-perspective devil's advocate thinking. Use when stress-testing a feature idea, doing risk assessment, or preparing for assumption mapping. |
| identify-assumptions-new | Identify risky assumptions for a new product idea across 8 risk categories including Go-to-Market, Strategy, and Team. Use when evaluating startup risks, assessing a new product concept, or mapping assumptions for a new venture. |
| prioritize-assumptions | Prioritize assumptions using an Impact × Risk matrix and suggest experiments for each. Use when triaging a list of assumptions, deciding what to test first, or applying the assumption prioritization canvas. |
| prioritize-features | Prioritize a backlog of feature ideas based on impact, effort, risk, and strategic alignment with top 5 recommendations. Use when prioritizing a feature backlog, making scope decisions, or ranking product ideas. |
| analyze-feature-requests | Analyze and prioritize a list of feature requests by theme, strategic alignment, impact, effort, and risk. Use when reviewing customer feature requests, triaging a backlog, or making prioritization decisions. |
| opportunity-solution-tree | Build an Opportunity Solution Tree (OST) to structure product discovery — map a desired outcome to opportunities, solutions, and experiments. Based on Teresa Torres' Continuous Discovery Habits. Use when structuring discovery work, mapping opportunities to solutions, or deciding what to build next. |
| interview-script | Create a structured customer interview script with JTBD probing questions, warm-up, core exploration, and wrap-up sections. Follows The Mom Test principles — no leading questions, no pitching, focus on past behavior. Use when preparing for user interviews, creating interview guides, or planning discovery research. |
| summarize-interview | Summarize a customer interview transcript into a structured template with JTBD, satisfaction signals, and action items. Use when processing interview recordings or transcripts, synthesizing discovery interviews, or creating interview summaries. |
| metrics-dashboard | Define and design a product metrics dashboard with key metrics, data sources, visualization types, and alert thresholds. Use when creating a metrics dashboard, defining KPIs, setting up product analytics, or building a data monitoring plan. |

**Examples:**
- `What are the riskiest assumptions for our AI writing assistant idea?`
- `Help me build an Opportunity Solution Tree for improving user activation`
- `Prioritize these 12 feature requests from our enterprise customers [attach CSV]`

### pm-product-strategy — Vision, business models, pricing, competitive landscape (12 skills)

| Skill | Description |
|-------|-------------|
| product-strategy | Create a comprehensive product strategy using the 9-section Product Strategy Canvas — vision, segments, costs, value propositions, trade-offs, metrics, growth, capabilities, and defensibility. Use when building a product strategy, creating a strategic plan, or defining product direction. |
| startup-canvas | Generate a Startup Canvas combining Product Strategy (9 sections) and Business Model (costs + revenue) for a new product. An alternative to BMC and Lean Canvas that separates strategy from business model. Use when launching a new product or evaluating a startup concept. |
| product-vision | Brainstorm an inspiring, achievable, and emotional product vision that motivates teams and aligns stakeholders. Use when defining or refining a product vision, creating a vision statement, or aligning the team around a shared direction. |
| value-proposition | Design a detailed value proposition using a 6-part JTBD template — Who, Why, What before, How, What after, Alternatives. Use when creating a value proposition, analyzing customer value delivery, or articulating why customers should choose your product. |
| lean-canvas | Generate a Lean Canvas with problem, solution, metrics, cost structure, UVP, unfair advantage, channels, segments, and revenue. Use when exploring a lean startup canvas, testing a business hypothesis, or modeling a new venture. |
| business-model | Generate a Business Model Canvas with all 9 building blocks. Use when creating a business model, documenting how a business creates value, or analyzing an existing business model. |
| monetization-strategy | Brainstorm 3-5 monetization strategies with audience fit, risks, and validation experiments. Use when exploring revenue models, evaluating pricing strategies, or deciding how to monetize a product. |
| pricing-strategy | Analyze and design pricing strategies including pricing models, competitive pricing analysis, willingness-to-pay estimation, and price elasticity. Use when setting prices, evaluating pricing models, preparing for a pricing change, or comparing freemium vs paid approaches. |
| swot-analysis | Perform a detailed SWOT analysis — strengths, weaknesses, opportunities, and threats with actionable recommendations. Use when doing strategic assessment, competitive analysis, or evaluating a product or business position. |
| pestle-analysis | Perform a PESTLE analysis covering Political, Economic, Social, Technological, Legal, and Environmental factors. Use when assessing the macro environment, doing strategic planning, or evaluating external factors affecting your business. |
| porters-five-forces | Perform Porter's Five Forces analysis — competitive rivalry, supplier power, buyer power, threat of substitutes, and threat of new entrants. Use when analyzing industry dynamics, assessing competitive forces, or evaluating market attractiveness. |
| ansoff-matrix | Generate an Ansoff Matrix analysis mapping growth strategies across market penetration, market development, product development, and diversification. Use when considering growth options, planning market expansion, or evaluating strategic growth paths. |

**Examples:**
- `Compare Lean Canvas vs Business Model Canvas vs Startup Canvas for my marketplace startup`
- `Design a value proposition for our AI writing assistant targeting non-native English speakers`
- `Run a Porter's Five Forces analysis for the project management SaaS market`

### pm-execution — PRDs, OKRs, roadmaps, sprints, retros, release notes, stakeholder management (15 skills)

| Skill | Description |
|-------|-------------|
| create-prd | Create a Product Requirements Document using a comprehensive 8-section template covering problem, objectives, segments, value propositions, solution, and release planning. Use when writing a PRD, documenting product requirements, preparing a feature spec, or reviewing an existing PRD. |
| brainstorm-okrs | Brainstorm team-level OKRs aligned with company objectives — qualitative objectives with measurable key results. Use when setting quarterly OKRs, aligning team goals with company strategy, drafting objectives, or learning how to write effective OKRs. |
| outcome-roadmap | Transform an output-focused roadmap into an outcome-focused one that communicates strategic intent. Rewrites initiatives as outcome statements reflecting user and business impacts. Use when shifting to outcome roadmaps, making a roadmap more strategic, or rewriting feature lists as outcomes. |
| sprint-plan | Plan a sprint with capacity estimation, story selection, dependency mapping, and risk identification. Use when preparing for sprint planning, estimating team capacity, selecting stories, or balancing sprint scope against velocity. |
| retro | Facilitate a structured sprint retrospective — what went well, what didn't, and prioritized action items with owners and deadlines. Use when running a retrospective, reflecting on a sprint, creating action items from team feedback, or learning how to run effective retros. |
| release-notes | Generate user-facing release notes from tickets, PRDs, or changelogs. Creates clear, engaging summaries organized by category (new features, improvements, fixes). Use when writing release notes, creating changelogs, announcing product updates, or summarizing what shipped. |
| pre-mortem | Run a pre-mortem risk analysis on a PRD or launch plan. Categorizes risks as Tigers (real problems), Paper Tigers (overblown concerns), and Elephants (unspoken worries), then classifies as launch-blocking, fast-follow, or track. Use when preparing for launch, stress-testing a product plan, or identifying what could go wrong. |
| stakeholder-map | Build a stakeholder map using a power/interest grid, identify communication strategies per quadrant, and generate a communication plan. Use when managing stakeholders, preparing for a launch, aligning cross-functional teams, or planning stakeholder engagement. |
| summarize-meeting | Summarize a meeting transcript into structured notes with date, participants, topic, key decisions, summary points, and action items. Use when processing meeting recordings, creating meeting notes, writing meeting minutes, or recapping discussions. |
| user-stories | Create user stories following the 3 C's (Card, Conversation, Confirmation) and INVEST criteria with descriptions, design links, and acceptance criteria. Use when writing user stories, breaking down features into backlog items, or defining acceptance criteria. |
| job-stories | Create job stories using the 'When [situation], I want to [motivation], so I can [outcome]' format with detailed acceptance criteria. Use when writing job stories, creating JTBD-style backlog items, or expressing user situations and motivations. |
| wwas | Create product backlog items in Why-What-Acceptance format — independent, valuable, testable items with strategic context. Use when writing structured backlog items, breaking features into work items, or using the WWA format. |
| test-scenarios | Create comprehensive test scenarios from user stories with test objectives, starting conditions, user roles, step-by-step actions, and expected outcomes. Use when writing QA test cases, creating test plans, defining acceptance tests, or preparing for feature validation. |
| dummy-dataset | Generate realistic dummy datasets for testing with customizable columns, constraints, and output formats (CSV, JSON, SQL, Python script). Use when creating test data, building mock datasets, or generating sample data for development and demos. |
| prioritization-frameworks | Reference guide to 9 prioritization frameworks with formulas, when-to-use guidance, and templates — RICE, ICE, Kano, MoSCoW, Opportunity Score, and more. Use when selecting a prioritization method, comparing frameworks like RICE vs ICE, or learning how different prioritization approaches work. |

**Examples:**
- `Which prioritization framework should I use for a 50-item backlog?`
- `Map our stakeholders for the platform migration project`
- `What's the difference between Opportunity Score, ICE, and RICE?`

### pm-market-research — Personas, segmentation, journey maps, market sizing, competitor analysis (7 skills)

| Skill | Description |
|-------|-------------|
| user-personas | Create refined user personas from research data — 3 personas with JTBD, pains, gains, and unexpected insights. Use when building personas from survey data, creating user profiles from research, or segmenting users for product decisions. |
| market-segments | Identify 3-5 potential customer segments with demographics, JTBD, and product fit analysis. Use when exploring market segments, identifying target audiences, evaluating new markets, or learning how to segment a market. |
| user-segmentation | Segment users from feedback data based on behavior, JTBD, and needs. Identifies at least 3 distinct user segments. Use when segmenting a user base, analyzing diverse user feedback, or building a segmentation model. |
| customer-journey-map | Create an end-to-end customer journey map with stages, touchpoints, emotions, pain points, and opportunities. Use when mapping the customer experience, identifying friction points, improving onboarding, or visualizing the user journey. |
| market-sizing | Estimate market size using TAM, SAM, and SOM with top-down and bottom-up approaches. Use when sizing a market opportunity, estimating addressable market, preparing for investor pitches, or evaluating market entry. |
| competitor-analysis | Analyze competitors with strengths, weaknesses, and differentiation opportunities. Identifies direct competitors and maps the competitive landscape. Use when doing competitive research, preparing a competitive brief, or finding differentiation opportunities. |
| sentiment-analysis | Analyze user feedback data to identify segments with sentiment scores, JTBD, and product satisfaction insights. Use when analyzing user feedback at scale, running sentiment analysis on reviews or surveys, or identifying satisfaction patterns. |

**Examples:**
- `Estimate TAM/SAM/SOM for an AI code review tool in the US market`
- `Create a customer journey map for our e-commerce checkout flow`
- `Segment these survey respondents by behavior and needs [attach CSV]`

### pm-data-analytics — SQL generation, cohort analysis, A/B test analysis (3 skills)

| Skill | Description |
|-------|-------------|
| sql-queries | Generate SQL queries from natural language descriptions. Supports BigQuery, PostgreSQL, MySQL, and other dialects. Reads database schemas from uploaded diagrams or documentation. Use when writing SQL, building data reports, exploring databases, or translating business questions into queries. |
| cohort-analysis | Perform cohort analysis on user engagement data — retention curves, feature adoption trends, and segment-level insights. Use when analyzing user retention by cohort, studying feature adoption over time, investigating churn patterns, or identifying engagement trends. |
| ab-test-analysis | Analyze A/B test results with statistical significance, sample size validation, confidence intervals, and ship/extend/stop recommendations. Use when evaluating experiment results, checking if a test reached significance, interpreting split test data, or deciding whether to ship a variant. |

**Examples:**
- `How large a sample do I need for 95% confidence with a 2% MDE?`
- `What retention metrics should I track for a subscription app?`

### pm-go-to-market — Beachhead segments, ICPs, messaging, growth loops, GTM motions, battlecards (6 skills)

| Skill | Description |
|-------|-------------|
| gtm-strategy | Create a go-to-market strategy covering marketing channels, messaging, success metrics, and launch timeline. Use when planning a product launch, creating a GTM plan from scratch, or defining a launch strategy for a new market. |
| beachhead-segment | Identify the first beachhead market segment for a product launch. Evaluates segments against burning pain, willingness to pay, winnable market share, and referral potential. Use when choosing a first market, targeting an initial customer segment, or planning market entry strategy. |
| ideal-customer-profile | Identify the Ideal Customer Profile (ICP) from research data with demographics, behaviors, JTBD, and needs. Use when defining your ICP, analyzing PMF survey data, or understanding who your best customers are. |
| growth-loops | Identify growth loops (flywheels) for sustainable traction. Evaluates 5 loop types: Viral, Usage, Collaboration, User-Generated, and Referral. Use when designing growth mechanisms, building product-led traction, or understanding how growth loops work. |
| gtm-motions | Identify the best GTM motions and tools across 7 motion types: Inbound, Outbound, Paid Digital, Community, Partners, ABM, and PLG. Use when selecting marketing channels, choosing between inbound and outbound strategy, or planning cross-channel campaigns. |
| competitive-battlecard | Create sales-ready competitive battlecards comparing your product against a specific competitor — positioning, feature comparison, objection handling, and win/loss patterns. Use when preparing sales teams, creating competitive materials, or responding to 'why not competitor X?' |

**Examples:**
- `What's the best beachhead segment for a developer productivity tool?`
- `Design a growth loop for a B2B SaaS with a freemium tier`
- `Define our ICP for an AI-powered HR screening platform`

### pm-marketing-growth — Marketing ideas, positioning, value props, naming, North Star metrics (5 skills)

| Skill | Description |
|-------|-------------|
| marketing-ideas | Generate 5 creative, cost-effective marketing ideas with channels, messaging, and engagement rationale. Use when brainstorming marketing campaigns, planning product promotion, or looking for creative marketing tactics. |
| positioning-ideas | Brainstorm product positioning ideas differentiated from competitors. Identifies top competitors and generates positioning statements with rationale. Use when developing product positioning, differentiating from competitors, or crafting brand positioning strategy. |
| value-prop-statements | Generate value proposition statements for marketing, sales, and onboarding from existing value propositions. Use when writing marketing copy, creating sales messaging, or crafting onboarding messages. |
| product-name | Brainstorm 5 unique, memorable product names with rationale aligned to brand values and target audience. Use when naming a new product, rebranding, or exploring product name ideas. |
| north-star-metric | Define a North Star Metric and 3-5 supporting input metrics that form a metrics constellation. Classify the business game (Attention, Transaction, Productivity) and validate against 7 criteria for an effective North Star. Use when choosing a North Star Metric, setting up a metrics framework, learning about the North Star Framework, or deciding what to measure. |

**Examples:**
- `Brainstorm 5 positioning angles that differentiate us from Notion`
- `What's a good North Star Metric for a two-sided marketplace?`
- `Generate value prop statements for our sales team's pitch deck`

### pm-toolkit — Resume review, legal documents, proofreading (4 skills)

| Skill | Description |
|-------|-------------|
| review-resume | Comprehensive PM resume review and tailoring against 10 best practices including XYZ+S formula, keyword optimization, job-specific tailoring, and structure. Use when reviewing a PM resume, preparing for job applications, or improving resume impact. |
| draft-nda | Draft a detailed Non-Disclosure Agreement between two parties covering information types, jurisdiction, and clauses needing legal review. Use when creating confidentiality agreements or preparing an NDA for a partnership. |
| privacy-policy | Draft a detailed privacy policy covering data types, jurisdiction, GDPR and compliance considerations, and clauses needing legal review. Use when creating a privacy policy, updating data protection documentation, or preparing for compliance. |
| grammar-check | Identify grammar, logical, and flow errors in text and suggest targeted fixes without rewriting the entire text. Use when proofreading content, checking writing quality, or reviewing a draft. |

**Examples:**
- `Review my PM resume against best practices [attach PDF]`
- `Check this product announcement for grammar and clarity`

## References

Skills are based on the work of:

- Teresa Torres — *Continuous Discovery Habits*
- Marty Cagan — *INSPIRED* and *TRANSFORMED*
- Alberto Savoia — *The Right It*
- Dan Olsen — *The Lean Product Playbook*
- Roger L. Martin — *Playing to Win*
- Ash Maurya — *Running Lean*
- Strategyzer — *Business Model Generation* and *Value Proposition Design*
- Christina Wodtke — *Radical Focus*
- Anthony W. Ulwick — *Jobs to Be Done*
- Alistair Croll & Benjamin Yoskovitz — *Lean Analytics*
- Sean Ellis — *Hacking Growth*
- Maja Voje — *Go-To-Market Strategist*

Curated by [The Product Compass Newsletter](https://www.productcompass.pm) by Paweł Huryn.

## License

MIT
