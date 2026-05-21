# Bike Sales Dashboard

A comprehensive Excel-based analytical dashboard for tracking and visualizing bike sales metrics across multiple dimensions including customer demographics, purchasing behavior, and geographic regions.

## 📊 Project Overview

This project contains an interactive Excel dashboard built to analyze bike sales data with a focus on understanding customer purchasing patterns, income trends, and commute behavior across different demographic segments.

## 🎯 Key Features

### Interactive Filters
- **Marital Status**: Filter data by Married or Single customers
- **Region**: Analyze performance across Europe, North America, and Pacific regions
- **Education Level**: Segment customers by Bachelors, Graduate Degree, High School, Partial College, and Partial High School

### Dashboard Visualizations

1. **Average Income Per Purchase**
   - Bar chart comparing income levels across gender segments
   - Breakdown by purchased bike status (Yes/No)
   - Identifies high-value customer segments

2. **Customer Age Brackets**
   - Line chart showing customer distribution across age groups (Adult, Middle Age, Old)
   - Dual-line comparison for purchased vs. non-purchased categories
   - Helps identify target demographics

3. **Count of Purchased Bikes**
   - Overview of total bike purchases segmented by customer attributes
   - Quick metric for sales performance tracking

4. **Customer Commute Distance**
   - Multi-distance analysis (0-1 Miles, 1-2 Miles, 2-5 Miles, 5-10 Miles, More than 10 Miles)
   - Trend comparison between purchased and non-purchased segments
   - Insights into how commute distance affects purchasing decisions

### Data Sheets
- **bike_buyers**: Raw customer and sales transaction data
- **Pivot Table**: Aggregated data for dashboard visualizations
- **Dashboard**: Interactive visualization hub with slicers and charts

## 📁 File Structure

```
bike-sales-dashboard/
├── Excel Project Dataset.xlsx    # Main workbook with all data and visualizations
├── README.md                      # This file
└── docs/
    └── usage-guide.md            # Detailed user guide (optional)
```

## 🚀 Getting Started

### Prerequisites
- Microsoft Excel 2016 or later (or compatible spreadsheet software like LibreOffice Calc)
- Basic familiarity with Excel slicers and pivot tables

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/bike-sales-dashboard.git
   cd bike-sales-dashboard
   ```

2. Open the Excel file:
   ```bash
   open "Excel Project Dataset.xlsx"
   ```

3. Navigate to the **Dashboard** sheet tab to interact with visualizations

## 📈 How to Use

1. **Applying Filters**: Click on any filter button (Marital Status, Region, Education) and select desired values
2. **Analyzing Charts**: All visualizations update automatically based on selected filters
3. **Exporting Data**: Use Excel's native export features to generate reports from the dashboard
4. **Modifying Data**: Update the `bike_buyers` sheet with new data; pivot tables will refresh automatically

## 📊 Dataset Information

- **Data Points**: Customer demographic information including age, marital status, education level, income, commute distance
- **Geographic Coverage**: Europe, North America, Pacific regions
- **Key Metrics**: Bike purchase status, income levels, commute distance, age demographics
- **Time Period**: [Specify the time period your data covers]

## 🎨 Dashboard Design Highlights

- Clean, professional layout with blue header branding
- Color-coded charts for easy comparison (Blue = No, Orange = Yes for purchase status)
- Dynamic slicers for real-time filtering without manual updates
- Multiple perspectives on the same data for comprehensive analysis

## 💡 Use Cases

- **Sales Analysis**: Track which customer segments have the highest purchase rates
- **Marketing Strategy**: Identify target demographics based on age, income, and commute patterns
- **Product Planning**: Understand how geographic location and commute distance influence bike purchases
- **Customer Segmentation**: Analyze purchasing behavior across education and marital status groups

## 🔧 Technical Details

- **Pivot Tables**: Used for data aggregation and dimensional analysis
- **Slicers**: Connected to multiple charts for synchronized filtering
- **Chart Types**: Bar charts, line charts, and data tables for comprehensive visualization
- **Data Validation**: Built-in filters ensure data integrity

## 📝 Data Privacy & Disclaimer

This dashboard is built on sample or anonymized data for analytical purposes. Ensure all sensitive customer information is handled according to your organization's data governance policies.

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📋 Future Enhancements

- [ ] Add time-series analysis for seasonal trends
- [ ] Implement predictive modeling for customer lifetime value
- [ ] Create additional visualizations for product category analysis
- [ ] Develop automated reporting features
- [ ] Add data refresh automation from external sources


## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Wajeeha Noor**

## 🙏 Acknowledgments

- Excel visualization best practices from Microsoft
- Data visualization principles from industry standards
- Community feedback and contributions

---

**Last Updated**: May 2026  
**Version**: 1.0.0
