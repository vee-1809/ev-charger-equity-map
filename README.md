# EV Charger Equity Map

This project identifies underserved ZIP codes in California based on the availability of public electric vehicle (EV) charging stations and socioeconomic indicators such as median household income and population.

## 🚀 Objective

To support equitable EV infrastructure planning by highlighting areas with:
- Low charger density per 10,000 people
- Low median household income

This project enables policymakers and planners to prioritize regions for future EV charger deployment.

## 🗂️ Data Sources

- [U.S. DOE Alternative Fuel Stations Dataset](https://afdc.energy.gov/stations/)
- [SimpleMaps US ZIP Code Database (Free)](https://simplemaps.com/data/us-zips)
- [American Community Survey 2023 (ACS 5-Year)](https://data.census.gov/)

## 🧪 Methodology

1. Count EV charging stations per ZIP code
2. Merge with ZIP-level population to compute charger density
3. Join ACS data to add median household income
4. Flag underserved ZIPs where:
   - Charger count < 2  
   - Median income < $45,000
5. Visualize underserved ZIPs using `folium`

## 🗺️ Output

- A map of California highlighting ZIPs with infrastructure gaps
- A list of top underserved ZIP codes by income and charger availability

## 🛠️ Tools & Technologies

- Python (Pandas, Folium)
- Jupyter / Google Colab
- Public government and open-source datasets

## 📈 Future Work

- Add real-time charger usage data
- Integrate traffic volume or EV ownership per ZIP
- Use H3 indexing for more granular spatial resolution

## 📄 License

This project is open for academic, nonprofit, and public planning use.

---

🔗 Connect with me on [LinkedIn](https://www.linkedin.com)  
💡 Feel free to fork, clone, or reach out with questions or collaborations.
