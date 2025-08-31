# 02 ‑ Classification Basics

Classification problems involve predicting a discrete label rather than a continuous value.  In this section we explore two popular techniques: **logistic regression** and **decision trees**.  Both are applied to well‑known datasets to illustrate how to train a model, evaluate its performance and understand its decision boundaries.

* Logistic regression is a linear model for binary or multinomial outcomes.  It's simple, fast and offers interpretable parameters.
* Decision trees partition the feature space into axis‑aligned regions, making them highly interpretable but prone to overfitting without proper regularisation.

Beyond textbook exercises, classification models underpin countless real‑world applications such as spam detection, medical diagnosis and customer churn prediction.  By the end of this section you'll see how to turn raw data into actionable insights.

## Industry applications

* **FinTech:** Use logistic regression to classify **fraudulent vs. legitimate transactions** or **approve vs. decline** credit applications. When paired with clear decision rules, this lowers false positives and improves customer experience.  
* **Logistics:** Classify **shipments** as high‑priority vs. standard based on package type, destination, and promised SLA, automating which shipments get expedited handling.  
* **Construction/field services:** Classify incoming **service requests** (e.g., plumbing vs. electrical vs. roofing) to route to specialists and decide dispatch urgency.

## Future case study ideas

* **FinTech:** Build a classification model to flag **high‑risk chargebacks** or **refund requests** requiring additional documentation. Measure how triaging improves recovery rates.  
* **SaaS:** Classify support tickets into **feature request**, **bug report**, or **how‑to question** to streamline internal workflows and cut backlog time.  
* **Logistics:** Automatically classify **perishable shipments** vs. non‑perishable to determine cold‑chain handling, reducing spoilage.  
* **Construction/field services:** Classify **job quotes** as urgent vs. schedulable; measure improved on‑time completion and customer satisfaction.

