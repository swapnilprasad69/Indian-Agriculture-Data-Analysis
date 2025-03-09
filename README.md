# Indian Agriculture Data Analysis

## Project Overview
This project analyzes Indian agricultural data using **SQL, Python (Pandas), and EDA tools**. The primary focus is on district-wise yearly **area, yield, and production** trends of **20 major crops** across India.

## Dataset
- **Source:** ICRISAT (International Crops Research Institute for the Semi-Arid Tropics)
- **Contains:**
  - Crop-wise area (in 1000 ha)
  - Production (in 1000 tonnes)
  - Yield (kg/ha)
  - Yearly data across multiple districts

## Analysis Performed
### 1. Exploratory Data Analysis (EDA)
- Data Cleaning and Handling Missing Values
- Statistical Summary & Distribution Analysis
- Correlation Matrix to identify dependencies between features

### 2. Key Insights
#### Correlation Analysis
- A heatmap visualization of **Kharif Sorghum Area vs. Rabi Sorghum Area** shows a correlation coefficient of **0.21**, indicating a weak positive correlation.

  ![Correlation Matrix](image.png)

#### Crop Production Trends
- Trend analysis on **Wheat, Rice, Pulses, and Oilseeds** across districts
- Time-series visualization to understand fluctuations in production

#### Yield Efficiency Comparisons
- Comparison of **yield trends across different states** to identify high and low-performing areas

## Technologies Used
- **SQL** (Data Extraction & Transformation)
- **Python (Pandas, NumPy, Matplotlib, Seaborn)** (Data Processing & Visualization)
- **Power BI / Tableau** (For Dashboard & Interactive Analysis)

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Indian-Agriculture-Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore EDA and visualizations.

## Future Scope
- **Machine Learning Models** for predicting crop yields
- **More Visualization Dashboards** for better insights
- **Interactive Web Application** for real-time data analysis

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

---
### Author
**Swapnil Prasad**

For any queries, feel free to reach out!

