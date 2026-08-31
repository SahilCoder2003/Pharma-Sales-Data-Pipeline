# End-to-End Pharma Sales Data Pipeline

## 📌 Project Overview
This project targets a common issue faced by Direct-to-Consumer (D2C) wellness and pharmaceutical brands: cleaning messy field sales data. Field reports uploaded by medical representatives often contain inconsistent formatting, missing metrics, and data entry errors. 

This automated Python pipeline ingests chaotic regional sales records and outputs structured, clean datasets ready for executive business dashboards.

## 🛠️ Tech Stack & Skills Demonstrated
* **Python** (Core Logic)
* **Pandas** (Datetime standardisation, parsing multi-format strings, handling missing/null records)
* **NumPy** (`np.where` conditional handling to isolate out-of-bound variables and anomalous data entry typos)

## ⚙️ How It Works
1. **Format Unification:** Resolves mixed regional date styles (e.g., `YYYY/MM/DD` and `DD-MM-YYYY`) robustly across older environments.
2. **Data Cleansing:** Eradicates accidental negative unit entries and flags extreme entry outliers (like '9999' typos) to normalize records to regional baseline medians.
3. **Executive Aggregation:** Automatically groups the finalized clean metrics by geographic region for instant analytical updates.
