# Target_Pregnancy_Prediction_Model_08 CaseCraft Analytics Project 8

## 🧬 Overview  
This project explores predictive modeling of early-stage pregnancy using synthetic purchase behavior data from Target’s loyalty program. It blends behavioral analytics, feature engineering, and ethical reflection.

## 🎯 Objective  
To identify subtle purchase signals linked to early pregnancy and build a classification model that predicts pregnancy likelihood.

## 🛒 Dataset & Features  
- Customers: 500 synthetic profiles  
- Timeframe: Jan–Aug 2023 (weekly data)  
- Categories: Lotion, Vitamins, Unscented Soap, Cotton, Pregnancy Test, Baby Wipes, Snacks, Books  
- Features: purchase frequency, recency, category mix  
- Target: `pregnant` (binary flag)

## 📊 Visual Explorations  
- Line chart: Weekly purchase trends by category  
- Bar chart: Purchase distribution by pregnancy status  
- Correlation matrix: Feature importance  
- Behavioral spike window: March–May 2023

## 🔍 Behavioral Signals  
- Pregnant customers show increased purchases of Lotion, Vitamins, Unscented Soap, and Pregnancy Tests  
- Spikes occur 4–8 weeks before pregnancy confirmation  
- Non-pregnancy categories remain stable

## 🤖 Classification Model  
- Model: Random Forest  
- Features: category-level purchase totals  
- Performance:  
  - Precision: 0.99–1.00  
  - Recall: 0.96–1.00  
  - F1-score: 0.98–1.00  
  - Accuracy: 99%

## 🧠 Key Insights  
1. **Signal Categories**: Lotion, Vitamins, Unscented Soap, Pregnancy Tests are strong indicators  
2. **Temporal Window**: March–May shows predictive spikes  
3. **Model Utility**: High precision and recall on synthetic data  
4. **Feature Importance**: Lotion and Vitamins top the correlation chart  
5. **Ethical Considerations**: Privacy, consent, and responsible targeting are critical

## ✅ Final Conclusion  
Predictive modeling of pregnancy behavior is feasible using purchase patterns. Target can leverage these insights for personalized recommendations and inventory planning—but must prioritize ethical safeguards to avoid misuse or privacy violations.