# DataSciencePolimi
The project “Analyzing Traffic Incidents Data from South Australia” was completed during the course Data Science and Security for Mobility in a four-person team. We cleaned and explored the data, searched for patterns and relationships, and built a machine learning model to support traffic safety analysis.

## Project Structure and Main Areas of Analysis

The work was divided into several thematic parts. Each team member focused on a different group of factors influencing road accidents. Together, the analyses helped us better understand how environment, infrastructure and external conditions affect accident frequency and severity.

Below is a short overview of all sections, with extended description of the parts related to **light, road and weather conditions**.

---

## Summary Statistics
- We started with general exploration of the dataset.
- We checked the number of accidents and their distribution across severity levels.
- This step helped us understand the scale of the problem and prepared the ground for deeper analysis.

---

## Regional Patterns
- We compared accident numbers between different regions.
- Urban areas concentrate the largest number of crashes.
- Some less populated regions show a relatively higher share of severe outcomes.

---

## Light & Road Conditions
*(main responsibility in the project)*

This part focused on visibility and road surface quality, and how they influence the seriousness of crashes.

### Light conditions
- Most accidents happen during daylight, mainly because traffic volume is highest.
- However, during the night we observe a **higher proportion of serious and fatal crashes**.
- Reduced visibility makes reaction time longer and increases stopping distance.

### Light combined with road surface
- We analyzed situations such as dry vs wet road in different lighting conditions.
- A wet surface at night significantly increases risk.
- Differences between dry and wet roads are smaller during the day.

### Serious and fatal crashes
- After filtering only severe outcomes, the role of darkness becomes even more visible.
- Night conditions, especially without street lighting, appear much more often in fatal statistics than in the general dataset.

### Absolute numbers vs risk
- Daytime dominates in total count.
- Nighttime dominates when we look at probability of severe consequences.
- This distinction is important for planning preventive actions.

### Key conclusions
- Visibility is one of the strongest environmental risk factors.
- Better lighting infrastructure could help reduce fatalities.
- Night + difficult road conditions is a high-risk combination.

---

## Weather Conditions
*(main responsibility in the project)*

In this section we investigated how atmospheric conditions change accident patterns.

### Distribution of accidents
- The majority of crashes occur in fine weather.
- This is expected because more vehicles are on the road.

### Weather vs severity
- Rain and adverse weather are linked with a higher chance of serious results.
- Lower grip and worse visibility increase braking distance and probability of collision.

### Regional differences
- The influence of rain is stronger in some regions.
- This may be related to infrastructure quality or driver behavior.

### Weather and light together
- One of the most dangerous combinations is **rain during night hours**.
- In such cases both visibility and control over the vehicle are reduced.

### Key conclusions
- Good weather does not automatically mean safe conditions.
- Adverse weather significantly increases the probability of severe accidents.
- Preventive communication to drivers could be especially important before and during rain.

---

## Time & Human Aspect
- We observed differences between peak hours and late night traffic.
- Human factors remain crucial, although they are harder to measure directly.

---

## Police Attendance
- Police presence is strongly connected with accident severity.
- Serious crashes are more likely to require official intervention.

---

## Predictive Modeling
- We built a binary model to estimate the probability of fatal outcomes.
- Environmental and road variables turned out to be important predictors.

---

## Future Improvements
- Extend the model with more driver and vehicle information.
- Include long-term temporal trends.
- Explore additional risk indicators useful for public safety planning.
