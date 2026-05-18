# 🛒 E-Commerce : Exploratory Data Analysis

 E-Commerce Customer Churn AnalysisAn end-to-end Exploratory Data Analysis (EDA) of e-commerce customer churn using Python to identify key retention factors, 
decode operational bottlenecks, and establish evidence-based customer lifetime value (CLV) growth strategies.

📌 Project Overview
The main objective of this project is to analyze customer behavior profiles, evaluate the primary drivers of account abandonment, and build operational hypotheses for customer retention. 
Based on a dataset of 6,000 customer records, the findings reveal that customer churn is a highly predictable cycle. It is heavily accelerated by customer support friction and can be effectively countered by proactive customer engagement and premium loyalty tier ecosystems.📂 Repository StructurePlaintext├── E-commerce.ipynb           

🧠 Hypotheses Verification

1. Recency vs. Frequency Dynamic
Hypothesis: An increase in days since last purchase combined with low total order volume spikes churn risk (Supported by De Alwis et al.).
Status: Proven ✅

2. The Support Friction Trap
Hypothesis: Accumulation of customer support tickets is a direct reflection of operational friction that actively alienates users (Supported by Luth Research).

Status: Proven ✅ — Bivariate analysis reveals that every customer support ticket filed inflicts a direct, automatic -1 point penalty on customer satisfaction scores, initiating the abandonment cycle.

3. The Loyalty Shield
Hypothesis: Premium loyalty program tiers provide structural armor against abandonment, stabilizing churn near zero (Supported by Hamsalekha & Divya, 2023).

Status: Proven ✅ — Grouped counts plots demonstrate a massive, drastic reduction in relative churn numbers for loyalty program members compared to non-members.

📈 Executive Summary Visualizations:

💡 Why I chose this graph: I chose the Customer Support Tickets vs. Customer Satisfaction Score plot because it serves as the definitive "smoking gun" of my analysis. It visually proves my core discovery—that operational friction directly drives down customer satisfaction—making the insights immediately actionable for business strategy. It is also a clean, high-impact visual that any visitor or recruiter can easily understand in under 3 seconds.

Customer Support Tickets vs. Customer Satisfaction Score
<img width="830" height="457" alt="Screenshot 2026-05-18 094134" src="https://github.com/user-attachments/assets/c4058537-d112-4da2-95f0-a42edd8f29e0" />

🎯 Conclusion & Strategic Recommendations

Analysis of the 6,000 customer records reveals that customer churn is not random, but a predictable cycle driven by operational friction and declining brand engagement. Based on the insights uncovered throughout this EDA, the following strategic actions are recommended to optimize customer retention:

💥 Fix the Support Leak: Since every support ticket inflicts a strict -1 point penalty on customer satisfaction, customer service bottlenecks act as the primary trigger for account abandonment. Investing in rapid, first-contact resolution workflows and fixing recurring app/website bugs will directly safeguard customer satisfaction scores.

🛡️ Scale the Loyalty Program: Premium loyalty membership serves as an ultimate shield against churn, maintaining customer attrition rates near 0%. Marketing efforts should focus heavily on onboarding high-risk non-members into the loyalty tier through targeted entry incentives.

⏳ Implement Recency Triggers: Because increasing days since last purchase acts as an early warning sign of upcoming churn, automated win-back email campaigns or personalized discount triggers should be deployed the moment a customer exceeds their typical purchasing window.

🛠️ Technologies Used

Data Manipulation: pandas 🐼

Data Visualization: matplotlib 📊 & seaborn 🌊

Environment: Jupyter Notebook 📓
