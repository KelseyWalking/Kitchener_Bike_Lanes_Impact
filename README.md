# Kitchener_Bike_Lanes_Impact
Impact of Bike Lane Construction on Cyclist Counts in Kitchener
# KitchenerBikeLanesImpact

## Project Overview

Welcome to the KitchenerBikeLanesImpact project! This repository is dedicated to analyzing the relationship between bike lane construction and cyclist counts in the City of Kitchener, Canada. Our goal is to assess whether the introduction of new bike lanes has led to an increase in cycling activity.

## Research Question

Did cyclist volume significantly increase after new bike lanes were added in the City of Kitchener?

## Data Sources

We utilize publicly available data from the City of Kitchener and the Region of Waterloo, including:

- **Bike Lane and Cycling Infrastructure Maps**: This dataset includes information on bike lane locations and installation dates.
  - [Open Data Kitchener GIS](https://open-kitchenergis.opendata.arcgis.com/datasets/416741dbcb40451899b84ca7e10a80ee_0/explore?location=43.481704%2C-80.548744%2C13.30)

- **Cyclist Volume Counts**: Data from trail counters measuring cycling activity, including "before and after" counts relative to bike lane installation dates.
  - [City of Waterloo Trail Counter Data](https://open-kitchenergis.opendata.arcgis.com/datasets/City-of-Waterloo::city-of-waterloo-trail-counter-data/about)
  - [Additional Cyclist Volume Data](https://open-kitchenergis.opendata.arcgis.com/datasets/a5e1adba2e5545a9b4f0a1d198cd0498_0/explore?location=43.486603%2C-80.554115%2C14.49)
  - [More Information](https://open-kitchenergis.opendata.arcgis.com/documents/fe6b24fd18d046c8a126b8ddd24120c0/about)

## Methodology

1. **Data Acquisition and Preparation**: We source, clean, and link bike lane installation data with cyclist volume counts, ensuring proper spatial and temporal alignment.

2. **Exploratory Data Analysis (EDA)**: We visualize trends in cycling volume over time, map counter locations relative to new infrastructure, and identify patterns.

3. **Hypothesis Testing**:
   - Paired t-test to compare average cyclist counts from "before" and "after" periods at specific locations where new bike lanes were installed.
   - ANOVA to compare differences across multiple locations or types of infrastructure if applicable.

4. **Addressing Confounding Factors**: We plan to control for factors such as population growth, seasonality, weather conditions, etc., using methods like regression analysis, control groups, Difference-in-Differences (DiD), and fixed effects models.

## Expected Outcome

Through this analysis, we aim to uncover statistically significant trends and provide insights into the effectiveness of cycling infrastructure investments in encouraging cycling. Our findings will contribute to data-driven policy discussions and help guide future urban planning decisions.

## Contributing

We welcome contributions from the community! If you have suggestions or improvements, please open an issue or submit a pull request.

## Kaggle Dataset

We also plan to submit our compiled dataset to Kaggle for others to explore and provide their own solutions. Stay tuned for updates on this submission!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact us at [your-email@example.com].

---

Thank you for your interest in our project! Let's work together to make cities more bike-friendly.
