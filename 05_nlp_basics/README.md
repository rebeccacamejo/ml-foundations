# 05 ‑ NLP Basics

This section introduces natural language processing (NLP) workflows using two fundamental text representation techniques: **Bag‑of‑Words (BoW)** and **TF‑IDF**.  I constructed a small sample dataset of positive and negative reviews to demonstrate sentiment classification.

The first notebook uses a simple BoW representation with logistic regression, while the second employs TF‑IDF weighting and a linear support vector machine.  These models illustrate how text can be transformed into numerical features and fed into classic machine‑learning algorithms.  Understanding these basics lays the groundwork for more advanced architectures like transformers  (checkout my repo llms-from-scratch-exercises).

## Industry applications

- **FinTech:** BoW/TF‑IDF models can classify **support ticket topics** (e.g., dispute, loan inquiry, account update) to route messages to the correct team.  
- **SaaS:** Use simple NLP to perform **sentiment analysis** on product reviews or NPS feedback; track trending issues to inform product roadmap.  
- **Logistics:** Parse **delivery instructions**, categorize special handling notes, or detect address anomalies, improving last‑mile success.  
- **Construction/field services:** Classify **work orders** and **job descriptions** to decide whether a plumber, electrician, or general contractor should be dispatched.

## Future case study ideas

- **FinTech:** Implement a BoW classifier to detect **regulatory keywords** or **privacy concerns** in customer chats; automatically elevate compliance issues.  
- **SaaS:** Enhance ticket triage by using TF‑IDF to distinguish **bug reports** from **feature requests**; reduce triage turnaround.  
- **Logistics:** Build a quick sentiment classifier for **driver feedback** or **delivery satisfaction surveys**; drive operational improvements.  
- **Construction/field services:** Use a simple NLP model to detect **urgent hazards** in job logs (e.g., “water leak,” “no power”) to prioritize emergency visits.

