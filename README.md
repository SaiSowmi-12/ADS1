# Multimodal Machine Learning for Forecasting Global Suicide Rates

## 📊 Project Description
This project aims to forecast global suicide rates by integrating WHO suicide statistics with World Bank socioeconomic and demographic indicators. Machine learning models such as Random Forest, LightGBM, and CatBoost are used to generate forecasts and identify key influencing factors through SHAP analysis.

## 📁 Dataset Description
- **Sources**: WHO Global Health Observatory, World Bank Open Data  
- **Coverage**: 1980–2017, 120 countries  
- **Key Features**: suicides_per_100k, GDP per capita, unemployment, population, healthcare spending  
- **Records**: ~3000+ after cleaning and merging

## 📂 Project Structure
/data/raw/ -> Original WHO and World Bank datasets
/data/processed/ -> Cleaned and merged dataset
/notebooks/ -> Jupyter notebooks for analysis and modeling
/models/ -> Saved trained ML models
/results/ -> Evaluation metrics, forecast outputs, SHAP plots

## 🧭 How to Reproduce
1. Clone the repository.  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3.Run the model training notebook or script:
python train_model.py
4.Outputs (metrics, plots) will be generated in the /results/ folder.
Outputs (metrics, plots) will be generated in the /results/ folder.

🧾 Version Control

Repository: GitHub (private or public)

Changes tracked through commits with version tags.

Branches used for experimental features and model improvements.

✍️ Author & Acknowledgements

Author: Sowmiya Shanmuganathan (8925GCUZ)

Dataset Providers: WHO Global Health Observatory, World Bank Open Data

Tools Used: Python, LightGBM, CatBoost, scikit-learn, SHAP

🔐 Ethics & Data Usage

All datasets are publicly available and aggregated — no personal identifiable data used.

Proper attribution and citation are maintained.

📝 License

This project is for academic and research purposes only
