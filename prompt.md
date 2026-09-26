# Prompt Submission: College Canteen Operations & Strategy Planner

## Prompt Metadata
- **Domain:** Business Operations & Financial Modeling
- **Task Type:** Constrained Optimization & Business Planning
- **Target Model:** Advanced LLM / Analytical Reasoning Model

---

## Prompt Text

```text
Act as a college canteen operations and business strategist. I have a hard budget cap of ₹10,000 to optimize and run a college canteen for exactly one week. Design a practical, profitable, and student-friendly operational plan.

### Baseline Parameters & Assumptions
- **Customer Base:** 500 potential college students (highly price-sensitive; prioritizing filling, quick-to-serve, affordable items).
- **Operating Schedule:** 6 days per week.
- **Budget Limit:** Total expenditure must strictly not exceed ₹10,000.
- **Cost Scope:** Raw ingredients, disposable packaging, and an emergency contingency reserve.

---

### Key Requirements

#### 1. Menu Design & Unit Economics (5–7 Items)
Select 5 to 7 food and drink items based on affordability, popularity, low prep time, and demand stability. For every item, provide:
- Selling price (₹)
- Cost per serving (₹)
- Total servings to prepare for the 6-day week
- Expected daily demand
- Expected total weekly profit (₹)

#### 2. Financial Allocation
Allocate the ₹10,000 budget across:
- Ingredient procurement
- Packaging materials
- Emergency/contingency reserve
Ensure the sum of these expenses is strictly less than or equal to ₹10,000.

#### 3. Operational Protocols
Detail clear, operational procedures for:
- **Peak Hour Surges:** Queue management and rapid throughput without bottlenecks.
- **Unsold Inventory:** End-of-day waste mitigation and safe repurposing or discounting.
- **Supply Shortages:** Rapid fallback rules if high-demand items sell out early.
- **Promotions:** Low-complexity combo deals or off-peak pricing mechanisms.

---

### Output Format Requirements
1. **Menu Economics Table:** Columns for Item Name, Cost/Serving, Selling Price, Weekly Volume, Weekly Cost, Weekly Revenue, and Net Profit.
2. **Budget Allocation Table:** Itemized breakdown proving total expenses $\le$ ₹10,000.
3. **Demand & Waste Strategy:** Concise, numbered operational steps.
4. **Financial Summary:** Total Cost, Total Projected Revenue, Total Net Profit, and Return on Investment (ROI %).
5. **Constraint Check:** Verify that all unit calculations match the total spending and do not exceed the ₹10,000 budget.