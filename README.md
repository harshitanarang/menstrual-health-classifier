# Menstrual Health Classifier

The Menstrual Health Classifier is a machine learning-based tool designed to help analyze and predict menstrual health conditions based on user input. It aims to support awareness, promote early detection of potential issues, and empower individuals to track their reproductive health effectively.

## 🚀 Features

- Predicts potential menstrual health conditions using physiological and behavioral inputs.
- Supports classification of multiple conditions (e.g., PCOS, PMS, irregular cycles).
- Built with machine learning for accurate and scalable analysis.
- Clean, modular codebase for easy customization and extension.
- Optional web interface for user-friendly interaction.

## 🧠 Technologies Used

- **Programming Language:** Python  
- **Machine Learning Libraries:** scikit-learn   
- **Data Handling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Web Interface (optional):**  Flask


## 📖 Overview

This project uses machine learning to classify menstrual cycle irregularities. It aims to support menstrual health awareness by analyzing symptoms and patterns using health indicators and cycle characteristics.

---


## 📊 Dataset

The model is trained on a curated dataset that includes features such as:

- Cycle length and regularity  
- Flow intensity  
- Hormonal symptoms  
- Lifestyle and stress indicators  
- Age and BMI  

*Note: All personal health data is anonymized and used solely for educational and research purposes.*


## 🏗️ Model Details

- **Model Type:** ensemble(Random Forest)
- **Performance:** 96.6 accuracy on test data  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score 
- **Preprocessing:** Missing value imputation, normalization, feature encoding,outliers handling

## 🔧 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/harshitanarang/menstrual-health-classifier.git
cd menstrual-health-classifier
pip install -r requirements.txt



## 🧪 Usage

### Predict via Command Line

```bash
python src/predict.py --input sample_input.json```

⚠️ Ethical Disclaimer
This tool is intended for educational and informational purposes only.
It does not replace professional medical advice, diagnosis, or treatment.
Always consult with a qualified healthcare provider for any medical concerns.


📝 License
This project is licensed under the MIT License.
See the LICENSE file for details.


🙌 Acknowledgments
Open-source contributors and dataset providers

Medical experts for domain knowledge

Kaggle for dataset support
