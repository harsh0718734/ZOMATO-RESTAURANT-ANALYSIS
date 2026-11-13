# Zomato Restaurant & Menu Analysis 

## 📌 Project Overview
This data analytics project focuses on the end-to-end processing, cleaning, and multidimensional analysis of a production-scale Zomato food delivery dataset. The primary objective was to transform a high-volume, noisy data payload into an executive-ready business intelligence matrix. 

By applying strict data-cleansing protocols and deploying hierarchical relational modeling within Microsoft Excel, this project isolates critical operational performance indicators (KPIs) to map local culinary trends, evaluate delivery network latencies, and pinpoint high-velocity spending hotspots across multiple major metropolitan cities.

---

## 🛠️ Data Cleansing, Transformation & Validation
Raw web-scraped logistical data contains significant systemic anomalies that skew statistical aggregation. Before executing any analytical calculations, the following data-engineering workflow was implemented to ensure structural data integrity:

* **De-duplication Engine:** Executed data de-duplication models to identify and completely strip out 22,127 exact, repeated row entries, reducing a chaotic raw payload of 123,657 listings down to a validated, unique tracking architecture.
* **Filter Matrix Optimization:** Filtered out null inputs, trailing white spaces, and empty records within the categorical columns, locking down a crisp, optimized operational core of 31,047 active transactional rows within the final analysis space.
* **Data Type Cast Conversions:** Standardized the `PRICES` and `VOTES` fields by casting them strictly into uniform numerical data structures, converting text traps into actionable mathematical parameters capable of running sum and average expressions.
* **Anomalous System Purging:** Cleaned up drop-down filter menus by systematically unchecking blank system flags, guaranteeing a spotless interface for business stakeholders.

---

## 📊 Relational Database Architecture & KPI Formulation
To extract actionable market insights, the unique dataset rows were structured inside an advanced, multi-variable Excel Pivot Table hierarchy:

### 1. Hierarchical Row Layout
* **Primary Level (CITY):** Grouped data at the macro level to compare revenue metrics and catalog density between competing major metropolitan markets.
* **Secondary Level (RESTAURANT NAME):** Drilled down inside each city to identify individual brand dominance and isolate premium pricing models from mass-volume street vendors.
* **Tertiary Level (PLACE NAME):** Deep-dived into specific residential zones and micro-neighborhood clusters to discover local geographic consumer density.

### 2. Multi-Variable Value Matrix (KPI Blocks)
Side-by-side analytical columns were constructed to measure total performance across four critical business angles on a single unified line:
* **Sum of PRICES:** Tracks the total financial pricing volume circulating across each municipal marketplace.
* **Count of ITEM NAME:** Calculates menu variety depth to rank which neighborhoods host the most diverse competitive options.
* **Max of DELIVERY RATING:** Pinpoints the absolute peak logistics benchmarks and highest-performing driver networks in the city.
* **Min of DINING RATING:** Establishes the absolute baseline for base customer satisfaction, allowing management to flag under-performing food zones instantly.

---

## 🎛️ Interactive Slicers & Visual Enhancements
To transition the static table arrays into an active, visual exploration dashboard, multi-level filter controls and visual formatting were integrated across the workspace:
* **CUISINE Master Filter:** Placed in cell `A1` to let users slice the entire dashboard instantly by food sector (*Fast Food, Biryani, Beverages, Bakery, etc.*).
* **BEST SELLER Slicer Control:** Placed in cell `A2` to let management instantly toggle between hot-selling flagship items and standard menu configurations with a single click.
* **Conditional Formatting Data Bars:** Applied horizontal green gradient data bars across the Pivot Table metrics to highlight relative market volume and rating differences at a glance.
* **City-Wise Menu Price Volume Pivot Chart:** Built a companion clustered bar chart tracking total menu price volume across all analyzed cities alongside the matrix.

---

## 📈 Strategic Business Insights Uncovered
* **Volume vs. Premium Pricing Power:** The analysis revealed that while certain cities like Hyderabad lead the network in menu listing depth (#1 in total item counts), metro hubs like Mumbai generate a higher total price sum with significantly fewer entries, proving a much higher consumer willingness to pay premium product pricing.
* **Quality Network Stability:** By evaluating maximum delivery thresholds against minimum dining baselines, the data isolates rising secondary markets (like Raipur) that maintain highly stable, top-tier rating networks across the board compared to oversaturated primary markets where base ratings drop as low as 2.8.

