# (2023) Data Mining of Real Estate in Moscow  
**Project Type:** Freelance Data Science Consulting Project  
**Programming Language:** Python 3 (XGBoost, scikit-learn, BeautifulSoup, CloudScraper, NLP regex)  
**Core Components:** [Data Pipeline](https://github.com/ResearchMachine/commercial-project-ml-mvp-insight-in-real-estate-moscow/blob/main/preprocessing/run_preprocessing.ipynb) | [Valuation Engine](https://github.com/ResearchMachine/ml-mvp-insight-in-real-estate-moscow/blob/main/modeling/run_modeling_clean.ipynb)  

### I. Project Objectives
* Developed automated web scraping pipeline for CIAN.ru commercial property listings with structured data output
* Conducted comprehensive exploratory analysis of Moscow's commercial real estate market dynamics
* Designed and validated an algorithmic valuation approach in collaboration with domain experts

### II. Key Achievements
* Implemented production-grade data extraction system processing 1,500+ active listings from Russia's leading real estate platform
* Reduced noise in target property pool by 40% (≈900 cleaned listings) through advanced NLP text analysis of listing content
* Engineered machine learning system identifying top 2% most undervalued commercial properties (30/day) using professional valuation parameters
* Delivered 3 expert-verified high-value investment opportunities during MVP phase with actionable pricing insights

### III. Technical Implementation  
**Valuation Algorithm Methodology:**  
* Price prediction model trained on market-average segment (XGBoost regression) with subsequent anomaly detection via residual analysis (price_fact - price_pred)  
* Feature engineering limited to professional valuation factors (property characteristics, geospatial features) to prevent overfitting on listing metadata  
* Implemented quality control mechanisms for problematic listings (fraudulent, distressed properties) requiring expert review  

**Operational Considerations:**  
* Model sensitivity to market-specific filters requiring domain knowledge for optimal configuration  
* Trade-off analysis between listing quality (construction year filters) and opportunity volume

  ![image](https://github.com/ResearchMachine/commercial-project-ml-mvp-insight-in-real-estate-moscow/assets/70639823/67974aa5-54b5-41b3-a3f4-8258d3fea1e1)  
Figure: Geographic distribution of commercial properties in Moscow (CIAN dataset)
