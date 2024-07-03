# Laptop Price Prediction

This project aims to predict the prices of laptops using various features such as brand, processor type, RAM size, and more. The model is built using the XGBoost regressor, which is a powerful and efficient implementation of gradient boosting. The project includes data cleaning, feature engineering, model training, hyperparameter tuning, and evaluation.

## Dataset

The dataset used for this project contains various features related to laptops, including:

- `brand`: Brand of the laptop
- `processor_brand`: Brand of the processor
- `processor_name`: Name of the processor
- `ram_gb`: RAM size in GB
- `ram_type`: Type of RAM
- `os`: Operating system
- `os_bit`: OS bit (32 or 64)
- `graphic_card_gb`: Size of the graphic card in GB
- `Touchscreen`: Whether the laptop has a touchscreen (Yes/No)
- `msoffice`: Whether the laptop has MS Office pre-installed
- `weight`: Weight of the laptop
- `processor_gnrtn`: Processor generation
- `ssd`: SSD storage in GB
- `hdd`: HDD storage in GB
- `warranty`: Warranty period in years
- `rating_stars`: Customer rating in stars
- `Price`: Price of the laptop (target variable)

The primary model used in this project is XGBoost Regressor, which was selected for its efficiency and performance. The model's effectiveness is measured using MAE and RMSE metrics.

1. Clone the repository:

```bash
git clone https://github.com/yourusername/laptop-price-prediction.git
cd laptop-price-prediction
