# 📊 AB-Testing-Marketing-Campaign

This repository contains an A/B Testing project designed to evaluate whether showing **advertisements (ads)** significantly increases product conversion compared to **Public Service Announcements (PSA)**.

---

## 🎯 Objective
The objective of this analysis is to determine whether the display of ads has a significant impact on product purchase conversion rates compared to PSA exposure.

---

## 🧪 Experiment Design
1. **Hypothesis**
   - **Null Hypothesis (H₀):** There is no significant difference in conversion rates between users who see ads and those who see PSA.  
   - **Alternative Hypothesis (H₁):** Users who see ads have a higher conversion rate than those who see PSA.

2. **Success Metric**
   - **Conversion Rate**: Percentage of users who made a purchase after exposure.

3. **Guardrail Metrics**
   - Average ad exposure per user  
   - Peak interaction time (most ads hour)  
   - Day with the highest ad impressions  

4. **Experiment Type**
   - **Superiority Test** (Ads must outperform PSA in terms of conversion rate).  

5. **Sample Size**
   - Per group: **19,908**  
   - Total: **39,816**  
   - Duration: ~1 week  

   Calculation based on:  
   - Confidence level: 95%  
   - Power: 80%  
   - Baseline Conversion Rate (Control): 20%  
   - Minimum Detectable Effect (MDE): 5% (20% → 25%)  
   - One-sided test  

---

## 🔍 Methodology
- Random assignment of eligible users into control (**PSA**) and variant (**Ads**) groups.  
- Statistical test conducted to evaluate conversion rate differences.  
- One-sided hypothesis test to check if Ads > PSA.  

---

## 📈 Business Impact
- **If Ads are effective** → allocate more marketing budget to Ads campaigns.  
- **If not effective** → avoid unnecessary ad spending and explore alternative strategies to boost conversions.  

---

## 🛠 Tech Stack
- **Python** (Pandas, SciPy, Statsmodels)  
- **Jupyter Notebook / Google Colab**  


## ✨ Tagline
*"Data-driven experiment to reveal the true impact of ads on conversions."*
