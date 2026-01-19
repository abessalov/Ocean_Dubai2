# Dubai Real Estate Price Prediction Challenge

## Overview

This repository contains a comprehensive machine learning system for predicting real estate prices in Dubai's property market. The system analyzes both rental and sales markets using XGBoost models trained on millions of historical transactions combined with external economic indicators.

**For detailed code functionality, algorithms, and technical documentation, see [CODE_DESCRIPTION.md](CODE_DESCRIPTION.md).**

## Quick Start

1. Install dependencies: `pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost jupyter`
2. Run notebooks in order (see Files description below)
3. View results in `Ocean_Dubai.pdf` or `Ocean_Dubai.md`

## Files description

- **README.md** - Project overview and quick start guide.
- **CODE_DESCRIPTION.md** - Comprehensive code functionality documentation with algorithms, usage examples, and technical details.
- **_startup.ipynb** - Central library imports executed in every notebook.
- **create_pdf.ipynb** - Converts markdown analysis to PDF format.
- **feats_rents.ipynb** - Feature Engineering for Rental market (~5.5M transactions).
- **feats_sales.ipynb** - Feature Engineering for Sales market (~1M transactions).
- **stat_rents.ipynb** - Statistical analysis and EDA for Rentals.
- **stat_sales.ipynb** - Statistical analysis and EDA for Sales.
- **model_rents.ipynb** - XGBoost model training for Rental prices.
- **model_sales.ipynb** - XGBoost model training for Sales prices.
- **eval.ipynb** - Model evaluation and investment opportunity identification.
- **Ocean_Dubai.md** - Comprehensive analysis report with all findings.
- **Ocean_Dubai.pdf** - PDF version of the analysis report.

## Key Features

- **Data Processing**: Handles millions of transactions with advanced cleaning and standardization
- **External Data Integration**: Incorporates CPI, GDP, population, tourism, and 389 World Bank indicators
- **Machine Learning**: Separate XGBoost models per property type for optimal accuracy
- **Performance**: Best MAPE of 9.86% (Land rentals), most types achieve 10-25% MAPE
- **Business Value**: Identifies undervalued properties for investment opportunities

## Model Performance

### Rental Market
- Building: 15.23% MAPE
- Land: 9.86% MAPE  
- Unit: 25.06% MAPE
- Virtual Unit: 42.65% MAPE

### Sales Market
- Building: 10.76% MAPE
- Land: 43.40% MAPE
- Unit: 13.85% MAPE

## Documentation

- 📚 [CODE_DESCRIPTION.md](CODE_DESCRIPTION.md) - Detailed technical documentation
- 📊 [Ocean_Dubai.md](Ocean_Dubai.md) - Full analysis report with visualizations
- 📄 Ocean_Dubai.pdf - PDF report (47MB with all charts) 
