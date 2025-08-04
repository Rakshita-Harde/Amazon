# Amazon
# 🛍️ Amazon Product Data Analysis
- This project explores and analyzes an Amazon product dataset to uncover insights into product pricing, discounts, ratings, and popularity. The analysis helps understand customer preferences, seller strategies, and product trends on the platform.

# 📁 Dataset Overview
**product_id :** Unique ids for product
**product_name :**	Name of the product
**category :** categories of the product (Computers&Accessories, Accessories&Peripherals, headphones etc)
**discounted_price :**	Final price after discount (₹)
**actual_price :**	Original price before discount (₹)
**discount_percentage	:** Discount applied on the product (%)
**rating :** Average customer rating (0–5 scale)
**rating_count :**	Number of customers who rated the product
**about_product :** Product information and it's compatibility 
**user_id :** Unique ids for user 
**user_name :** Names of users who buys the perticular product 
**review_id :** Review ids are generated for unique review
**review_title :** Tiltel of review by coustomer
**review_content :** What people says about the product
**img_link :** link of the image whic user posted for the review 
**product_link :** link of the actual product 

# 📌 Tools & Libraries Used
- Python 
- Pandas – data manipulation
- Matplotlib & Seaborn – data visualization
- Jupyter Notebook – interactive data exploration

# 📷 Visual Insights
- Histogram of Discount Percentages
- Bar Chart of Top 10 Most Rated Products
- Distribution of Ratings & Prices
- All charts are clean, color-coded, and labeled for easy understanding.

# Steps
**1. Data Import 🔃**
- Dataset was successfully loaded using the pandas library in Jupyter Notebook.
**2. Data Preparation 🔐**
- Converted colums in clean for for apply various methods.
**3. Exploratory Data Analysis (EDA)**
Counted the frequency of each device type (Smart TV: 870).
Calculated the average completion rate for each platform.
Identified and listed content in order of increasing completion rate.
**4. Data Visualization 📊**
Histogram: Analyzed the distribution of the completion_rate and watch_time_minutes variables.
Heatmap: Explored correlations, especially between watch time and completion rate.
Histplot: Visualized the frequency of watchtime distributon .
