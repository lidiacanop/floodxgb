# Feature Importance with XGBoost
This repo contains the code used to study  which characteristics of the survey population are more strongly
associated with an individual participant’s exposure to a particular type of extreme weather event. We
assess nine participant characteristics, split into three categories: four commonly referenced climate
vulnerability demographics (income, age, gender, and education level), three rarely-referenced climate
vulnerability demographics (queer identity, disability identity, and non-dominant primary language),
and two self-reported perceptions of vulnerability (self-perceived vulnerability to flood risk and self-
perceived discrimination).

We employ a supervised machine learning approach whereby importance analysis is performed
through gradient-boosted decision trees to measure the importance of each of the participant char-
acteristics relative to each other, for a given climate hazard type. We performed this analysis through the XGBoost library (Chen and Guestrin 2016).
