# Decode-lab-Internship
# DecodeLabs Internship Portfolio - Artificial Intelligence Track

Welcome to my repository for the 4-week Artificial Intelligence Industrial Training program at DecodeLabs (Batch 2026). This space serves as a weekly milestone tracking portfolio showcasing supervised learning pipelines and control layer architectures.

| Repository Structure
The project files are organized chronologically by milestone tasks:
* `Week 1/` - Rule-Based AI Guardrail Engine (`chatbot.py`)
* `Week 2/` - Supervised Machine Learning Data Classification (`classification_model.py`)
* `Week 3/` - Algorithmic Pattern Alignment & Content Personalization (`recommendation_engine.py`)

| Weekly Milestone Breakdown

| Week 1: Rule-Based AI Chatbot (Deterministic Guardrails)
* Goal: Build a robust input control layer simulation acting as a rigid logic filter to prevent hallucinations.
* Core Concepts: Input sanitization, continuous feedback loops, and atomic lookups using Python dictionaries to achieve constant $O(1)$ lookup time.
* How to Run: `python "Week 1/chatbot.py"`

| Week 2: Supervised Data Classification (Iris Benchmark Classifier)
* Goal: Move past hardcoded rules into true predictive analytics by teaching a machine to derive its own decision boundary logic from historical inputs.
* Core Concepts: Feature scaling via standardization (Mean=0, Variance=1), randomized train-test splits (80/20) to eliminate order bias, and model training using the K-Nearest Neighbors (KNN) algorithm. Evaluated via confusion matrix metrics and weighted F1-Scores.
* How to Run: `python "Week 2/classification_model.py"`

| Week 3: Personalization Engine (AI Recommendation Logic)
* Goal: Build an algorithmic recommendation matrix that aligns user interest tags to item attributes within a consistent vocabulary vector space.
* Core Concepts: Text normalization processing, profile vector mapping, and vector alignment math concepts to calculate similarity scores and rank top items cleanly.
* How to Run: `python "Week 3/recommendation_engine.py"`

| Environment Setup & Requirements
To run these scripts locally on your desktop machine, make sure you have Python installed alongside the following required libraries:

```bash
pip install numpy scikit-learn
