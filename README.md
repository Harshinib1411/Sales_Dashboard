# Sales_Dashboard_creation
Amazon Product Review Dashboard is an interactive Power BI visualization created to analyze Amazon product listings and user reviews. The dashboard highlights key metrics such as product ratings, pricing (actual vs discounted), user engagement, and top-performing categories. With dynamic slicers and KPIs.


# 📊 Amazon Product Review Dashboard (Power BI)

This interactive Power BI dashboard visualizes Amazon product data to uncover insights about product pricing, discounts, user ratings, and customer reviews. It enables dynamic filtering and comparison across product categories to help understand performance, popularity, and pricing strategies.

---

## 📁 Dataset Overview

The dataset includes the following key fields:

| Column Name | Description |
|-------------|-------------|
| `product_id` | Unique ID of the product |
| `product_name` | Name of the product |
| `category` | Product category |
| `actual_price` | Original price of the product |
| `discounted_price` | Price after discount |
| `discount_percentage` | Calculated discount percentage |
| `rating` | User rating (out of 5) |
| `rating_count` | Number of ratings received |
| `user_id` | ID of the reviewer |
| `user_name` | Name of the reviewer |
| `review_id` | Unique ID of the review |
| `review_title` | Short summary of the review |
| `review_content` | Detailed review content |
| `img_link` | Product image link |
| `product_link` | Link to the product on Amazon |

---

## 🎯 Dashboard Goals

- Compare actual and discounted prices across products.
- Analyze average rating by product and category.
- Monitor user engagement through review counts and rating counts.
- Display key KPIs such as average rating and user count.
- Provide category-level insights with filtering capabilities.

---

## 📊 Features of the Dashboard

### 🔹 KPI Cards
- **Average Rating** (e.g., 2.84)
- **Count of Unique Users** (e.g., 15)
- **Most Frequently Reviewed Product** (e.g., FanHeaters)

### 🔹 Visualizations
- **Bar Chart**: Average Rating by Product
- **Column Chart**: Actual Price vs. Discounted Price Comparison
- **Slicers**: 
  - Filter by Product Category
  - Filter by Rating Range

### 🔹 Interactivity
- Hover tooltips for deeper insights
- Dynamic filtering with slicers
- Real-time metric recalculation on filter change

## 🛠 Tools Used

- **Power BI Desktop**: for dashboard creation
- **Microsoft Excel**: for minor data preprocessing

