# Solar Energy Prediction - UK Open Climate Fix Dataset

This project builds a machine learning model (XGBoost) to predict solar energy production using weather and plant metadata from the [Open Climate Fix UK PV Dataset](https://huggingface.co/datasets/openclimatefix/uk_pv/tree/main).

## Setup Instructions

1. **Clone the repository**

```
git clone https://github.com/entl/evolyte-ml-backend
cd evolyte-ml-backend
```

2. **Install dependencies**:
   
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Dataset**:

   The full UK PV dataset is **not included** in this repository due to its large size.

   You can download it from:
   [Open Climate Fix - UK PV Dataset on Hugging Face](https://huggingface.co/datasets/openclimatefix/uk_pv/tree/main)

4. **Run the Jupyter Notebook**:

   Open the `.ipynb` file and run the cells to train and evaluate the model.

   ```bash
   jupyter notebook
   ```

## Notes

- The model uses XGBoost with optimised hyperparameters.
- Only a selected subset of PV plants is used to reduce computation time.
- Preprocessing includes scaling, feature engineering, and smoothing.

