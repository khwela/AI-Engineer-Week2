# Water Potability Prediction Project
## SDG 6: Clean Water and Sanitation

This project uses machine learning to predict whether water is safe to drink based on various water quality metrics. It directly contributes to UN Sustainable Development Goal 6: Ensure availability and sustainable management of water and sanitation for all.

### Project Overview
The project implements a Random Forest classifier to predict water potability using the following water quality parameters:
- pH value
- Hardness
- Total dissolved solids
- Chloramines
- Sulfate
- Conductivity
- Organic carbon
- Trihalomethanes
- Turbidity

### Setup Instructions
1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open `water_potability.ipynb` and run the cells in sequence

### Project Structure
- `water_potability.ipynb`: Main Jupyter notebook containing the analysis and model
- `requirements.txt`: List of Python package dependencies
- `README.md`: Project documentation

### Model Features
- Data preprocessing and cleaning
- Exploratory data analysis with visualizations
- Random Forest model training and evaluation
- Feature importance analysis
- Prediction function for new water samples

### Dataset
The dataset contains water quality metrics and potability labels for thousands of water samples. The target variable is binary:
- 1: Potable (safe to drink)
- 0: Not potable (unsafe to drink)

### Results
The model evaluates water potability based on multiple parameters and provides:
- Binary classification (Potable/Not Potable)
- Confidence score for predictions
- Feature importance analysis
- Model performance metrics

### Contributing
Feel free to fork this repository and submit pull requests for improvements.

### License
This project is open source and available under the MIT License.