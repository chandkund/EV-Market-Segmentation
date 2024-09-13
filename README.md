
# **EV Market Segmentation**

## **Project Overview**
This project focuses on segmenting the Electric Vehicle (EV) market in India to identify key customer groups based on their preferences, behaviors, and demographics. The insights derived from this segmentation will aid in tailoring marketing strategies, improving product offerings, and boosting customer satisfaction. The analysis uses customer survey data to understand preferences regarding EV features, charging infrastructure, and price sensitivity.

## **Dataset Description**
The dataset used for this project contains demographic information and customer preferences. The columns include:
- **ID:** Unique identifier for each customer.
- **Gender:** Customer's gender.
- **Ever_Married:** Marital status of the customer.
- **Age:** Age of the customer.
- **Graduated:** Whether the customer has completed their graduation.
- **Profession:** The customer's profession.
- **Work_Experience:** Number of years of work experience.
- **Spending_Score:** A metric indicating the customer's spending habits.
- **Family_Size:** Number of family members in the customer's household.
- **Var_1:** Additional customer feature (e.g., preferred type of EV).
- **Segmentation:** The segment or cluster each customer belongs to based on their preferences and demographics.

The second dataset contains **EV sales data** across Indian states for the years 2020 to 2023, providing a historical overview of EV adoption trends.

## **Project Objectives**
- Segment the EV market in India based on customer demographics and preferences.
- Identify key customer segments that are most likely to purchase EVs.
- Provide actionable insights for marketing and business strategies.

## **Installation Instructions**
### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook (optional, for code exploration)
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

To install the required libraries, run:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Cloning the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/chandkund/EV-Market-Segmentation.git
```

Navigate into the project directory:
```bash
cd EV-Market-Segmentation
```

## **Usage Guide**
### Data Preprocessing
The datasets need to be preprocessed before segmentation. Steps include:
- Handling missing values.
- Encoding categorical variables such as `Gender` and `Ever_Married`.
- Scaling numeric features like `Age`, `Work_Experience`, and `Spending_Score`.

### Customer Segmentation
To perform customer segmentation, the K-Means Clustering algorithm is applied. The script segments customers into different clusters based on their demographic and preference data. You can run the clustering script by executing:
```bash
python customer_segmentation.py
```
This will output the segmentation results and visualize the clusters.

### Sales Trend Analysis
The EV sales dataset is analyzed to observe trends over the years and across different states/UTs. Use the following script to analyze EV sales data:
```bash
python sales_trend_analysis.py
```
This script generates visualizations and insights into how EV adoption has grown in different regions.

### Marketing Mix and Target Segment
Based on the analysis, the marketing mix (4Ps) is determined for the targeted customer segments. Key findings from this section:
- **Target Segment:** Customers aged **20-35 years** with a family size of more than one are the most promising group for EV adoption. Graduates in this segment show a stronger preference for EVs.
- **Price Strategy:** Pricing must reflect the quality of EVs and customer price sensitivity. This balance will help attract cost-conscious consumers while ensuring profitability.
- **Place Strategy:** Bangalore is identified as an ideal location to focus initial marketing efforts, as it has shown higher EV adoption rates.
- **Promotion Strategy:** Digital marketing campaigns, loyalty programs, and family-centric promotions will drive sales among target segments.

## **Code Explanation**
The repository includes several Python scripts to guide you through the segmentation and analysis process:
- `customer_segmentation.py`: Performs customer segmentation using K-Means Clustering.
- `sales_trend_analysis.py`: Analyzes EV sales data to identify adoption trends.

## **Results**
- **Customer Segments:** The K-Means algorithm identified distinct customer segments based on their age, spending score, and family size. The most promising segments for EV marketing are young professionals and families.
- **Sales Trends:** EV sales have grown significantly from 2020 to 2023, with notable growth in cities like Bangalore. This trend suggests increasing adoption in urban centers with better charging infrastructure.
  
## **Conclusion**
This project successfully segmented the EV market in India and provided valuable insights that can be used to tailor marketing strategies for different customer segments. The target group identified is more likely to adopt EVs, and focused efforts in Bangalore will yield better results initially.

## **Future Work**
Further analysis could involve:
- Expanding the customer dataset with additional preferences such as vehicle model choices and environmental concerns.
- Performing a more detailed geographic analysis to uncover other regions with high EV adoption potential.
- Incorporating other segmentation algorithms like DBSCAN or Hierarchical Clustering for comparison.

## **License**
This project is licensed under the MIT License - see the LICENSE file for details.
