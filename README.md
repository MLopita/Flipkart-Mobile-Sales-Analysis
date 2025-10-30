# Flipkart Mobile Data Analysis – Power BI Dashboard

### Tools Used
Microsoft Excel – Preliminary data cleaning (null handling, standardization)  
Microsoft Power BI – Data modeling, DAX calculations, and interactive dashboard design  

### Objective
Analyze smartphone listings from Flipkart to uncover insights into brand presence, pricing tiers, customer ratings, and discount trends.  
The goal was to support pricing and marketing strategies by visualizing competitive positioning, profit margins, and consumer preferences.  

### Project Description
This project utilizes scraped Flipkart mobile data containing 4,689 smartphone listings across 17 brands.  

Price segmentation was performed to classify phones into:  
• Low Range (< ₹10K)  
• Mid Range (₹10K–₹25K)  
• Premium (> ₹25K)  

Excel was used for initial cleaning and preprocessing.  
Power BI was used for data modeling, DAX measures (Average Rating, Avg Discount %, Profit Margin), and dashboard design with filters and visuals.  

### Key Visuals in Dashboard  

| Visual Type | Description |
|--------------|-------------|
| KPI Cards | Total mobiles, Avg Selling Price, Avg Rating, Avg Discount %, Total Brands |
| Pie Chart | Distribution of phones by price segment (Low, Mid, Premium) |
| Bar Chart | Original Price vs Selling Price comparison by brand |
| Stacked Bar Chart | Brand-wise model count by price tier |
| Column Chart | Most common RAM + Storage combinations |
| Donut Chart | Total model count by brand |
| Line + Scatter Chart | Total sales by color |
| Slicers | Brand, Price Tier, and Color for interactive filtering |

### Insights and Impact  

• Samsung leads in listings, offering phones across all three price segments.  
• Mid-range phones (₹10K–₹25K) dominate the market with 42% share.  
• 6 GB RAM + 128 GB storage emerged as the most common configuration.  
• Black and Blue were the most frequent color variants.  
• Profit gap of up to 40% observed between original and selling prices for certain models.  
• Brands like POCO and Motorola offered the highest average discounts, reflecting aggressive pricing strategies.  

### Dashboard Preview
![Flipkart Power BI Dashboard](./83696ae0-4cab-43ff-8f72-1a40658f56c9.png)

### How to Use
1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/Flipkart-Mobile-Data-Analysis.git
   ```
2. Open the .pbix file in Power BI Desktop  
3. Explore insights using the interactive filters and visuals  

### Learning Outcomes  
• Hands-on experience in data modeling and visualization with Power BI  
• Understanding of pricing strategy analysis using DAX measures  
• Improved ability to derive business insights from marketplace data  

### Future Enhancements  
• Incorporate time-based price trends (historical data)  
• Add consumer review sentiment analysis  
• Automate data updates using Power BI Dataflows or Python ETL  

### Author  
**Lopita Mishra**  
Aspiring Business Intelligence Analyst  
Location: India  
LinkedIn: [Lopita Mishra](https://www.linkedin.com/in/lopita-mishra)  
Email: lopitamishra@gmail.com  
