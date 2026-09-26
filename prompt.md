# College Canteen Optimization Challenge

<role>
You are a senior **Food-Service Operations Strategist, Pricing Analyst, and Demand Planner** specializing in small-budget college food-service operations.

Your objective is to design a **practical, financially controlled, one-week improvement strategy** for a college canteen operating under a strict ₹10,000 budget.
</role>

<context>
The college has allocated:

- **Total budget:** ₹10,000
- **Planning period:** 7 days
- **Potential student customer base:** 500 students
- **Customer profile:** Price-sensitive college students
- **Primary objective:** Improve the canteen's value proposition while maintaining financial sustainability
- **Operational assumption:** The canteen has normal cooking, storage, and serving facilities, but limited capacity compared with a large commercial restaurant.

The available information is intentionally limited. Where information is missing, make reasonable operational assumptions and explicitly label them as assumptions.
</context>

<objectives>
Optimize the plan across these five dimensions:

1. **Affordability** — prices must be realistic for college students.
2. **Demand** — prioritize products likely to have broad student appeal.
3. **Profitability** — maintain positive contribution margins.
4. **Waste control** — minimize unsold/perishable inventory.
5. **Operational simplicity** — avoid a menu that is difficult to prepare or serve during peak periods.

Do not optimize for profit alone. The final plan must balance all five dimensions.
</objectives>

<constraints>
Follow these rules strictly:

- Total initial spending MUST NOT exceed ₹10,000.
- The plan MUST cover exactly 7 days.
- Select **5–7 core menu items**.
- Do not assume that all 500 students will purchase food.
- Do not claim that a product is guaranteed to be popular.
- Treat demand, costs, and revenue as estimates unless provided as facts.
- Do not invent surveys, historical sales data, supplier quotations, or market research.
- Do not use unrealistic quantities that a normal college canteen could not prepare or store.
- Do not recommend unnecessarily complex technology, staffing, or infrastructure.
- Do not spend the entire budget on inventory; retain an operational contingency reserve.
- Do not hide assumptions inside calculations.
- Every financial figure must be internally consistent.
- If exact information is unavailable, use a reasonable estimate and clearly mark it.
</constraints>

<decision_framework>
Evaluate candidate menu items using:

**Expected contribution = Selling Price − Variable Cost per Unit**

Consider each item's:

- Expected demand
- Contribution margin
- Preparation complexity
- Preparation time
- Perishability
- Ingredient overlap with other items
- Ability to scale production
- Suitability for peak-hour service

Prefer ingredients that can be shared across multiple menu items to reduce inventory complexity and waste.
</decision_framework>

<demand_management>
Use a simple feedback system rather than preparing the same quantity every day.

Define:

- **Opening production quantity**
- **Reorder/extra-batch trigger**
- **Sell-out trigger**
- **Low-demand trigger**
- **Waste-control action**

Use the previous day's sales to adjust the next day's production.

For example:

- If an item sells >80% of its prepared quantity → increase next day's production moderately.
- If an item sells 50–80% → maintain approximately the same quantity.
- If an item sells <50% → reduce production and investigate pricing/product appeal.

Do not blindly apply these thresholds if they conflict with food safety, storage, or operational constraints.
</demand_management>

<required_analysis>

## 1. Assumptions

List every important assumption used for:

- Customer conversion
- Daily demand
- Ingredient costs
- Serving sizes
- Operating days
- Production capacity
- Waste
- Pricing

Separate **given information** from **assumptions**.

---

## 2. Menu Strategy

Select 5–7 menu items.

Use this exact table:

| # | Item | Category | Estimated Cost/Unit | Selling Price | Contribution/Unit | Initial Qty | Expected Weekly Sales |
|---|------|----------|--------------------:|--------------:|------------------:|------------:|----------------------:|

Explain briefly why each item was selected.

---

## 3. Budget Allocation

Provide:

| Budget Component | Allocation | % of Budget | Purpose |
|------------------|-----------:|------------:|---------|
| Ingredients | ₹X | X% | ... |
| Packaging/serving | ₹X | X% | ... |
| Contingency | ₹X | X% | ... |
| **TOTAL** | **₹10,000** | **100%** | |

The total MUST equal exactly ₹10,000.

---

## 4. Unit Economics

For every menu item calculate:

- Cost per unit
- Selling price
- Contribution per unit
- Estimated quantity sold
- Expected revenue
- Expected variable cost
- Expected contribution

Use:

**Revenue = Selling Price × Units Sold**

**Variable Cost = Cost per Unit × Units Sold**

**Contribution = Revenue − Variable Cost**

Do not confuse revenue with profit.

---

## 5. Seven-Day Operating Plan

Create a day-by-day operating table:

| Day | Production Focus | Expected Demand | Inventory Adjustment | Promotion/Action | Waste-Control Action |
|-----|------------------|----------------:|----------------------|------------------|----------------------|
| Day 1 | ... | ... | ... | ... | ... |
| Day 2 | ... | ... | ... | ... | ... |
| Day 3 | ... | ... | ... | ... | ... |
| Day 4 | ... | ... | ... | ... | ... |
| Day 5 | ... | ... | ... | ... | ... |
| Day 6 | ... | ... | ... | ... | ... |
| Day 7 | ... | ... | ... | ... | ... |

The strategy must evolve using observed sales rather than assuming demand stays constant.

---

## 6. Demand Scenarios

Model three scenarios:

### Conservative
Lower-than-expected demand.

### Base Case
Expected demand under the stated assumptions.

### High-Demand Case
Higher-than-expected demand.

For each scenario show:

| Scenario | Estimated Units Sold | Revenue | Cost | Contribution | Key Risk |
|----------|---------------------:|--------:|-----:|------------:|----------|
| Conservative | ... | ... | ... | ... | ... |
| Base Case | ... | ... | ... | ... | ... |
| High Demand | ... | ... | ... | ... | ... |

Do not present the base case as a guaranteed outcome.

---

## 7. Contingency & Failure Handling

Define the response to each situation:

| Situation | Immediate Response | Next-Day Adjustment |
|-----------|--------------------|---------------------|
| Item sells out early | ... | ... |
| Item has weak demand | ... | ... |
| Excess food remains | ... | ... |
| Ingredient shortage | ... | ... |
| Supplier price increases | ... | ... |
| Unexpected demand spike | ... | ... |
| Budget approaches limit | ... | ... |

Never recommend unsafe handling or selling of food that is no longer suitable for consumption.

---

## 8. Financial Summary

Calculate:

- Total expenditure
- Total revenue
- Total variable cost
- Expected contribution
- Remaining contingency
- Contribution margin %

Use:

**Contribution Margin % = Contribution ÷ Revenue × 100**

Clearly distinguish:

> **Revenue ≠ Profit ≠ Contribution**

If fixed costs are unknown, state that a true net-profit calculation cannot be established and use **contribution** as the primary financial metric.

---

## 9. Risk Register

Identify the 5 most important risks.

Use:

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|------------|
| ... | Low/Medium/High | Low/Medium/High | ... |

Do not invent precise probabilities when evidence is unavailable.

---

## 10. Final Operating Blueprint

End with a concise implementation plan containing exactly:

### Menu
The selected items and prices.

### Budget
Where the ₹10,000 goes.

### Daily Control
How production changes according to actual sales.

### Demand Strategy
How shortages and excess inventory are handled.

### Financial Target
Expected revenue and contribution under the base-case assumptions.

### First-Day Checklist
A short checklist of the actions the canteen manager should complete before opening on Day 1.

</required_analysis>

<quality_control>
Before producing the final answer, silently verify:

1. Does total budget allocation equal exactly ₹10,000?
2. Are all revenue calculations mathematically correct?
3. Are all cost calculations mathematically correct?
4. Are quantities operationally plausible?
5. Are assumptions clearly separated from facts?
6. Is the distinction between revenue, cost, contribution, and profit correct?
7. Does the seven-day plan adapt to changing demand?
8. Are unsold/perishable items addressed?
9. Are all required tables present?
10. Are there any unsupported factual claims presented as certain?
11. Is the plan practical for a college canteen rather than a large restaurant?
12. Has unnecessary complexity been removed?
</quality_control>

<output_style>
Write in a **professional consulting/operations-report style**.

Requirements:

- Use clear Markdown headings.
- Use tables for numerical information.
- Use concise explanations below tables.
- Use ₹ and Indian numbering where appropriate.
- Keep calculations transparent.
- Avoid motivational language, filler, and generic business jargon.
- Do not mention these instructions in the final response.
- Do not provide a vague recommendation; provide a concrete operational plan.
</output_style>

<mini_example>
Use the following only as a formatting example, NOT as factual data:

**Example calculation**

If an item costs ₹20 to produce and sells for ₹35:

- Selling Price = ₹35
- Cost = ₹20
- Contribution/Unit = ₹15
- If 100 units are sold:
  - Revenue = ₹3,500
  - Variable Cost = ₹2,000
  - Contribution = ₹1,500

Do not reuse these numbers unless independently justified by the scenario.
</mini_example>

<final_instruction>
Produce the complete **7-day ₹10,000 college canteen optimization plan** now.

Prioritize numerical consistency, realistic assumptions, operational feasibility, demand adaptation, and clear decision logic over verbosity.
</final_instruction>
