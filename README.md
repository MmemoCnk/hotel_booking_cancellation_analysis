# 🏨 Hotel Booking Cancellation Prediction

A comprehensive machine learning analysis to predict hotel booking cancellations and provide actionable business insights.

## 📊 Project Overview

This project analyzes hotel booking data to predict cancellations, which affect **37% of all bookings**. Using machine learning techniques, we achieved **87% accuracy** in predictions and identified key factors driving cancellations.

### Key Results
- 📈 **87% Accuracy** with Random Forest model
- 🎯 **0.94 AUC Score** 
- 💰 **$3.5-7.2M** potential annual savings
- 🔍 Identified **5 key cancellation drivers**
- 👥 Created **5 customer segments**

## 🚀 Quick Start

### Prerequisites
```bash
# Required libraries
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Running the Analysis
```bash
# Clone the repository
git clone https://github.com/yourusername/hotel-cancellation-prediction.git
cd hotel-cancellation-prediction

# Open Jupyter Notebook
jupyter notebook Hotel_Booking_Cancellation_Analysis.ipynb
```

## 📁 Repository Contents

```
hotel-cancellation-prediction/
├── Hotel_Booking_Cancellation_Analysis.ipynb  # Main analysis notebook
├── hotel_booking_cancellation_analysis_and_prevention_strategy.py  # Main analysis python
├── hotel_bookings.csv                          # Dataset (119,390 bookings)
└── README.md                                   # Project documentation
```

## 📓 Notebook Structure

The Jupyter notebook contains the complete analysis pipeline:

1. **Data Loading & Exploration**
   - Dataset overview and statistics
   - Missing value analysis
   - Initial visualizations

2. **Data Cleaning & Preparation**
   - Handling missing values
   - Removing outliers
   - Data type corrections

3. **Feature Engineering**
   - Creating 13 new features
   - Encoding categorical variables
   - Feature scaling

4. **Model Development**
   - Training 4 ML models
   - Hyperparameter tuning
   - Cross-validation

5. **Model Evaluation**
   - Performance metrics
   - ROC curves
   - Feature importance analysis

6. **Business Insights**
   - Customer segmentation
   - Risk scoring system
   - ROI calculations
   - Actionable recommendations

## 📊 Key Findings

### Top 5 Risk Factors
1. **Lead Time** - Bookings >100 days in advance
2. **No Deposit** - Missing financial commitment
3. **High ADR** - Expensive room rates
4. **Portuguese Guests** - Domestic market behavior
5. **No Special Requests** - Lack of personalization

### Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | 87% |
| Precision | 84% |
| Recall | 81% |
| F1-Score | 82% |
| AUC | 0.94 |

## 💼 Business Recommendations

1. **Implement Risk-Based Pricing**
   - Dynamic pricing based on cancellation probability
   - Early-bird discounts for high-risk periods

2. **Targeted Deposit Policies**
   - Mandatory deposits for high-risk bookings (>60% probability)
   - Flexible policies for loyal customers

3. **Proactive Communication**
   - Automated reminders 30-60 days before arrival
   - Personalized offers to prevent cancellations

4. **Revenue Optimization**
   - Strategic overbooking based on predictions
   - Optimized inventory allocation

## 🛠️ Technologies Used

- **Python 3.8+**
- **pandas** - Data manipulation
- **scikit-learn** - Machine learning
- **matplotlib/seaborn** - Visualizations
- **numpy** - Numerical operations

## 📈 Dataset Information

- **Source**: Hotel booking demand dataset
- **Size**: 119,390 bookings
- **Features**: 32 variables
- **Target**: is_canceled (binary)
- **Time Period**: 2015-2017

## 🤝 Contributing

Feel free to open issues or submit pull requests with improvements.

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Dataset from [Kaggle Hotel Booking Demand](https://www.kaggle.com/jessemostipak/hotel-booking-demand)
- Based on research by Antonio, Almeida & Nunes (2019)

## 📧 Contact

For questions or collaboration opportunities, please reach out through GitHub issues.

---

⭐ **If you find this analysis helpful, please consider giving it a star!**
