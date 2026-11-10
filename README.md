# Keenan Palwono <br> <small>[Data Science Student](#), [ML Engineering Enthusiast](#)</small>

I am passionate about solving complex problems through data-driven approaches. I actively hone my analytical and predictive modeling skills by participating in various data science competitions. Combining my technical foundation with a strong background in organizational leadership, I strive to build impactful solutions and communicate them effectively.

### 🏆 Featured Competitions & Projects

*Here are some of the data science challenges and models I have built:*

- **[1st Consolation Prize - International Data Science Challenge (IDSC) 2026](https://github.com/palwono/bintang-glaucoma-detection)**
  - **Objective:** Developed BINTANG (Biomedical Intelligence for Neural Tracking and Glaucoma), an automated AI triage engine to detect glaucomatous optic neuropathy from fundus images, aiming to prevent irreversible blindness.
  - **Approach:** Designed a 4-stage clinical preprocessing pipeline (FOV Crop, Ben Graham Normalization, Green CLAHE, Unsharp Masking) and built a Dual-Backbone Ensemble fusing EfficientNet-B4 and ConvNeXt-Base. Engineered a novel "Quality-Weighted Focal Loss" to combat extreme class imbalance and integrated Grad-CAM for clinical explainability.
  - **Result:** Achieved an Out-of-Fold (OOF) Image-Level AUC of 0.9888 and a Patient-Level AUC of 0.9950. Implemented Patient-Level Quality-Weighted Aggregation, which drastically reduced False Negatives by 93.75%, ensuring a safety-first diagnostic tool.

- **[Participant - Data Science Competition (DSC) MCF ITB 2026](https://github.com/palwono/health-insurance-claim-forecasting)**
  - **Objective:** Mitigate financial risks caused by rising healthcare utilization by forecasting health insurance claim frequency, severity, and total trends.
  - **Approach:** Designed a Two-Part Ensemble Architecture integrating Holt-Winters, YoY Calibrated, Random Forest, and Theta models to predict claim frequency and severity independently. Implemented Walk-Forward Cross Validation to prevent look-ahead bias and applied Post-Hoc Bias Correction using probing data.
  - **Result:** Achieved an outstanding Mean Absolute Percentage Error (MAPE) of 5.66% on the Test A hold-out evaluation, outperforming all baseline models. Successfully projected peak claim activity for November 2025, forecasting 274 claims with a total severity of Rp12.75 billion.

- **[Participant - GAMMAFEST 2026 by IPB University](https://github.com/palwono/international-football-score-prediction)**
  - **Objective:** Forecast international football match scores (1872–2026) by analyzing historical match results, Elo ratings, FIFA rankings, and socio-economic/geographical factors.
  - **Approach:** Engineered 68+ robust features using time-decayed target encoding and developed a diverse machine learning ensemble (LightGBM, XGBoost, CatBoost) optimized for Poisson and MAE objectives. Applied Isotonic Calibration and Dixon-Coles Correction via Maximum Likelihood Estimation (MLE) to accurately adjust low-scoring match probabilities.
  - **Result:** Successfully deployed a Joint Match-Level Optimization pipeline, achieving a highly competitive Augmented Weighted Mean Absolute Error (AW-MAE) score of 3.0941 against the evaluation ground truth.

- **[Advanced Level Capstone: Smart Road Crack Inspection - Nalara Academy](https://github.com/palwono/smart-road-crack-inspection)**
  - **Objective:** Developed an end-to-end Computer Vision system to automate road condition monitoring as the final graduation project for the Nalara Academy National AI & Deep Learning Acceleration Bootcamp.
  - **Approach:** Deployed a Mobile-UNet hybrid architecture (MobileNetV2 encoder + custom U-Net decoder) via TensorFlow/Keras for lightweight pixel-level semantic segmentation. Extracted structural characteristics to formulate an automated 0-100 Severity Score and built a Streamlit web application.
  - **Result:** Successfully delivered an interactive diagnostic UI with a live analytics dashboard, demonstrating production-ready deployment skills and securing graduation from the rigorous 96-hour advanced program.

- **[Participant - National Statistics Challenge (NSC) 2026 Universitas Brawijaya](https://github.com/palwono/smart-farm-humidity-forecasting)**
  - **Objective:** Forecast the relative humidity (%RH) of a smart farm environment for a 15-day horizon to optimize irrigation scheduling and mitigate biological risks, utilizing 62 days of high-frequency historical sensor data.
  - **Approach:** Designed a robust preprocessing pipeline to handle extreme physical anomalies (e.g., negative water volumes) and temporal gaps using 30-minute interval resampling and linear interpolation. Engineered a Stacking Generalization architecture, combining XGBoost, LightGBM, and CatBoost with a non-negative Ridge Regression meta-model, validated through a rigorous 5-fold Time-Series Split.
  - **Result:** The 4-model stacking ensemble successfully improved the local Out-of-Fold (OOF) RMSE to 7.2942. Achieved a Public Leaderboard RMSE score of 3.93174, though the Private Leaderboard evaluation highlighted the natural volatility of microclimate forecasting across different validation folds.

- **[Participant - FIK FAIR 2026 Data Science Competition](https://github.com/palwono/cost-of-living-prediction)**
  - **Objective:** Predict the Anonymous Competition Score (ACS), an indicator of relative cost of living, utilizing a highly constrained and fully anonymized dataset of 382 train observations and 24 features.
  - **Approach:** Mitigated the extreme risk of variance explosion on small data by deploying **TabPFN v2**, a state-of-the-art tabular foundation model. Architected a **Dual-Representation Multi-Seed Ensemble (`T3_TA12_50`)**, fusing three stochastic raw-feature models to reduce in-context variance, alongside a PCA-augmented model leveraging 12 orthogonal components to retain 99.2% variance. The pipeline was systematically developed via local VS Code environments before final batch inference.
  - **Result:** Achieved a Public Leaderboard RMSE of 8.03913 and a stable Private Leaderboard RMSE of 8.15130. Maintained absolute zero target leakage and avoided artificial post-processing like threshold clipping, demonstrating a principled, production-ready approach to micro-dataset modeling.

### 🛠️ Core Toolkit

- **Languages:** Python, SQL
- **Libraries:** PyTorch, TensorFlow/Keras, Scikit-Learn, TabPFN, LightGBM, XGBoost, CatBoost, Pandas, OpenCV, Streamlit
- **Specialization:** Machine Learning, Predictive Modeling, Deep Learning, Computer Vision, Time Series Forecasting
- **Soft Skills:** Organizational Leadership, Strategic Communications, Public Speaking

---

### 🤳 Connect with me:

<a href="https://linkedin.com/in/keenanpalwono" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linkedin/linkedin-original.svg" alt="LinkedIn" width="30"/></a>&nbsp;&nbsp;&nbsp;<a href="https://instagram.com/keenangadi_" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" width="30"/></a>
<br>

LinkedIn: Keenan Palwono  
Instagram: @keenangadi_
