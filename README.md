# Coffee Shop Sales Analysis
This repository contains an analysis of sales data for a coffee shop. The objective is to gain insights into sales patterns, product performance, and customer preferences. The analysis is presented through data exploration, pivot tables, and a dashboard, making it suitable for showcasing data analysis skills and methodologies.

## Data
The data used in this analysis includes transaction records from a coffee shop, detailing various aspects such as transaction date and time, product category, product type, and total bill amount. The data is organized into the following sheets:
    - Data: Contains raw transactional data.
    - Pivot: Contains pivot tables for summarizing data.
    - Dashboard: Contains visualizations and key insights.

## Preprocessing
To kick off the project and ensure accurate results, I started by cleaning the data. This involved removing any duplicate entries to avoid skewed outcomes. I also updated some values to make them more understandable, like changing “Rg”, “Lg”, and “Sm” to “regular”, “large”, and “small”. To help with better visualization, I created new columns for the month, hour, and day of the week. Additionally, I checked for any missing data and made sure each field had the correct data type.

## Analysis overview
To find patterns and insights in the data the exploratory analysis was performed, which includes the following:
  1. Data Exploration: Initial exploration of the raw data to understand the key metrics and trends.
  2. Pivot Tables: Summary tables created to aggregate data by various dimensions such as day of the week, product category, and month.
  3. Dashboard: Visualizations highlighting key insights such as sales trends, top-performing products, and sales distribution by time.

But first, business questions were formulated, answers of which could help the coffee shop provide actionable insights for improving sales, managing inventory, and planning marketing and operational strategies:
- When are the peak sales periods? (to identify the days and hours with the highest sales to optimize staffing and inventory).
- Which products are the top sellers? (to highlight which products drive the most sales volume to focus marketing efforts).
- How do sales vary by product category? (to compare performance across different categories like coffee, tea, bakery items, etc.).
- What is the sales distribution by store location? (to examine how sales differ across various store locations to identify high-performing areas).
- How do seasonal trends affect sales? (to analyze monthly sales patterns to prepare for seasonal fluctuations).
- Are there specific times of day with higher or lower sales? (to identify peak times of day for sales to inform promotional activities and operational planning).
- What are the most popular product sizes? (to evaluate the preference for product sizes (e.g., regular, large, small) to optimize product offerings).
- Do sales trends vary by day of the week? (to determine if certain days consistently show higher or lower sales, guiding weekly promotions and staffing).
- What is the total revenue generated over the analysis period? (to provide a summary of total revenue to assess overall financial performance).
- How effective are different product types in driving sales? (to look at the impact of product types (e.g., brewed herbal tea vs. coffee beans) on overall sales).
- Which products contribute most to total revenue? (to identify products that generate the highest revenue, informing stocking decisions and promotions).
- How does customer purchase behavior vary over time? (to analyze patterns in customer purchases to predict future trends and tailor customer engagement strategies).
- What are the average transaction amounts? (to calculate the average bill to help understand customer spending habits and inform pricing strategies).
- Are there any notable differences in sales trends by hour of the day? (to identify hourly sales trends to optimize store hours and special time-based promotions).

## Key Findings and Recommendations
These insights and recommendations can help the coffee shop enhance its operations, increase sales, and better serve its customers:
1. **Peak Sales Periods**
   **Insights**: Sales peak during weekday mornings (7-10 AM) and late afternoons (3-6 PM), with weekends, especially Saturdays, also showing high sales.
   **Recommendations**:
     - Increase Staffing: Allocate more staff during peak hours to handle the rush efficiently.
     - Promotions: Offer morning and afternoon promotions to capitalize on high traffic times.
     - Inventory Management: Ensure sufficient stock of popular items during peak times to meet demand.

2. **Product Popularity**
   **Insights**: Coffee beverages, particularly regular and large-sized brewed coffee, are the top sellers. Pastries and lattes also perform well.
   **Recommendations**:
     - Expand Coffee Options: Introduce seasonal or specialty coffee beverages to attract more customers.
     - Upsell Larger Sizes: Promote larger sizes through pricing strategies or combo deals to increase average transaction value.
     - Enhance Pastry Offerings: Regularly update pastry selections to keep the menu interesting and encourage repeat visits.
    
3. **Sales by Product Category**
   **Insights**: Coffee is the dominant category, followed by bakery items. Branded merchandise contributes the least to sales.
   **Recommendations**:
     - Focus on Coffee: Invest in quality coffee beans and brewing techniques to enhance customer satisfaction and loyalty.
     - Bakery Variety: Offer a variety of fresh bakery items, including healthy options, to complement coffee sales.
     - Merchandise Strategy: Reevaluate the merchandise strategy; consider introducing more appealing items or creating bundle deals with beverages.
       
4. **Sales Distribution by Location**
   **Insights**: The downtown store generates the highest sales, while suburban locations have steady but lower sales.
   **Recommendations**:
     - Location-Specific Marketing: Tailor marketing efforts to each location's customer base. For example, offer promotions suited to office workers downtown and family-friendly deals in suburban areas.
     - Local Partnerships: Establish partnerships with nearby businesses or events to increase foot traffic, particularly in lower-performing locations.
       
5. **Seasonal Trends**
   **Insights**: Sales increase during the colder months (October to February), peaking in December. Summer months see a slight decrease in sales.
   **Recommendations**:
     - Seasonal Offerings: Introduce seasonal drinks and snacks to align with customer preferences during colder months (e.g., hot chocolate, holiday-themed beverages).
     - Summer Specials: Offer cold beverages and light snacks during the summer to attract customers seeking refreshment.
       
6. **Time-of-Day Sales Trends**
   **Insights**: Sales are highest in the morning and late afternoon, with a dip during mid-afternoon and late evening.
   **Recommendations**:
     - Targeted Promotions: Create time-specific promotions, such as a “Morning Coffee Deal” or “Afternoon Snack Combo,” to boost sales during slower periods.
     - Happy Hours: Implement happy hour discounts in the late afternoon to attract customers during the lull before the evening rush.
       
7. **Product Size Preferences**
   **Insights**: Regular size is the most popular, followed by large. Small sizes have the least demand.
   **Recommendations**:
     - Promote Larger Sizes: Encourage customers to upgrade to larger sizes with slight discounts or loyalty rewards.
     - Evaluate Small Sizes: Consider reducing or optimizing small size offerings based on demand to minimize waste and increase efficiency.
       
8. **Day-of-Week Sales Trends**
   **Insights**: Sales are generally higher from Monday to Friday, with a notable peak on Fridays. Saturdays also see significant sales.
   **Recommendations**:
     - Weekday Specials: Introduce weekday specials to drive traffic, such as “Two-for-Tuesday” deals or “Midweek Mornings” promotions.
     - Weekend Events: Host events or introduce weekend-exclusive menu items to increase customer visits on Saturdays and Sundays.
       
9. **Customer Purchase Behavior**
   **Insights**: Customers tend to make larger purchases in the mornings and late afternoons, likely purchasing coffee and breakfast items or afternoon snacks.
   **Recommendations**:
     - Morning Combos: Offer breakfast combos including coffee and a pastry at a discounted rate to encourage larger purchases.
     - Afternoon Incentives: Provide incentives for afternoon purchases, such as a free cookie with any drink after 2 PM.
       
10. **Revenue and Transaction Insights**
    **Insights**: Total revenue generated is approximately $800,000, with an average transaction amount of $6.50.
    **Recommendations**:
      - Increase Average Transaction Value: Introduce bundling options and loyalty programs to encourage customers to spend more per visit.
      - Monitor Trends: Regularly review sales and transaction data to identify new opportunities for increasing revenue and optimizing product offerings.
        
11. **Product Type Effectiveness**
    **Insights**: Brewed coffee and lattes are the most effective in driving sales, contributing significantly to total revenue.
    **Recommendations**:
      - Highlight Bestsellers: Promote the most popular coffee options prominently on the menu and in marketing materials.
      - Introduce New Variants: Experiment with new flavors or limited-edition variants to keep the menu fresh and attract repeat customers.
        
12. **Sales by Hour of the Day**
    **Insights**: Morning (7-10 AM) and late afternoon (3-6 PM) are the busiest times, while mid-afternoon and late evening show lower sales.
    **Recommendations**:
      - Optimize Store Hours: Adjust store hours if necessary to maximize sales during peak times and reduce operational costs during slower periods.
      - Time-Based Discounts: Offer discounts or specials during slower hours to increase traffic and sales.

## Results
The results of the analysis are presented in the Excel file under the "Dashboard" sheet. I also added a slicer, so you can filter the data by different criteria.
