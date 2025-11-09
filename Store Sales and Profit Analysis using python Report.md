### **Store Sales and Profit Analysis using Python Report**





#### **Objective:**

The primary goal of this analysis is to evaluate sales and profit performance across multiple dimensions — including time, product categories, and customer segments — to identify profitability patterns, cost efficiencies, and potential areas for business growth.

This project provides a data-driven foundation for decision-making related to pricing, customer targeting, and product portfolio optimization.





#### **Data Overview:**

The dataset used in this analysis contains retail transaction-level information.

It includes columns such as:

Order ID, Order Date, Ship Date

Customer Segment (Consumer, Corporate, Home Office)

Category and Sub-Category

Sales, Quantity, Discount, and Profit

The dataset represents transactional sales data of a retail store over a period of time.





#### **Data Preparation \& Cleaning:**

**Key data preprocessing steps included:**



* Reading the dataset using pandas.read\_csv() with correct encoding to prevent Unicode errors.



* Parsing date columns (Order Date, Ship Date) into proper datetime formats.



* Checking for missing values — no significant null entries were found.



**Feature Engineering:**



* Extracted Order Month from Order Date for time-based trend analysis.



* Computed Sales-to-Profit Ratio to evaluate efficiency across customer segments.









#### **Exploratory Data Analysis (EDA):**

**A. Monthly Sales Trend:**

* The analysis of monthly sales highlighted seasonal fluctuations, with certain months showing spikes in demand — possibly linked to promotions or festive seasons.
* This trend helps in identifying sales seasonality and planning inventory or campaigns accordingly.



**B. Sales by Category**

* A pie chart visualized total sales distribution across categories:
* Technology and Office Supplies showed strong revenue contributions.
* Furniture recorded high sales volume but moderate profitability, indicating potential pricing or cost optimization opportunities.



**C. Sales by Sub-Category**

* Sub-category analysis (like Phones, Chairs, Binders, etc.) revealed granular insights into which products drive the most sales and profit.
* Technology-related sub-categories such as Phones and Accessories dominated sales figures.



**D. Monthly Profit Trend**

* Monthly profit visualization displayed patterns similar to sales but with greater variability, suggesting differing discount structures, cost margins, or seasonal promotions.



**E. Profit by Category**

* While Technology generated higher profits, Furniture showed relatively lower profit margins, highlighting the need for margin improvement in high-volume product lines.



**F. Profit by Sub-Category**

* Certain sub-categories with lower overall sales demonstrated disproportionately high profitability, revealing potential for strategic promotion or product mix adjustments.







#### **Customer Segment Analysis:**

A comparative study of sales and profit by Customer Segment (Consumer, Corporate, Home Office) revealed:

| Segment     | Total Sales | Total Profit       | Sales-to-Profit Ratio | Insight                       |

| ----------- | ----------- | ------------------ | --------------------- | ----------------------------- |

| Consumer    | High        | Moderate           | 8.66                  | High sales, low profit margin |

| Corporate   | Moderate    | Good               | 7.68                  | Balanced segment              |

| Home Office | Lower       | Highest efficiency | 7.13                  | Most profitable               |



**Interpretation:**

* The Consumer segment contributes the most to revenue but earns less profit per sale (low efficiency).
* The Home Office segment generates fewer sales but maintains a stronger profit margin, indicating better pricing power or cost efficiency.







#### **Key Metric: Sales-to-Profit Ratio:**

This metric quantifies how much sales revenue is required to generate ₹1 of profit:



Sales-to-Profit Ratio=Total Sales/Total Profit

&nbsp;	​

Lower ratio = better profitability

Higher ratio = lower efficiency





**interpretation:**

* Consumer: ₹8.66 sales per ₹1 profit → Low margin
* Corporate: ₹7.68 sales per ₹1 profit → Moderate margin
* Home Office: ₹7.13 sales per ₹1 profit → Best margin performance







#### **Visualization Insights:**

* Several visualizations (using Plotly Express and Graph Objects) provided interactive, presentation-ready charts:
* Donut Charts: For category-wise and segment-wise analysis (with dark themes for contrast).
* Bar Charts: To compare Sales vs Profit across segments.
* Trend Charts: For monthly performance.
* These visuals make it easier to identify performance gaps, category strengths, and sales inefficiencies.







#### **Business Insights:**

* The Consumer segment drives most of the top-line revenue but at a lower profit rate, likely due to higher discounts or product mix.
* The Home Office segment should be prioritized for strategic marketing, as it offers the best ROI per sale.
* Technology products are profitable and should continue to be emphasised.
* Furniture needs margin improvement through cost control, vendor negotiation, or targeted promotions.
* Consistent monthly fluctuations imply opportunities for inventory optimization and seasonal campaign planning.







#### **Recommendations:**

**Enhance Profit Margins:**

Re-evaluate pricing for Consumer segment products.

Focus on Home Office clients for premium offerings.



**Category Optimization:**

Increase investment in high-margin sub-categories (e.g., Technology accessories).

Reduce or restructure low-profit items under Furniture.



**Customer Strategy:**

Personalize promotions for Corporate and Home Office segments to drive higher retention.

Introduce loyalty incentives for the Consumer segment to balance volume with profit.



**Forecasting:**

Use monthly sales trends for predictive planning and inventory forecasting.









#### **Conclusion:**

* The Store Sales and Profit Analysis offers a clear picture of performance across multiple business dimensions.
* It emphasizes that revenue growth must be balanced with profitability efficiency to ensure sustainable success.
* While Consumer sales dominate, the Home Office segment and Technology category provide the best profit leverage.
* By applying data-driven insights from this analysis, the store can strategically align pricing, marketing, and product management to maximize profitability and enhance customer value.
