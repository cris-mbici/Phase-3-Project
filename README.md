# SyriaTel Customer Churn Analysis

A comprehensive data science project analyzing customer behavior to predict and prevent churn in the telecommunications industry.

## Project Overview

**Objective**: Build a predictive model to identify at-risk customers and develop data-driven retention strategies for SyriaTel.

**Business Impact**: Projected 20-30% reduction in customer churn through targeted interventions.

## Dataset

- **Source**: SyriaTel customer database
- **Size**: 3,333 customers with 21 behavioral attributes
- **Quality**: Complete dataset with no missing values
- **Features**: Usage patterns, billing information, service interactions, demographics, and churn outcomes

## Analysis Methodology

### 1. Exploratory Data Analysis
- **Univariate Analysis**: Distribution patterns for key metrics
- **Bivariate Analysis**: Churn relationships across features
- **Multivariate Analysis**: Complex interactions and geographic patterns

### 2. Statistical Testing
- **Levene's Test**: Variance homogeneity testing
- **Mann-Whitney U Test**: Non-parametric group comparisons
- **Chi-Square Test**: Categorical associations
- **Kruskal-Wallis Test**: Multi-group distribution analysis

### 3. Machine Learning Models
- **Logistic Regression**: Baseline linear model
- **Decision Tree**: Interpretable non-linear model
- **XGBoost**: Advanced ensemble method (selected as final model)

## Key Findings

### Primary Churn Drivers
1. **Service Experience**: Churn probability jumps to 50% after 4+ service calls
2. **International Plans**: 42% churn rate vs. 11% for standard plans
3. **Value Perception**: High-usage customers feel overcharged
4. **Geographic Factors**: Significant state-level variations (New Jersey highest risk)

### Model Performance
- **Accuracy**: 87.5%
- **Recall**: 75% (catches 3 out of 4 potential churners)
- **F1 Score**: 0.64
- **Precision**: Balanced to minimize false alarms

## Business Recommendations

### Immediate Actions (0-3 months)
1. **Deploy Early Warning System**: Automated at-risk customer identification
2. **Service Excellence Initiative**: First-call resolution and proactive outreach
3. **International Plan Redesign**: Transparent pricing to eliminate bill shock

### Strategic Initiatives (3-6 months)
4. **Value Bundle Creation**: Amazon Prime-style service packages
5. **Geographic Targeting**: State-specific retention campaigns
6. **Loyalty Program Launch**: Tiered rewards for long-term customers

## Technical Stack

- **Python**: Core analysis language
- **Pandas & NumPy**: Data manipulation and analysis
- **Scikit-learn**: Machine learning models and evaluation
- **XGBoost**: Advanced predictive modeling
- **Matplotlib & Seaborn**: Data visualization
- **SciPy**: Statistical testing
- **Jupyter Notebook**: Interactive analysis environment

## Results Impact

### Financial Benefits
- **Revenue Protection**: Reduced customer lifetime value loss
- **Cost Savings**: Lower customer acquisition expenses
- **ROI**: Projected 300%+ return on retention investments

### Operational Improvements
- **Proactive Customer Care**: Shift from reactive to predictive service
- **Resource Optimization**: Targeted interventions in high-risk segments
- **Competitive Advantage**: Data-driven customer retention capabilities

## Implementation Timeline

- **Month 1**: Model deployment and staff training
- **Month 2**: Service process improvements
- **Month 3**: Pricing structure updates
- **Month 4**: Bundle and loyalty program launch
- **Month 5**: Geographic targeting rollout
- **Month 6**: Full system integration and monitoring

## Success Metrics

- **Primary**: Monthly churn rate reduction
- **Secondary**: Service call resolution rates, customer satisfaction scores
- **Leading Indicators**: Early warning system accuracy, intervention success rates

## Stakeholder Value

**For Executives**: Clear ROI and competitive advantage through customer retention
**For Operations**: Actionable intervention points and resource optimization
**For Customer Service**: Enhanced tools and processes for customer success
**For Marketing**: Targeted retention campaigns and loyalty programs

## Contact

For questions about methodology, implementation, or results interpretation, please reach out for detailed discussions and technical walkthroughs.

---

*This analysis provides SyriaTel with a comprehensive, data-driven approach to customer retention that transforms reactive customer service into proactive relationship management.*
