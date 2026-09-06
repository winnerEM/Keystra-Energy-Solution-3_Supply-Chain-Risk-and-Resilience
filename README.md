Keystra Energy Group
Solution 3: Supply Chain Risk & Operational Resilience Early-Warning System

Overview:
A portfolio proof-of-concept developed for Keystra Energy Group, a fictional integrated energy company.
The project uses risk analytics and machine learning to identify emerging supplier risk, predict potential supplier failure, explain risk drivers, trace downstream exposure, and prioritise intervention.

Core risk chain:
Supplier → Material → Asset → Business Unit → Exposure → Intervention


Business Challenge:
Supplier disruption can extend beyond procurement to affect critical materials, operational assets, inventory availability, and business continuity.
The system addresses four key questions:
* Which suppliers are becoming unreliable?
* Why are they at risk?
* What could their failure affect?
* How urgently should Keystra respond?


Data Foundation:
Synthetic data was engineered specifically for Keystra Energy Group to simulate realistic supply-chain relationships.
* 90 Suppliers
* 60 Materials
* 13 Assets
* 5 Business Units
* 40,000 Purchase-Order Lines
* Analysis period: Jan 2022 – Jul 2026


Analytical Approach
The project covers:
1. Risk Signal Identification — procurement, delivery, fulfilment, quality and inventory signals.
2. Predictive Supplier Risk — prediction of supplier failure within a 90-day horizon.
3. Explainable Early Warnings — identification of key drivers behind supplier risk.
4. Risk Propagation — tracing supplier exposure through materials and operational assets.
5. Intervention Prioritisation — combining likelihood, consequence and exposure.
6. Final Supplier Risk Register — converting 90 suppliers into clear management priorities.


Model Performance
Final model performance on unseen test data:
Metric	       Result
Precision	      95.27%
Recall	        87.05%
F1 Score	      90.97%
PR-AUC	        0.9721
ROC-AUC        	0.9893


Key Findings:
* $4.05B in outstanding procurement exposure identified.
* Only 11 suppliers (12.22%) were classified as Critical/High Early Warning, but they represented 42.01% ($1.70B) of total exposure.
* Downstream Propagation emerged as the dominant population-level risk driver.
* The highest-risk supplier combined 92% predicted failure probability with $1.258B exposure.
* Supplier failure probability alone was insufficient; business consequence and dependency criticality materially changed risk priority.


Tools:
Python · MS Word· Google Colab


Limitations:
This is a proof-of-concept using synthetic data. Real-world deployment would require validated operational data, additional external risk variables, continuous data-quality monitoring, and ongoing model recalibration.

Outcome:
The project demonstrates an end-to-end approach to supply-chain risk analytics;
Risk Signals → Prediction → Explanation → Exposure → Propagation → Prioritisation → Early Warning
The result is a structured framework for identifying developing supplier risk early and translating it into actionable management priorities.


Below is the link to the engineered dataset:
https://drive.google.com/drive/folders/1GRId3FFoEGBG7ZAgyCqDn3hU41vAMEz7?usp=sharing
