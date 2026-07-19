---
title: "10 High-ROI Product Management Prompts"
domain: solopreneur
source_url: "https://www.reddit.com/r/promptingmagic/comments/1np1r4u"
platform: reddit
author: "u/Beginning-Willow-801"
---

# 10 High-ROI Product Management Prompts

[← All prompt packs](../../CATALOG.md) · **Solopreneur** · [Original post ↗](https://www.reddit.com/r/promptingmagic/comments/1np1r4u)

## Prompts

Copy a prompt and replace the bracketed text with your own context.

### 1. Strategic Product Ideation

```text
# Role
You are an experienced Product Trio (PM, Designer, Engineer) performing continuous product discovery.

# Objectives
Generate product ideas that increase user retention by 30% for our [product type] serving [target market].

# Context
- Current retention rate: [X%]
- Top churn reasons: [List top 3]
- User feedback themes: [Key patterns]
- Competitive advantages: [Your strengths]
# Process
1. Analyze retention challenges from each trio perspective
2. Generate 5 ideas per role (15 total)
3. Rank top 5 by impact/effort matrix
4. Include implementation timeline and success metrics

# Output Format
- Idea name
- Problem it solves
- Target user segment
- Expected impact (quantified)
- Implementation effort (T-shirt size)
- Key assumptions to validate
```

### 2. Competitor Intelligence Analysis

```text
# Role
Senior User Researcher specializing in competitive analysis and sentiment monitoring.

# Objective
Analyze competitor [Company Name] to identify product gaps and positioning opportunities.

# Data Sources
- Customer reviews from G2, Capterra, App Store
- Reddit discussions in [relevant subreddits]
- Recent product announcements
- Pricing changes
# Analysis Framework
1. Identify top 5 user personas from reviews
2. Extract satisfaction scores and pain points per persona
3. Map feature gaps compared to our product
4. Recommend 3 strategic opportunities

# Output
- Persona summaries with satisfaction scores (-1 to +1)
- Feature gap analysis matrix
- Strategic recommendations with business impact estimates
```

### 3. Data-Driven User Stories

```text
# Role
Senior Product Manager with 10+ years experience writing exceptional user stories.

# Context
Feature: [Feature name]
User research findings: [Key insights]
Business objective: [Specific goal]

# Requirements
Follow INVEST principles (Independent, Negotiable, Valuable, Estimable, Small, Testable)
Include acceptance criteria with edge cases
Write for primary school reading level
Focus on user value, not features
# Template
As a [specific user type with context]
I want to [specific action with clear intent]
So that I can [specific outcome with measurable value]

**Acceptance Criteria:**
- [Testable condition 1]
- [Testable condition 2]
- [Edge case handling]

**Definition of Done:**
- [Technical requirements]
- [UX requirements]
- [Analytics tracking]
```

### 4. Meeting Intelligence

```text
# Role
Executive assistant specializing in extracting actionable insights from product meetings.

# Instructions
Analyze this meeting transcript and extract:

1. **Key Decisions Made**
   - Decision
   - Rationale
   - Owner
   - Timeline

2. **Action Items**
   - Task
   - Owner
   - Due date
   - Dependencies
3. **Assumptions Identified**
   - Assumption
   - Risk level (High/Medium/Low)
   - Validation method needed

4. **Strategic Insights**
   - Patterns in discussion
   - Unresolved tensions
   - Opportunities not discussed

# Output Format
Executive summary (2-3 sentences) followed by structured sections above.
```

### 5. Devil's Advocate Analysis

```text
# Role
Experienced Product Strategist known for identifying blind spots and challenging assumptions.

# Your Mission
Play devil's advocate for this product decision: [Your decision]

# Challenge Areas
1. **Market Assumptions**
   - What if the market doesn't respond as expected?
   - What competing priorities might users have?
2. **Technical Risks**
   - What could go wrong during implementation?
   - What dependencies could fail?

3. **Business Model Threats**
   - What if competitors copy this quickly?
   - What if costs exceed projections?

4. **User Behavior**
   - What if users don't adopt as predicted?
   - What alternative solutions might they prefer?
# Output
- 5 highest-risk assumptions
- Potential failure scenarios
- Recommended validation experiments
- Contingency plans
```

### 6. Experiment Design

```text
# Role
Growth PM and experimentation expert with proven track record of designing high-impact tests.

# Objective
Design an A/B test to [specific goal] for [specific user segment].

# Context
- Current baseline metric: [X]
- Target improvement: [Y%]
- Available traffic: [Z users/week]
- Test duration limit: [N weeks]
# Requirements
1. Formulate clear hypothesis with reasoning
2. Define primary and secondary metrics
3. Calculate required sample size and test duration
4. Identify potential confounding variables
5. Plan analysis approach

# Output Template
**Hypothesis:** If we [change], then [metric] will [improve by X%] because [reasoning based on user psychology/behavior]
**Test Design:**
- Control: [Current experience]
- Treatment: [New experience]
- Success metrics: [Primary and secondary]
- Guardrail metrics: [What we can't hurt]
- Sample size needed: [Calculated number]
- Test duration: [Timeline with rationale]

**Analysis Plan:**
- Statistical method
- Segmentation approach
- Decision framework for results
```

### 7. SQL Query Generation

```text
# Role
Senior Data Analyst specializing in product analytics with expertise in [your database type].

# Database Schema Context
[Provide relevant table structures, relationships, and key fields]

# Business Question
[Your specific analytics question]
# Requirements
1. Generate optimized SQL query
2. Include comments explaining logic
3. Handle edge cases (null values, data quality issues)
4. Optimize for performance on large datasets
5. Provide sample output interpretation

# Additional Context
- Database type: [PostgreSQL/MySQL/BigQuery/etc.]
- Approximate table sizes: [For performance optimization]
- Date ranges typically queried: [For partitioning considerations]
# Output
- SQL query with detailed comments
- Expected output format
- Performance optimization notes
- Data interpretation guidance
```

### 8. Customer Interview Analysis

```text
# Role
UX Researcher expert in qualitative data analysis and pattern recognition.

# Instructions
Analyze these customer interview transcripts to identify:

1. **Job-to-be-Done Analysis**
   - Functional jobs
   - Emotional jobs
   - Social jobs

2. **Pain Point Categories**
   - Severity (High/Medium/Low)
   - Frequency
   - Current workarounds
3. **Opportunity Areas**
   - Unmet needs
   - Feature gaps
   - Process improvements

4. **User Quotes**
   - Most compelling quotes per theme
   - Voice of customer for stakeholder presentations

# Context
Product: [Your product]
Interview focus: [Research objectives]
Number of interviews: [X]
# Output Format
- Executive summary with key insights
- Structured findings with supporting quotes
- Prioritized opportunity backlog
- Recommended next research steps
```

### 9. PRD Template Generation

```text
# Role
Senior Product Manager creating a comprehensive PRD template optimized for [your company type/size].

# Requirements
Create a PRD template that includes:

1. **Strategic Alignment**
   - Problem statement
   - Success metrics
   - Business impact

2. **User Research Foundation**
   - User personas
   - Use cases
   - User journey integration
3. **Technical Specifications**
   - Functional requirements
   - Non-functional requirements
   - Integration points

4. **Go-to-Market Elements**
   - Launch strategy
   - Success metrics
   - Risk mitigation

# Context
- Company stage: [Startup/Growth/Enterprise]
- Product type: [B2B SaaS/B2C App/etc.]
- Team structure: [Your team composition]
- Development process: [Agile/Scrum/etc.]
# Output
Comprehensive PRD template with:
- Section descriptions and purposes
- Guiding questions for each section
- Example content for clarity
- Stakeholder review checkpoints
```

### 10. Competitive Feature Analysis

```text
# Role
Competitive intelligence analyst with deep expertise in [your industry].

# Objective
Conduct comprehensive competitive feature analysis for [specific feature/product area].

# Competitors to Analyze
[List 3-5 main competitors]

# Analysis Framework
1. **Feature Comparison Matrix**
   - Core capabilities
   - Implementation approach
   - User experience quality
2. **Positioning Analysis**
   - Target user segments
   - Value propositions
   - Pricing strategies

3. **Gap Analysis**
   - Features we lack
   - Features they lack
   - Differentiation opportunities

4. **Strategic Recommendations**
   - Build vs. buy vs. partner decisions
   - Feature prioritization
   - Go-to-market implications
# Data Sources
- Product websites and documentation
- User reviews and feedback
- Demo videos and screenshots
- Pricing pages

# Output Format
- Executive summary with key findings
- Detailed feature comparison matrix
- SWOT analysis per competitor
- Strategic recommendations with rationale
```
