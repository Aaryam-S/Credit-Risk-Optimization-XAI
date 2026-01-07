# Credit Risk Optimization with Explainable AI

## Business Objective
In the banking sector, the cost of a loan default (loss of principal) significantly outweighs the cost of rejecting a valid customer (loss of interest). This project builds a machine learning pipeline to minimize financial risk while ensuring regulatory transparency.

## Project Highlights
*   Model: XGBoost Classifier trained on the German Credit dataset.
*   Technique: Cost-Sensitive Learning to optimize the decision threshold.
*   Explainability: SHAP (SHapley Additive exPlanations) values to interpret model decisions.

## Key Results
By simulating a **5:1 business cost ratio** (Default Cost vs. Opportunity Cost), I implemented an automated optimization loop to find the ideal probability threshold.

*   Optimal Threshold: 0.13 (vs standard 0.50)
*   Outcome: Reduced False Negatives (Missed Defaults) to just **6 out of 200** cases in the test set.
*   Impact: Maximized theoretical profit by aggressively filtering high-risk applicants.

## Visuals
https://picstatic.com/v/L0DXkPU,HlqAO2k,FStYJlv,vAgcEa9,lVDUtF2,4PWCmYs
