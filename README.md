# Diamond Quality vs. Price Tradeoff

**🧠 Overview:** 
This project investigates the relationship between diamond quality attributes—namely, cut, color, and clarity—and the price per carat, aimed at guiding first-time or uninformed diamond buyers in making smart, budget-conscious decisions. Using data visualization and analytical techniques, we help identify combinations that deliver optimal visual quality for cost, enabling data-backed purchases rather than brand-driven decisions.

**📊Data:**
The project uses the Diamonds Dataset from Kaggle, containing information about around 54,000 individuals. This dataset includes fields such as carat, cut, color, clarity, depth, table, price, x (length), y (width), and z (depth).

**🛠️ Method & Tools:**

- **✅ Data Cleaning & Preparation:** Removed duplicates, checked for nulls, created price_per_carat column.
- **🔍Exploratory Data Analysis:** Density plots and histograms for price/carat patterns
- **🔥 Heatmaps:** Visualized mean price/carat across combinations (e.g., clarity × color, cut × clarity)

**⚠️ Key challenges:**

- **Pricing complexity:** Diamond pricing is non-linear and influenced by multiple overlapping quality dimensions.
- **Perceived vs. actual value:** A higher price does not always equate to a perceptible increase in quality.
- **Consumer knowledge gap:** Many buyers lack understanding of how cut, clarity, and color interact to influence price.
- **Feature overlap:** Similar combinations (e.g., VS1 vs. VS2) can behave differently in pricing due to brand or market factors.

📈 Impact & Insights:

- **💎 Best Value Combo:** cut: "Ideal," color: E, clarity: SI1 or VS2.
- **🔍 Overrated Grades:** saw the highest global and U.S. layoff volume.
- **🎯 Premium Cut Insight:** Ideal cut often outperforms Premium in value and sparkle.
- **💸 Smart Trade-Off:** Going from VVS1 to VS2 or E to G can reduce costs by up to 30% with minimal visible difference.

**📌 Recommendations:**
- Educate consumers on purchasing diamonds based on their clarity, color, and cut.
- The best option to purchase a diamond is to buy the one that has “Ideal” cut with color D or E and any clarity.
- Avoid D color unless paired with IF clarity for investment purposes.
