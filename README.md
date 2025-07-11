# Ad Performance Analysis

A comprehensive data analysis project examining advertising lead performance and conversion patterns using Python and machine learning techniques.

## 📊 Project Overview

This analysis examines over 3,000 advertising leads to understand conversion patterns, identify key performance drivers, and build predictive models for lead quality assessment. The project focuses on debt relief advertising campaigns and their effectiveness across different channels, demographics, and creative elements.

## 🎯 Key Findings

- **Lead Quality Distribution**: 13.2% good quality leads, 86.8% poor quality leads
- **Geographic Performance**: State targeting is the strongest predictor (25.7% feature importance)
- **Debt Level Impact**: Debt level segmentation significantly affects conversion (17.6% feature importance)
- **Temporal Trends**: Monthly lead quality shows slight positive trend but not statistically significant
- **Model Performance**: Achieved 86.4% accuracy in predicting lead conversions

## 📈 Analysis Components

### 1. Exploratory Data Analysis
- Lead quality distribution across time periods
- Geographic performance analysis by state
- Campaign performance by publisher zones and referral domains
- Widget (ad creative) effectiveness analysis

### 2. Performance Segmentation
- **Where ads were shown**: Top performing referral domains and publisher zones
- **What kind of ads**: Widget names, advertiser campaigns, and ad groups
- **Who responded**: State demographics and debt level analysis

### 3. Trend Analysis
- Monthly lead quality trends with statistical significance testing
- Widget performance growth/decline analysis
- Cross-platform performance comparisons

### 4. Predictive Modeling
- Random Forest classifier for lead conversion prediction
- Feature importance analysis identifying key conversion drivers
- Model evaluation with precision, recall, and F1-score metrics

## 🛠️ Technologies Used

- **Python**: Primary analysis language
- **pandas**: Data manipulation and analysis
- **matplotlib/seaborn**: Data visualization
- **scikit-learn**: Machine learning modeling
- **statsmodels**: Statistical analysis and regression
- **numpy**: Numerical computations



### Running the Analysis
1. Clone the repository
2. Install required packages
3. Place your dataset in the `data/` directory
4. Run the Jupyter notebook: `jupyter notebook ad_performance_analysis.ipynb`

## 📊 Key Visualizations

### Lead Quality Distribution
- Monthly trends in lead quality percentages
- Geographic distribution of good vs. bad leads
- Campaign-wise performance breakdown

### Feature Importance Analysis
Top factors influencing lead conversion:
1. **State** (25.7%) - Geographic targeting effectiveness
2. **Debt Level** (17.6%) - Target audience segmentation
3. **Referral Domain** (17.0%) - Traffic source quality
4. **Widget Name** (15.3%) - Creative effectiveness
5. **Marketing Campaign** (7.6%) - Campaign strategy impact

### Performance Heatmaps
- Cross-analysis of referral domains vs. ad creatives
- State vs. debt level performance matrices
- Publisher zone effectiveness mapping

## 🔍 Business Insights

### Top Performing Elements
- **Best Referral Domains**: Identified high-converting traffic sources
- **Effective Ad Creatives**: Widgets showing consistent lead growth
- **Geographic Hotspots**: States with highest conversion rates
- **Optimal Debt Segments**: Most responsive debt level categories

### Recommendations
1. **Focus Geographic Targeting**: Prioritize high-performing states
2. **Optimize Creative Strategy**: Scale successful widget designs
3. **Refine Audience Segmentation**: Target optimal debt level ranges
4. **Channel Optimization**: Invest more in top-performing referral domains

## 📋 Model Performance

```
Model Accuracy: 86.45%

Classification Report:
                precision    recall    f1-score    support
Bad Leads           0.88      0.98      0.93       532
Good Leads          0.24      0.05      0.09        73
```



