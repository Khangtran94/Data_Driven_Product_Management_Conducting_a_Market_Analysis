# Data-Driven Product Management: Conducting a Market Analysis

## Project Overview
This repository contains a Python-based market analysis project for a fitness studio in Singapore aiming to develop digital fitness products. The analysis leverages Google Trends and YouTube keyword search data to assess global and regional demand for fitness-related products and services, identify competitor strengths, and uncover opportunities for unique digital offerings.

## Objectives
- **Explore Global and Regional Trends**: Analyze interest in fitness workouts globally and in specific regions, including Singapore, to understand market demand.
- **Identify Peak Interest**: Determine the year with the highest global search interest for the keyword "workout" and save it as `year_str` in the format "yyyy".
- **Analyze Keyword Popularity**: Identify the most popular fitness-related keywords during the COVID-19 pandemic and currently, saved as `peak_covid` and `current`, respectively.
- **Determine Regional Leaders**: Identify which country among the United States, Australia, or Japan has the highest interest in workouts, saved as `top_country`.
- **Expansion Opportunities**: Evaluate potential for expanding virtual home workout offerings to either the Philippines or Malaysia.

## Dataset
The analysis uses CSV files containing:
- **Google Trends Data**: Global and regional search interest for fitness-related keywords.
- **YouTube Keyword Search Data**: Insights into fitness-related content searches.

These datasets are located in the `data` folder and are processed using helper functions `read_file` and `read_geo` for efficient data loading and visualization.

## Prerequisites
To run the analysis, ensure you have the following installed:
- Python 3.8+
- Required Python libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`

Install dependencies using:
```bash
pip install pandas matplotlib seaborn
```

## Repository Structure
```
├── data/                    # CSV files containing Google Trends and YouTube data
├── notebook.ipynb           # Jupyter Notebook with the market analysis
├── README.md               # Project documentation
```

## Usage
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Khangtran94/Data_Driven_Product_Management_Conducting_a_Market_Analysis.git
   cd Data_Driven_Product_Management_Conducting_a_Market_Analysis
   ```

2. **Run the Analysis**:
   - Open the `notebook.ipynb` in Jupyter Notebook or JupyterLab.
   - Execute the cells to load, process, and analyze the data.
   - The notebook includes visualizations and insights to guide product strategy decisions.

3. **Key Outputs**:
   - Visualizations of global and regional fitness trends.
   - Identification of peak search years and popular keywords.
   - Recommendations for digital product offerings based on market gaps and competitor analysis.

## Key Insights
- **Market Demand**: Understand which fitness keywords and workout types are trending in Singapore and globally.
- **Competitor Analysis**: Identify strengths of competitors to inform unique value propositions.
- **Expansion Strategy**: Data-driven recommendations for targeting markets like the Philippines or Malaysia.

## Future Work
- Conduct periodic analyses (e.g., every 6 months) to stay updated on market trends.
- Explore additional datasets, such as social media sentiment or app store reviews, for deeper insights.
- Pilot digital products like Zumba or Yoga-based virtual classes based on identified trends.

## Contributing
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your changes. Ensure code follows PEP 8 style guidelines.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Data provided by [DataCamp](https://www.datacamp.com).
- Inspired by real-world product management challenges in the fitness industry.
