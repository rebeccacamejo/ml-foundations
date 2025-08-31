# 03 ‑ Neural Networks

This section introduces neural networks at two different levels.  First we build
a **Multi‑Layer Perceptron (MLP)** to classify handwritten digits from the
classic digits dataset.  Then we explore the fundamentals of **convolution**,
the key operation that powers convolutional neural networks (CNNs).  While we
don't train a full CNN here (due to resource constraints), we demonstrate how
convolution filters extract features such as edges from raw image data.

Neural networks are ubiquitous in modern applications – from character
recognition and speech processing to fraud detection and recommendation
systems.  The exercises in this folder highlight how neural architectures
generalise linear models, learn complex patterns and underpin state‑of‑the‑art
performance.

## Industry applications

- **FinTech:** Deep neural networks can model **non‑linear credit risk** by ingesting hundreds of borrower features; or detect **check fraud** via signature/character recognition from scanned images.  
- **Logistics:** Apply a 1D CNN to time‑series sensor data from trucks to detect **engine anomalies** or **predictive maintenance** needs, reducing unplanned downtime.  
- **Construction/field services:** Employ a CNN to analyze photos from job sites for **safety compliance** (e.g., PPE detection) or **quality control** (e.g., cracks in concrete).

## Future case study ideas

- **FinTech:** Create a neural network that scores handwritten checks or invoices for **authenticity** and **amount accuracy**, speeding up back‑office processing.  
- **SaaS:** Build a voice‑to‑text MLP to **transcribe support calls** automatically, then feed transcripts into sentiment or topic models.  
- **Logistics:** Develop a CNN to classify **damaged parcels** from warehouse photos, guiding which packages need repackaging or claims processing.  
- **Construction/field services:** Train a multi‑modal network that combines **sensor readings** and **image data** from equipment to predict failure with high confidence, cutting repeat service calls.

