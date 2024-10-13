# WNBA MVP Prediction Model Using LGBM

## Overview
This project focuses on predicting the WNBA MVP winner using the LGBM (LightGBM) model. The model achieved remarkable accuracy, correctly predicting 15 out of the last 19 MVP winners, including a perfect streak from 2013 to 2024. This analysis dives into the model's strengths, its occasional missteps, and key insights that can help refine future predictions.

## Key Findings

1. **Model Accuracy:**
   - The LGBM model successfully predicted 15 of the last 19 WNBA MVP winners.
   - From 2013 to 2024, the model had a perfect accuracy rate.

2. **Unexpected Misses:**
   - The model struggled between 2008 and 2012, incorrectly predicting 4 out of 5 times. 
   - In 2008, Candace Parker won the MVP award with 25% of the votes coming from fans, likely skewing predictions.

3. **Analysis of MVP Criteria:**
   - The model showed that **PER (Player Efficiency Rating)** is one of the most influential variables in both the WNBA and NBA MVP predictions.
   - In the WNBA, the higher a player's **Defensive Rating**, the less likely they were to win MVP, suggesting that high scorers receive more MVP votes than defensive specialists.

4. **Challenges for Guards:**
   - Guards have faced significant challenges in winning MVP in the WNBA, with only one guard (Diana Taurasi) winning in the past 16 seasons.
   - By contrast, the NBA has seen more frequent MVP wins by guards.

5. **Key Variables:**
   - The models highlighted the importance of stats like **team seed**, **win percentage**, **WS/40** (Win Shares per 40 minutes), and **FGM (Field Goals Made) per game** for determining MVP candidates.
   - The model demonstrated that assists have less impact on MVP voting compared to other stats like rebounds and points.

## Conclusion
This analysis highlights both the strengths and limitations of the model in predicting MVP winners. While the model performed well overall, especially from 2013 onwards, future work could focus on improving accuracy for earlier seasons and better accounting for external factors like fan votes.

## Future Work
- Incorporate more external variables such as fan voting or media narratives.
- Explore other machine learning models to see if performance can be improved in earlier seasons.

## Inspiration
- This project was inspired by an NBA MVP prediction model initially developed by Gabriel Pastorello here: https://towardsdatascience.com/predicting-the-nba-mvp-with-machine-learning-c3e5b755f42e. His work on using machine learning to predict NBA MVP winners was pivotal in shaping the approach and methodology used in this WNBA MVP model.


