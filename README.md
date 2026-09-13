# Tableau-Flight-Satisfaction
# Airline Passenger Satisfaction Analysis

This repository contains a comprehensive Tableau dashboard project analyzing the key factors that influence airline passenger satisfaction. The analysis evaluates customer demographics, travel behavior, flight delays, and inflight service ratings to provide actionable business insights.

## Project Overview
The objective of this analysis is to identify patterns in passenger satisfaction and pinpoint areas for service improvement. By visualizing the data, this project highlights how different demographics perceive inflight amenities and how operational metrics like delays impact the overall customer experience.

## Key Business Insights

*   **Demographics & Travel Purpose:** There are no significant differences in travel patterns between genders, with both men and women traveling predominantly for business (approximately 70%) versus personal reasons (30%). The passenger age demographic follows a classic normal distribution (bell curve).
*   **Class Impact on Satisfaction:** Travel purpose and cabin class directly influence satisfaction. Business travelers flying in Business class are the most numerous demographic (~34,000 passengers) and report the highest satisfaction levels. Conversely, personal travelers predominantly book Eco class (~24,000 passengers) and show lower satisfaction rates. Eco Plus records the lowest booking volume across all travel types.
*   **Service Performance:** "Inflight Service" and "Baggage Handling" are the highest-rated amenities. "Inflight Wifi" is a critical pain point, receiving the lowest average score across all three cabin classes (Business, Eco, Eco Plus). When analyzed by age, "Inflight Entertainment" consistently outscores "Inflight Wifi" across all age groups, with passengers aged 40-60 providing the highest overall service ratings. 
*   **Operational Delays:** There is a strong 1:1 positive correlation between departure and arrival delays; a 200-minute delay at departure reliably generates a 200-minute delay upon arrival. While minor delays (0-100 minutes) do not significantly impact overall satisfaction, extreme delays (over 500 minutes) result in overwhelmingly dissatisfied passengers.

## Technical Implementation & Visualizations
The analysis was conducted using Tableau, utilizing multiple visualization techniques to extract data patterns:
*   **Area Charts:** Mapped passenger distribution by travel class, purpose, and satisfaction.
*   **Dual Line Charts:** Compared the average scores of Inflight Wifi versus Entertainment across different age groups.
*   **Histograms (5-year bins):** Analyzed the age distribution of the passenger base.
*   **Grouped Bar Charts:** Evaluated travel purpose distribution by gender.
*   **Heatmaps:** Compared average service scores (ranging from 2.675 to 3.843) across Business, Eco, and Eco Plus classes.
*   **Scatter Plots:** Visualized the direct correlation between departure and arrival delays and their impact on satisfaction.
*   **Horizontal Bar Charts:** Ranked inflight services to identify the best and worst-performing amenities.

## Strategic Recommendation
The airline's primary operational focus should be upgrading its **Inflight Wifi** infrastructure, as it is the only service that consistently scores negatively across all age demographics and cabin classes. Improving this specific amenity will yield the highest return on overall passenger satisfaction.
