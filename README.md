# Formula 1 Dashboard

A data analytics project developed for the Programming for Artificial Intelligence Lab (AIL-202) at Bahria University Karachi Campus. This project leverages Power BI to create interactive dashboards for analyzing Formula 1 data, focusing on driver and constructor performance across multiple seasons. The dashboards provide insights into race wins, points, pit stop efficiency, and other key metrics, using data sourced from Kaggle and processed with Python.

## 🌟 Features

### Drivers Dashboard
- **Multi-Row Cards**: Highlights top performers (e.g., most wins: Lewis Hamilton, most participations: Fernando Alonso, highest win rate: Juan Fangio at 41.38%).
- **KPI Cards**: Displays total drivers and races.
- **Slicers**: Filters by race, driver, nationality, constructor, circuit, and season.
- **Visuals**:
  - **Donut Chart**: Top 10 nations producing successful drivers (e.g., UK, Germany, Finland).
  - **Line Chart**: Growth in drivers and races post-1980s.
  - **Gauges**: Percentage of finished races and accidents.
  - **Bar Chart**: Reasons for non-finishes (e.g., engine failures, accidents).
  - **Scatter Plot**: Impact of starting grid position on points scored.

### Constructors Dashboard
- **Multi-Row Cards**: Showcases dominant teams (e.g., Ferrari with 246 wins, 10,770 points, 1,088 races).
- **Slicers**: Filters by race, driver, constructor, circuit, and season.
- **Visuals**:
  - **Pie Chart**: Distribution of race wins among constructors.
  - **Table**: Top constructors by points and nationality.
  - **Tree Map**: Points breakdown by constructor and driver.
  - **Line Chart**: Average pit stop time by constructor.
  - **Area Chart**: Total points by season.
  - **Bubble Chart**: Points vs. wins, with race participation as bubble size.

## 🛠️ Technologies Used
- **Programming Language**: Python (Pandas, NumPy)
- **Visualization Tool**: Power BI (DAX measures, relational data modeling)
- **Data Source**: Kaggle Formula 1 dataset
- **File Formats**: CSV, Excel (`.xlsx`), Power BI (`.pbix`)

## 🚀 Setup and Installation

### Prerequisites
- **Python**: Version 3.8 or higher with Pandas, NumPy, and XlsxWriter.
- **Power BI Desktop**: Latest version for viewing and interacting with `F1 Dashboard 2.pbix`.
- **Unzipping Tools**: To extract `original dataset.zip` and `cleaned tables.zip`.

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Talha-Shahid-07/F1-Dashboard.git
   cd F1-Dashboard
   ```
2. **Set Up Python Environment**:
   Install required packages:
   ```bash
   pip install pandas numpy xlsxwriter
   ```
3. **Prepare Data**:
   - Extract `original dataset.zip` to access raw CSV files.
   - Extract `cleaned tables.zip` to use preprocessed CSV files or run `Pre-Processing/pre processing.py` to generate them.
   - Ensure `merged_f1_data_final.xlsx` is in the project root for Power BI import.
4. **Open Power BI Dashboard**:
   - Launch Power BI Desktop.
   - Open `F1 Dashboard 2.pbix` to view and interact with the dashboards.

## 💡 Usage
- **Preprocessing**: Run `pre processing.py` to clean and transform the Kaggle dataset, producing `cleaned_*.csv` files and `merged_f1_data_final.xlsx`.
- **Dashboard Interaction**:
  - Open `F1 Dashboard 2.pbix` in Power BI.
  - Use slicers to filter data by race, driver, constructor, or season.
  - Explore visuals to analyze driver and constructor performance metrics.
- **Sample Insights**:
  - Ferrari dominates with 246 wins and 10,770 points.
  - Starting grid position significantly impacts points scored.
  - Engine failures are the top reason for non-finishes.

## 📂 Project Structure
```
F1-Dashboard/
├── pre processing.py              # Python script for data cleaning
├── original dataset.zip           # Raw Kaggle dataset
├── cleaned tables.zip             # Cleaned CSV files
├── F1 Dashboard 2.pbix            # Power BI dashboard file
├── merged_f1_data_final.xlsx      # Merged dataset for Power BI
├── PAI LAB PROJECT REPORT.pdf     # Project report
├── README.md                      # This file
```

## 🤝 Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make and commit changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request on GitHub.

## 📧 Contact
For questions or support, please open an issue in the GitHub repository.

## Acknowledgments
Developed as part of the AIL-202 course at Bahria University Karachi Campus. Special thanks to Ms. Salas Akbar for her guidance and support throughout the project.
