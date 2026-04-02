# QUICK START GUIDE
## Olist Delivery Time Prediction Project

Get up and running in 10 minutes!

---

## Step 1: Install Required Packages

```bash
pip install -r requirements.txt
```

Or install individually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## Step 2: Verify Data Files

Ensure these files are in the `Olist Dataset (1)` folder:

- olist_customers_dataset.csv
- olist_geolocation_dataset.csv
- olist_orders_dataset.csv
- olist_order_items_dataset.csv
- olist_order_payments_dataset.csv
- olist_order_reviews_dataset.csv
- olist_products_dataset.csv
- olist_sellers_dataset.csv
- product_category_name_translation.csv

---

## Step 3: Run the Analysis

### Option A: Jupyter Notebook (Recommended)
```bash
jupyter notebook Olist_Delivery_Analysis_Project.ipynb
```
Then click "Run All" from the Cell menu.

### Option B: VS Code
1. Open `Olist_Delivery_Analysis_Project.ipynb` in VS Code
2. Select Python kernel
3. Run all cells sequentially

---

## Step 4: View Results

The notebook will:
- Load and analyze 96,000+ orders
- Generate 30+ visualizations
- Train 5 machine learning models
- Output predictions and recommendations

**Total Runtime:** 5-10 minutes (depending on hardware)

**Output Files:** 
- `final_df_engineered.csv` - Processed dataset

---

## What You'll Get

1. **Exploratory Data Analysis**
   - Delivery performance metrics
   - Geographic patterns
   - Customer behavior insights

2. **Predictive Model**
   - 80% accuracy in predicting delivery time
   - Feature importance analysis
   - Business recommendations

3. **Actionable Insights**
   - Key drivers of delivery performance
   - Strategic recommendations
   - ROI projections

---

## Troubleshooting

**Problem:** Module not found error  
**Solution:** Run `pip install -r requirements.txt`

**Problem:** File not found error  
**Solution:** Update file paths in first cells to match your directory structure

**Problem:** Kernel crashes  
**Solution:** Reduce dataset size or increase available RAM

**Problem:** Visualizations not showing  
**Solution:** Add `%matplotlib inline` at the beginning

---

## Next Steps

After running the analysis:

1. Review the **Executive Summary** section
2. Examine **visualizations** for insights
3. Check **model performance** metrics
4. Read **business recommendations**
5. Share findings with stakeholders

---

## File Overview

- `Olist_Delivery_Analysis_Project.ipynb` - Main analysis (COMPREHENSIVE)
- `README.md` - Detailed project documentation
- `EXECUTIVE_SUMMARY.md` - High-level business summary
- `requirements.txt` - Python dependencies
- `Draft report.pdf` - Initial project report
- `EDA & Feature engineering.ipynb` - Original exploration

---

## Support

For questions or issues:
1. Check README.md for detailed documentation
2. Review code comments in the notebook
3. Contact the Data Science team

---

**Ready to start? Run the notebook and explore the insights!**
