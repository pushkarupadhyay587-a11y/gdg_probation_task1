# Data Overview :
(this dataset is based on the data of the accidents happening in the india on daily basis)

the given dataset contains :
- 202000 rows
- 48 columns

* out of which :
- 16 columns were numeric
- 32 columns were non_nummeric

# Column-wise Analysis :

# 1. Date / Accident Date
- Trend: Peaks during festivals and seasonal travel.
- Pattern: Accident frequency rises during high-mobility periods.

# 2. State
- Distribution: High-traffic states dominate accident counts.
- Most affected: Uttar Pradesh
- Pattern: Dense road networks and large population increase exposure.

# 3. City / District
- Distribution: Urban districts record more accidents.
- Most affected: Dense urban and highway-connected districts
- Pattern: Congestion and mixed traffic intensify crash risk.

# 4. Time of Day
- Distribution: Evening and night record the highest accidents.
- Peak time: 5–6 PM
- Pattern: Traffic congestion, reduced visibility, and fatigue increase risk.

# 5. Weather Condition
- Distribution: Rain and fog worsen accident risk.
- Conditions: ['Clear', 'Rainy', 'Hazy', 'Foggy', 'Stormy']
- Pattern: Poor visibility and wet roads increase crash probability.

# 6. Road Type
- Distribution: Highways face severe collision patterns.
- Road types: ['State Highway', 'Other District Road', 'National Highway', 'Village Road', 'Expressway']
- Pattern: National and state highways report the highest severe crashes.

# 7. Severity
- Distribution: Minor accidents are most common.
- Pattern: Severe and fatal crashes are fewer but more damaging.
# 8. Vehicle Type
- Distribution: Two-wheelers and cars dominate.
- Pattern: Two-wheelers are more vulnerable; cars and buses contribute heavily.
# 9. Driver Age
- Median: 30–35 years
- Max: 60–65 years
- Pattern: Most drivers are young adults (20–40).
- Insight: Working-age drivers have higher exposure and road usage.
# 10. Number of Vehicles Involved
- Pattern: One or two vehicles are most common.
- Insight: Small-vehicle crashes dominate; multi-vehicle crashes are more severe.

# 11. Number of Casualties
- Min: 0
- Median: 1
- Max: 4
- Pattern: Most cases have low casualty counts.

# 12. Number of Injured
- Min: 0
- Median: 1
- Max: 3
- Pattern: Minor injuries are most frequent.

# 13. Speed Limit / Speed
- Median: 57.3 km/h
- Max: 101.2 km/h
- Pattern: Higher speed significantly increases severity.
- Insight: Overspeeding is a major factor in severe outcomes.

#14. Alcohol Involved
- Pattern: Alcohol-impaired driving increases accident severity.
- Insight: Reaction time and judgment worsen under influence.

## 15. Cause of Accident
- Distribution: Speeding and negligence lead most crashes.
- Pattern: Major causes include overspeeding, wrong-side driving, poor roads, and weather.

## 16. Road Condition
- Pattern: Poor roads increase crashes.
- Insight: Potholes, narrow lanes, and weak drainage worsen safety.

## 17. Lighting Condition.
- Insight: Night-time crashes are linked with reduced visibility and fatigue.

## 18. Gender
- Distribution: Male drivers dominate accident records due to more exposure to vehicles .


## 19. Accident Count
- Pattern: Few hotspots account for many incidents.
- Insight: A small number of districts and corridors contribute a large share of crashes.

## 20. Secondary Cause
- Pattern: Most accidents were influenced by overspeeding, wrong-side driving, and poor road conditions.


## 21. Estimated Speed (km/h)
- Min: 27.5
- Median: 57.3
- Max: 101.2
- Pattern: Most crashes occur at moderate to high speed.

## 22. Response Time (minutes)
- Min: 5.9
- Median: 12.5
- Max: 35–40
- Pattern: Response time varies significantly across cases.
- Insight: Faster emergency response can reduce fatality risk.

# 23. Insurance Claim Amount
- Min: 0
- Median: 29462
- Max: 60000
- Pattern: Most claims are moderate, while a few large claims dominate the upper range.

# 24. Number of Injuries
- Min: 0
- Median: 1
- Max: 3
- Pattern: Most accidents involve minor injuries.

# 25. Driving Experience (years)
- Min: 0
- Median: 16
- Max: 16
- Pattern: Moderate experience is common, but inexperience remains a risk factor.

## Bivariate Analysis :

# 1. Alcohol vs Severity
- Alcohol-related crashes show a higher share of severe and fatal outcomes.
- Non-alcohol crashes are mostly minor and moderate.
- Insight: Alcohol strongly increases crash severity.

# 2. Speed vs Severity
- Higher estimated speed is associated with higher accident severity.
- Severe and fatal crashes occur at much higher speeds.
- Insight: Overspeeding is a major severity driver.

# 3. State vs Fatalities
- Fatalities are concentrated in a few states.
- Uttar Pradesh has the highest total fatalities.
- Insight: Risk is uneven across regions.

# 4. Year vs Accidents
- Accident counts remain high across years with a gradual decline in recent years.
- Insight: Safety has improved slightly, but risk remains significant.

# 5. Hour vs Accidents
- Accident frequency peaks around 5–6 PM.
- Evening rush hours are the most accident-prone.
- Insight: Congestion and reduced visibility increase risk.

# 6. Road Condition vs Severity
- Poor road conditions are linked to more severe crashes.
- Wet, loose, and under-construction roads increase serious outcomes.
- Insight: Road quality directly affects crash severity.

## Multivariate Analysis Insights
- `speed_limit_kmph` and `estimated_speed_kmph` is 0.77, showing that high-speed conditions are linked to more serious accidents.
- `num_injuries` and `num_fatalities` have a correlation of 0.22, indicating that more severe crashes tend to produce more casualties.
- Driver age and driving experience are highly correlated (0.97)

## Key Insights
- Alcohol involvement and overspeeding strongly raise accident severity.
- Evening hours and poor road conditions increase crash risk.
- Fatalities are concentrated in a few high-risk states.




