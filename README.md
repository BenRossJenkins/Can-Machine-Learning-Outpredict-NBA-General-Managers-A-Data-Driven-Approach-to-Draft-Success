# Can-Machine-Learning-Outpredict-NBA-General-Managers-A-Data-Driven-Approach-to-Draft-Success



## 1.	Introduction

This study presents an in-depth analysis of the NBA draft classes from 2009 to 2021, focusing on player performance and potential predictive factors that impact their professional success. Using data from NCAA games and NBA performance metrics, we constructed a model to evaluate how various college-level statistics, such as offensive and defensive ratings, usage rates, shooting efficiencies, and other advanced metrics, translate into NBA success. The analysis aims to provide insight into the predictive accuracy of pre-draft data and offers a framework for improving scouting and draft decision-making.

## 2.	Methods

The dataset includes a wide array of player statistics from NCAA seasons and subsequent NBA performance, covering over 60 attributes such as offensive ratings (Ortg), usage percentages (usg), shooting efficiencies (eFG%), and advanced defensive metrics. A combination of machine learning models, including neural networks and gradient-boosting methods, was used to assess how these factors correlate with NBA performance, using measures such as Win Shares (WS), Box Plus-Minus (BPM), and Value Over Replacement Player (VORP). SHAP (SHapley Additive exPlanations) values were employed to interpret the contribution of individual features toward model predictions, providing transparency and identifying the most influential predictors of NBA success. In addition to predicting a player’s mean outcome, the model also provides percentile ranges, offering a robust measure of uncertainty and allowing scouts to assess a player’s potential within a distribution of possible outcomes. The model was trained on past draft classes and validated using player outcomes to ensure robustness and minimize bias.

## 3.	Results

The results show that certain college metrics, particularly draft position, BPM, steals, and DBPM, are strong predictors of NBA success, as revealed by the SHAP values plot. The predictive accuracy of the model was robust, yielding a test RMSE of 0.5782, a test MAE of 0.4263, and an R² value of 0.5048. Additionally, the model’s ability to predict a range of percentile outcomes allows teams to assess the uncertainty surrounding a player's potential and make more informed decisions. Furthermore, the model consistently outperforms historical NBA draft rankings, as shown by higher Spearman correlation values between the predicted ranks and actual performance metrics (VORP), validating the model’s superiority in forecasting player success over traditional draft selections.

## 4.	Conclusion

This analysis provides a valuable tool for NBA teams and scouts, helping them to make more informed decisions during the draft by quantifying the predictive power of collegiate performance metrics. By incorporating SHAP values, the model offers greater interpretability, allowing scouts and analysts to understand the specific metrics contributing most to a player's projected success. Furthermore, the inclusion of percentile ranges provides a measure of uncertainty, giving a fuller picture of a player’s potential. The model’s superior performance compared to historical NBA draft rankings indicates that advanced data-driven methods can substantially improve draft efficiency by reducing uncertainty and yielding more accurate predictions of long-term player success.



