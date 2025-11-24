# (2023) Data Mining of Real Estate in Moscow (Part of Commercial Segment)  
**NDA:** segment parameters, property links  
**Project Type:** Freelance Data Science   
**Coding Language:** Python 3 (XGBoost, scikit-learn, BeautifulSoup, CloudScraper, NLP regex)  
**Solution Code:** [Data Pipeline](https://github.com/ResearchMachine/commercial-project-ml-mvp-insight-in-real-estate-moscow/blob/main/preprocessing/run_preprocessing.ipynb) | [Valuation Engine](https://github.com/ResearchMachine/ml-mvp-insight-in-real-estate-moscow/blob/main/modeling/run_modeling_clean.ipynb)  


### I. Project Objectives
* Developed automated web scraping pipeline for CIAN.ru commercial property listings with structured data output in special segment (NDA)
* Designed and validated an algorithmic valuation approach in collaboration with domain experts

### II. Key Achievements
* Implemented production-grade data extraction system processing 1,500+ active listings from Russia's leading real estate platform
* Reduced noise in target property pool by 40% (≈900 cleaned listings) through advanced NLP text analysis of listing content
* Engineered machine learning system identifying top 2% most undervalued commercial properties (30/day) using professional valuation parameters
* Delivered 3 expert-verified high-value investment opportunities during MVP phase with actionable pricing insights

### III. Technical Implementation  
**Valuation Algorithm Methodology:**  
* Price prediction model trained on market-average segment (XGBoost regression) with subsequent anomaly detection via residual analysis (price_fact - price_pred)  
* Feature engineering limited to professional valuation market factors (no user actions, only property characteristics, geospatial features, and etc.) to prevent overfitting of prediction model 
* Model sensitivity to market-specific filters requiring domain knowledge for optimal configuration 

**Solution Code:** [Data Pipeline](https://github.com/ResearchMachine/commercial-project-ml-mvp-insight-in-real-estate-moscow/blob/main/preprocessing/run_preprocessing.ipynb) | [Valuation Engine](https://github.com/ResearchMachine/ml-mvp-insight-in-real-estate-moscow/blob/main/modeling/run_modeling_clean.ipynb)  

<img width="533" height="307" alt="image" src="https://github.com/user-attachments/assets/58d4686f-3f84-41ef-bfa2-5701d5911e7d" /> 
**Figure: Geographic distribution of commercial properties in Moscow (CIAN dataset)**





  ## License

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

This project is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

