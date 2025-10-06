# EDA-Zomato_dataset  

---

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on Zomato data to uncover trends and patterns in in restaurant finding. We use libraries like **Pandas, Numpy, Matplotlib, Seaborn**for cleaning, visualization, and analysis. 

![](https://github.com/Saswati-18/EDA-Zomato_dataset/blob/main/zomato.jpg)

---

## Objective
The goal of this project is to:
1.Analyze **cost for two, online order, and table booking options** across different restaurant.
2.Understand **customer vote and rating patterns**.
3.Provide **recommendations for restaurants and customers** based on insights.

---

## Dataset
The dataset contains 148 entries and 7 features, including:
**name**: Name of the Restaurant listed
**online_order**: online ordering option available or not
**book_table**: Table booking option available or not
**rate**: Rating of the restaurant 
**votes**: Votes of the restaurant
**approx_cost(for two people)**: Approx. cost for two
**listed_in(type)**: Listed Restaurant type (e.g.-Dining,Cafes,Buffet, others)

---

## Steps and Workflow
**1. Data Cleaning**
Fix data types: Converted rate to a float object.

**2. EDA (Exploratory Data Analysis)**
Rating of Restaurant:
highest and Lowest rated restaurant

 1.**Price Analysis:** 
Maximum cost and minimun cost for two in the restaurants listed 
Online Ordering option:
90 restaurants does not have online order option available.

 2.**Table booking option:**
140 restaurants does not have table booking option.

 3.**Types of Listed restaurants:**
Used histogram to get the count for each restaurant type.

 4.**Price distribution:**
Used histograms to show the distribution of prices.
Majority of the listings were priced between rupees 100 - 600.

 5.**Review behavior:**
Used pair plots to show relationships between number of rating, votes, and cost for two for each restaurant type.

**3. Data Visualization**
**Pairplot:** To see correlations among cost_for_two, votes, and number of ratings.
**Heatmap:** Showing correlations among numerical features.
**Histograms and Boxplots:** To detect outliers in price.
**Scatter plot:** Displaying rating and cost for two distributions.

---

## Key Findings and Insights
**Rating :**
Highest is Onesta and Lowest rated restaurant is Nandhini Deluxe
**Online order:**
Most of the restaurants does not have online ordering option available 
**Price:**
Most of the restaurants approx. cost for two lies between 200-600
**Table booking :**
140 restaurants does not have table booking options
**Types of Restaurants Listed:**
Majority are Dinning, few are cafes and very less number of buffet 

---

## Recommendations
**For customers:**
Choose restaurants with high votes and consistent ratings.
Online delivery offers more choices with lower costs.
**For Restaurant:**
Enable online ordering to increase visibility.
Encourage user reviews and ratings for higher engagement.
Track high-performing categories like Dine-out or Buffet for expansion.

---

## Conclusion
This project offers valuable insights into the Zomato Restaurant data, helping both customers and owners make informed decisions. By using EDA techniques, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.
