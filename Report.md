# 📄 Survival Analysis Report

## 🔍 Interpretation of Model Results

Based on the **Log-Logistic AFT model**, several variables showed significant influence on customer churn:

- 📈 Customers subscribed to **Plus service** and **Total service** plans had **longer survival times**, suggesting greater retention.
- 📉 **Basic service** users were more likely to churn earlier in their lifecycle.
- 🧓 Demographic factors such as **age**, 💍 **marital status**, and 💵 **income** were positively associated with retention — older, married, and higher-income users tended to stay longer.
- 📡 Features like **internet service** and **call forwarding** were negatively associated with survival, implying these users may require additional engagement or proactive support.

---

## 💎 Most Valuable Segments

From a business perspective, the most valuable customer segments are those with both **high predicted CLV** and **low churn risk**.

- Notably, **Plus service** users had the **highest mean Customer Lifetime Value (CLV)**, approximately **$4385**.
- These users are strong candidates for loyalty programs or upselling, given their predicted long tenure and contribution to revenue.

---

## 💰 Suggested Retention Strategy

Assuming the dataset represents the full subscriber population:

- The company should allocate an **annual retention budget** toward **at-risk high-value customers**.
- Based on CLV predictions and 12-month survival probabilities, a reasonable investment of **$100–$200 per high-risk high-CLV customer** could be justified.
- Effective strategies may include:
  - 🎯 Targeted retention campaigns for **Basic service** customers
  - 💡 Improved digital onboarding to enhance early engagement
  - 🎁 Loyalty rewards or service bundles for users identified at higher risk of churn by the survival model

---

This approach combines model interpretability with business impact, enabling data-driven retention planning.