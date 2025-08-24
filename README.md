# Purpose: Analysis of the effectiveness of personalization strategies in marketing. The insights from the project showed that personalization is especially effective on Instagram with younger age groups, while the strategy needs to be adjusted for older age groups or languages ​​such as German/Arabic. The project uses A/B testing and the lift function as a powerful tool for measurement and automated analysis, helping the organization optimize future marketing campaigns.
# Link to Dataset: https://www.kaggle.com/datasets/kavitabhagwani/marketing-campaign/data
# Insights:

## 1. Overall A/B Testing Effectiveness
*Overall Results:*
  - The control group had an average conversion rate of about 28.15%.
  - The personalization group had an average conversion rate of about 39.08%.
  - Lift: Personalization resulted in a 39% increase in conversion rate compared to the control group.

## 2. Segmentation analysis by Email channel
*Overview of Email channel:*
  - Lift: 39%, p-value = 0.0065 (statistically significant).
*By language displayed (language_displayed):*
  - Arabic: Lift = 50%, but p-value = 0.58 (not statistically significant), small sample (5 controls, 5 personalizations).
  - English: Lift = 39%, p-value = 0.027 (statistically significant), large sample (240 controls, 248 personalizations).
  - German: Lift = -2%, p-value = 0.85 (not statistically significant), small sample (17 controls, 27 personalizations).
  - Spanish: Lift = 167%, p-value = 0.04 (statistically significant), but very small sample (8 controls, 4 personalizations).

## 3. Instagram Channel Segmentation Analysis
*Instagram Channel Overview:*
  - Lift: 380%, p-value = 3.66e-26 (highly significant).
  - Instagram Personalization is Superior to Email.
*By Age Group (age_group):*
  - 0-18: Lift = 532%, p-value = 1.39e-05 (highly significant).
  - 19-24: Lift = 1007%, p-value = 4.71e-17 (highly significant).
  - 24-30: Lift = 542%, p-value = 2.17e-08 (highly significant).
  - 30-36: Lift = 171%, p-value = 0.083 (weakly significant).
  - 36-45: Lift = 145%, p-value = 0.065 (weak statistical significance).
  - 45-55: Lift = 21%, p-value = 0.68 (not statistically significant).
  - 55+: Lift = -39%, p-value = 0.35 (not statistically significant).

## 4. Key Points to Remember
  - Sample Size: Small sample segments (e.g. Arabic, Spanish) show high engagement but should be treated with caution due to lack of statistical significance or low reliability.
  - Instagram Outperforms: Engagement on Instagram is significantly higher than Email, suggesting this channel responds better to personalization.
  - Target Audience: Younger age groups (0-30) benefit the most from personalization, especially on Instagram.

