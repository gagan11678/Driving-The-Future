# Washington Electric Vehicle (EV) Adoption Analysis

## Project Overview

This project presents a comprehensive analysis of Electric Vehicle (EV) adoption trends within the state of Washington. Utilizing publicly available EV registration data, the study explores:

- Distribution and popularity of Battery Electric Vehicles (BEVs) versus Plug-in Hybrid Electric Vehicles (PHEVs).
- The evolution of electric vehicle range over time.
- Variations in EV pricing by region and Clean Alternative Fuel Vehicle (CAFV) eligibility.
- Adoption rates across legislative districts.
- Geospatial trends in EV clustering and the relationship with utility providers and charging infrastructure.

The objective is to derive meaningful insights into the dynamics shaping EV adoption across Washington and contribute to broader discussions on sustainable transportation trends.

---

## 1. BEVs vs. PHEVs Distribution Analysis

The initial phase of the analysis involved comparing the distribution of BEVs and PHEVs across various counties and cities.

**Key Observations:**
- **King County** exhibits the highest concentration of EVs, with BEVs significantly outnumbering PHEVs, particularly in Seattle.
- **Clark** and **Pierce Counties** demonstrate a relatively balanced distribution of BEVs and PHEVs.
- Technology-driven cities such as **Bellevue**, **Redmond**, and **Kirkland** show a higher prevalence of EVs, while emerging cities like **Bellingham** and **Spokane** also indicate growing adoption.

**Conclusion:** BEVs dominate EV ownership in urban centers, suggesting a strong inclination toward fully electric models among Washington’s population.

**Interactive Visualization:**  
[County Distribution Dashboard](https://public.tableau.com/views/Q1county/Dashboard1)

---

## 2. Evolution of EV Range Over Time

The second phase explored trends in the electric range of EVs across different model years.

**Key Observations:**
- In the early 2000s, EVs typically offered ranges below 100 miles.
- Mid-2010s saw advancements from manufacturers such as **Nissan** and **BMW**, achieving ranges between 80–100 miles.
- Post-2018, EV ranges exceeded 200 miles on average, with manufacturers like **Tesla**, **Chevrolet**, and **Hyundai** setting new benchmarks.

**Conclusion:** Significant technological advancements in battery systems have resulted in a consistent and substantial increase in EV range over the past decade.

**Interactive Visualization:**  
[EV Range Distribution](https://public.tableau.com/views/EVDistribution_17397702593090/Sheet3)

---

## 3. Base MSRP and CAFV Eligibility Analysis

The third analysis focused on understanding variations in Base Manufacturer’s Suggested Retail Price (MSRP) across regions and the influence of CAFV eligibility.

**Key Observations:**
- Cities such as **Hughesville** and counties like **Travis** report the highest average EV MSRPs, often exceeding $100,000.
- CAFV-eligible vehicles (typically long-range or luxury BEVs) demonstrate higher base MSRPs.
- Outliers (e.g., Tesla Model S Plaid) notably skew average prices.

**Conclusion:** There is a positive correlation between CAFV eligibility and higher vehicle prices, underscoring that long-range and premium EVs dominate CAFV-eligible lists.

**Interactive Visualizations:**  
[City Price Analysis](https://public.tableau.com/views/20city/Sheet4)  
[County Price Analysis](https://public.tableau.com/views/20counties/Sheet5)

---

## 4. Legislative District Analysis of EV Adoption

This phase analyzed EV adoption rates across Washington’s legislative districts.

**Key Observations:**
- Urban districts exhibited EV adoption rates exceeding 70–80%.
- Rural districts had significantly lower adoption rates, closer to 30–40%.
- A linear regression model using district names as predictors performed poorly (negative R²), suggesting geographical location alone is insufficient to explain adoption patterns.

**Conclusion:** EV adoption is significantly influenced by socio-economic factors such as income levels, education, and policy support rather than merely geography.

---

## 5. Geospatial Clustering and Utility Provider Analysis

The final stage involved geospatial clustering based on latitude and longitude to identify EV "hotspots," and assessing the impact of utility providers on EV-related variables.

**Key Observations:**
- Four major EV clusters were identified: **Northwest**, **Southwest**, **Central**, and **Southeast** Washington.
- King County and Seattle are primary hotspots for EV ownership and infrastructure development.
- Predictive models using only utility provider and location yielded poor results initially; however, incorporating additional variables (vehicle make, model year, CAFV eligibility) improved model accuracy significantly (R² = 0.84).

**Conclusion:** Vehicle-specific attributes play a larger role in determining EV value and adoption than geographical or utility factors alone.

---

## Final Conclusions

The findings from this project highlight several important trends:

- BEVs dominate Washington’s EV landscape, particularly in densely populated regions.
- The electric range of EVs has shown a consistent and substantial increase since 2015.
- CAFV-eligible vehicles are generally more expensive, driven by their enhanced range and premium features.
- EV adoption rates are higher in urban districts with strong infrastructure, emphasizing the importance of investment in public charging stations and supportive policy frameworks.

Washington is demonstrating leadership in EV adoption, providing insights that could inform other regions aiming to accelerate their transition to sustainable transportation.

---


*Prepared as part of an exploratory data science initiative on Electric Vehicle adoption trends in Washington State.*

