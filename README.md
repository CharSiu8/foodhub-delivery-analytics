# FoodHub Delivery Analytics

A comprehensive exploratory data analysis of food delivery order patterns to identify demand trends and revenue optimization opportunities. This project delivers actionable business recommendations backed by statistical analysis and data visualization.

## 📊 Project Overview

FoodHub is a food aggregator company that connects customers with restaurants through a mobile app. This analysis examines order data to understand customer behavior, demand patterns, and restaurant performance to help drive strategic business decisions.

### Business Problem

With increasing competition in the food delivery market, FoodHub needs to:
- Understand temporal demand patterns (weekday vs. weekend)
- Identify factors affecting customer ratings and satisfaction
- Optimize restaurant promotions and customer retention strategies
- Maximize revenue while maintaining service quality

## 🎯 Key Findings

### 1. Weekend Dominance
- **Average weekday orders**: 109.4 per day
- **Average weekend orders**: 675.5 per day
- Weekends generate 6x more business than weekdays

### 2. Promotional Strategy Impact
- Higher-rated restaurants receive more promotional support, creating a positive feedback loop
- This strategy may inadvertently alienate lower-performing restaurants
- Recommendation: Balanced promotional approach to support restaurant diversity

### 3. Customer Behavior Insights
- Delivery time does not significantly impact ratings (quality is the primary driver)
- Customer retention analysis reveals opportunities for loyalty programs
- Peak demand patterns suggest targeted promotion opportunities

## 💡 Strategic Recommendations

### Boost Weekday Engagement
**Proposed Strategy**: Time-windowed discount system
- Send push notifications at 3pm on weekdays
- Offer discounts for orders placed within 2-hour window with scheduled delivery
- Benefits:
  - Increases weekday revenue with minimal margin impact
  - Gives restaurants advance notice for better preparation
  - Reduces peak-hour stress on restaurant operations
  
**Implementation Plan**:
1. Run 2-week pilot program with full promotions
2. Collect engagement and conversion data
3. Optimize discount percentage and timing based on results
4. Transition to sustainable long-term promotion schedule

### Customer Retention Focus
- Identify "whale" customers (top 5% by order frequency/value)
- Develop loyalty program targeting repeat customers
- Analyze churn patterns to reduce customer loss

## 🛠️ Technical Stack

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 📁 Dataset

The analysis examines 1,898 food delivery orders with the following features:
- Order details (ID, date, time, cost)
- Restaurant information (name, cuisine type)
- Customer ratings
- Delivery metrics (preparation time, delivery time)
- Promotional data

**Dataset source**: Available in repository

## 🔍 Analysis Workflow

1. **Data Loading & Exploration**
   - Initial data inspection and structure analysis
   - Identifying data types and missing values

2. **Data Cleaning**
   - Handling missing values (736 unrated orders)
   - Type conversions for temporal data
   - Outlier detection and treatment

3. **Exploratory Data Analysis**
   - Temporal patterns (weekday vs. weekend, hourly trends)
   - Restaurant performance analysis
   - Rating distribution and factors
   - Cost and delivery time analysis

4. **Statistical Analysis**
   - Correlation analysis between variables
   - Hypothesis testing for rating factors
   - Customer segmentation analysis

5. **Visualization & Insights**
   - Interactive plots for demand patterns
   - Distribution analyses
   - Comparative visualizations

6. **Business Recommendations**
   - Data-driven strategic proposals
   - Implementation roadmaps
   - Expected impact analysis

## 📈 Key Visualizations

- Weekday vs. weekend order volume comparison
- Rating distribution by restaurant and cuisine type
- Temporal demand patterns (hourly, daily, weekly)
- Delivery time vs. customer satisfaction analysis
- Customer segmentation and order frequency distribution

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Analysis
```bash
jupyter notebook FoodHub_Data_Analysis.ipynb
```

## 📝 Project Structure

```
foodhub-delivery-analytics/
├── FoodHub_Data_Analysis.ipynb    # Main analysis notebook
├── FoodHub_Data_Copy.csv          # Dataset
├── README.md                       # Project documentation
└── requirements.txt                # Python dependencies
```

## 🎓 Skills Demonstrated

- **Data Analysis**: Comprehensive EDA with statistical rigor
- **Business Intelligence**: Translating data insights into actionable strategies
- **Data Visualization**: Clear, compelling visual storytelling
- **Statistical Thinking**: Hypothesis testing and correlation analysis
- **Strategic Thinking**: Revenue optimization and customer retention strategies
- **Communication**: Clear documentation and stakeholder-ready recommendations

## 📬 Contact

**Steven** - [Your Email/LinkedIn]

---

*This project demonstrates end-to-end data analysis capabilities from raw data exploration to strategic business recommendations, showcasing both technical proficiency and business acumen.*
