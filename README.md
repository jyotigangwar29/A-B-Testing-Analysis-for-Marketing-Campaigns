# **A/B Testing Analysis for Marketing Campaigns**

## **Executive Summary**
This project presents a comprehensive analysis of two marketing campaigns—Control Campaign and Test Campaign—to evaluate their performance in driving user engagement and conversions. By analyzing key metrics such as Click-Through Rate (CTR) and Conversion Rate (CR), this project identifies the strengths of the Test Campaign while highlighting opportunities for improvement in conversion strategies.

Through the application of statistical techniques, the analysis provides actionable insights to optimize future campaigns, improve business outcomes, and ensure data-driven decision-making.

---

## **Objective**
The primary goal of this project is to:
- Compare the **Control Campaign** and **Test Campaign** using key performance indicators:
  - **CTR**: The proportion of ad clicks to total impressions.
  - **CR**: The proportion of conversions to total clicks.
- Assess statistical significance in performance differences.
- Provide actionable insights for enhancing campaign effectiveness.

This project is critical for marketing teams to optimize resource allocation, improve ROI, and refine customer engagement strategies.

---

## **Business Context**
An e-commerce company launched two variations of a digital marketing campaign:
1. **Control Campaign**: Featured a static ad design with a generic call-to-action.
2. **Test Campaign**: Included a dynamic ad design with personalized messaging.

The company’s objective was to determine whether the Test Campaign delivers superior engagement (CTR) and conversion (CR) outcomes, thereby justifying the adoption of similar strategies for future campaigns.

---

## **Methodology**

### **Data Collection**
- The dataset for this project was sourced from Kaggle: [A/B Testing Dataset](https://www.kaggle.com/datasets/amirmotefaker/ab-testing-dataset).
- Two groups (Control and Test) were established, each comprising 30 participants.
- Data points included:
  - **Impressions:** Total number of times the ad was displayed.
  - **Clicks:** Number of users who clicked the ad.
  - **Conversions:** Number of users who completed a purchase after clicking.

### Metrics Definition
The analysis focuses on the following metrics:

1. **Click-Through Rate (CTR):**  
   CTR = (Clicks / Impressions)

2. **Conversion Rate (CR):**  
   CR = (Conversions / Clicks)

### **Statistical Testing**
To ensure robust conclusions:
- **Confidence Intervals:** Used to estimate CTR and CR ranges for each campaign.
- **Mann-Whitney U Test:** Selected due to the non-normal distribution of the data and the small sample size (n=30 per group).

---

## **Results**

### **Key Observations**
1. **CTR Performance:**
   - **Test Campaign significantly outperforms the Control Campaign** in CTR.
   - Non-overlapping confidence intervals confirm statistical significance:
     - Control Campaign CTR: 0.0434 to 0.0584.
     - Test Campaign CTR: 0.0771 to 0.1277.

2. **CR Performance:**
   - Confidence intervals for CR **overlap** between the two campaigns, indicating no statistically significant difference:
     - Control Campaign CR: 0.0891 to 0.1393.
     - Test Campaign CR: 0.0757 to 0.1089.

3. **Sample Size Limitation:**
   - With 30 participants per group, the analysis lacks sufficient power to detect medium effect sizes for CR.

---

## **Insights**

1. **Engagement Success:** 
   - The Test Campaign demonstrates superior user engagement, evidenced by significantly higher CTR.
   - Personalized ad designs and targeted messaging are effective in capturing attention.

2. **Conversion Bottleneck:** 
   - Despite higher engagement, the Test Campaign does not lead to more conversions than the Control Campaign.
   - This highlights potential issues in the post-click conversion process (e.g., landing page experience, checkout process).

3. **Need for Larger Samples:**
   - A larger sample size is required to draw definitive conclusions regarding CR performance.

---

## **Conclusion**
This project highlights the power of A/B testing in driving informed marketing decisions. The Test Campaign demonstrates its ability to boost user engagement significantly. However, conversion outcomes remain a challenge, necessitating a deeper focus on the conversion funnel and audience segmentation.

By adopting insights from this project, businesses can optimize their marketing campaigns, improve ROI, and foster data-driven decision-making across teams.
