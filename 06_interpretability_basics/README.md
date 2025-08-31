# 06 ‑ Interpretability Basics

Predictive power is only part of the story; understanding **why** a model makes its decisions is critical for trust, compliance and actionable insights.  This section explores two ways to peek inside machine‑learning models:

1. **Feature importance** from a Random Forest classifier: we identify which variables contribute most to predicting breast cancer diagnoses.
2. **Word weights** from a text classifier: by examining logistic regression coefficients, we reveal which words carry positive or negative sentiment.

Interpretability techniques help translate technical models into business language.  They empower stakeholders to validate assumptions, identify key drivers and communicate results effectively.

## Industry applications

- **FinTech:** Feature importance helps explain **why a credit score is low** or why a transaction is flagged; transparent explanations are essential for regulatory compliance.  
- **SaaS:** Visualizing feature weights reveals **drivers of churn** (e.g., low weekly active usage); product teams can act on these insights.  
- **Logistics:** Explain which features (distance, weight, time of day) most influence a **delivery time estimator**, aiding operations in reducing delays.  
- **Construction/field services:** Show which factors (crew experience, materials, scope) drive **cost and duration predictions**, helping managers allocate resources better.

## Future case study ideas

- **FinTech:** Use interpretability to audit models for **fairness** across demographic segments; communicate which variables have disproportionate impact.  
- **SaaS:** Build an “insights dashboard” where the **top churn predictors** are updated weekly, tied to specific product features; drive targeted improvements.  
- **Logistics:** Create a report showing **feature contribution** to fuel consumption predictions; justify investments in route planning or driver training.  
- **Construction/field services:** Run partial dependence plots to show **how job cost scales** with project size or crew size; inform contract pricing strategies.
