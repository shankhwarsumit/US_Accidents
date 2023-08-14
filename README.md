<img width="300" alt="image" src="https://github.com/shankhwarsumit/US_Accidents/assets/88932858/ab9a5030-56c2-419f-9eb4-c66ce9be0109">
<img width="300" alt="image" src="https://github.com/shankhwarsumit/US_Accidents/assets/88932858/dfa6848d-0ebe-4f81-8418-1f0bf85421c9">

# US Accidents Exploratory Data Analysis (2016-2023)

Explore and analyze a comprehensive dataset of car accidents across the USA from 2016 to 2023, utilizing Seaborn, Matplotlib, Pandas, NumPy, and Folium for data visualization and insights.

## Description

This project delves into a countrywide car accident dataset, covering 49 states of the USA. The dataset, comprising approximately 7.7 million accident records, was collected between February 2016 and March 2023, sourced through multiple APIs capturing real-time traffic incident data from various entities including government departments, law enforcement agencies, and traffic sensors. The analysis provides valuable insights into accident patterns, severity, and the interplay with weather conditions.

## Content

The dataset offers real-time accident data for the Contiguous United States from February 2016 to March 2023. For more details, visit [here](https://www.kaggle.com/sobhanmoosavi/us-accidents).

## Inspiration

This dataset holds potential for various applications, including real-time accident prediction, hotspot identification, casualty analysis, cause-effect rule extraction, and studying the impact of weather on accident occurrence. It also facilitates the study of COVID-19's influence on traffic behavior and accidents.

## Summary and Conclusion

### Data Insights

1. **Missing Data**: The dataset lacks information from New York, which may impact a complete nationwide analysis.

2. **City-wise Analysis**: The number of accidents per city follows an exponential decrease, highlighting areas with higher accident concentration.

3. **City Severity**: Less than 5% of cities experience over 1000 yearly accidents, signifying significant variation in accident distribution.

4. **Single Accident Cities**: Over 1600 cities reported just one accident, warranting further investigation into the underlying causes.

5. **Temporal Patterns**: Accidents peak between 6am-10am, possibly due to morning rush hours, and the pattern continues between 3pm-7pm.

6. **Weekend Peaks**: On weekends, accidents peak from 10am-4pm, unlike weekdays, possibly indicating different traffic behaviors.

7. **Temporal Data Gap**: Data inconsistencies are observed in 2016, requiring careful consideration while analyzing that period.

8. **Source Data Issue**: An issue with source 3 data suggests potential data quality concerns.

9. **Wind Direction Variability**: Variability in wind direction naming, such as "Calm" and "CALM," poses challenges for data interpretation.

### Weather and Severity

10. **Fog Severity**: An insightful finding is that 76% of accidents under foggy conditions are categorized as severity level 2, prompting further investigation into this relationship.

11. **Severity Distribution**: The severity distribution reveals that 65% of accidents are severity level 2, while only 2% fall under severity 1 and 4.

12. **Low Visibility Impact**: Accidents predominantly occur at low visibility levels.

13. **Rain Impact**: Under rain-related accidents, 71% occur due to light rain, while heavy rain contributes to only 6% of accidents.

### Utilization and Implications

The comprehensive analysis of the US Accidents dataset demonstrates its potential for various applications, including real-time accident prediction, hotspot identification, and the study of weather impacts on accident occurrence. The dataset's availability for a prolonged period (2016-2023) enables insights into the evolving impact of external factors, such as COVID-19, on traffic behavior and accidents.

## Conclusion

The exploratory analysis sheds light on accident patterns, severity, and weather associations across the USA. The insights garnered from this project can inform predictive modeling, aid in identifying accident-prone areas, and contribute to studies addressing the dynamic nature of traffic behavior and external influences.
