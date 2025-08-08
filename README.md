# 🎯 Sonar Rocks vs Mines Prediction using Logistic Regression

A **machine learning classification project** that predicts whether an object detected by sonar signals is a **rock** or a **mine**. This project implements a **Logistic Regression** model on the classic [Sonar dataset](https://archive.ics.uci.edu/dataset/151/connectionist+bench+(sonar,+mines+vs.+rocks)), demonstrating **end-to-end ML workflow** — from data collection and preprocessing to model evaluation and prediction system creation.

---

## 📌 Project Overview

| Category      | Details                                                                                  |
| ------------- | ---------------------------------------------------------------------------------------- |
| 📊 Dataset    | [UCI Machine Learning Repository - Sonar Dataset](https://docs.google.com/spreadsheets/d/1jKZedVzxT2zuL4pMM2YGbOl3i1F8VSW9WX3usxq0RQ4/edit?usp=sharing)) |
| 📌 Goal       | Predict whether the sonar reading corresponds to a rock (`R`) or a mine (`M`)            |
| ⚙️ Model      | Logistic Regression (Binary Classification)                                              |
| 🧪 Evaluation | Accuracy Score on Training & Testing Data                                                |
| 🛠️ Tools      | Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn                                  |
| 💼 Author     | Samar Ranjit (Undergraduate Research Assistant, Texas State University)                  |

---

## 🚀 Features of This Project

- **Data Loading & Exploration**
  - Loaded CSV dataset directly into Pandas DataFrame
  - Performed statistical summarization and class distribution analysis
- **Data Preprocessing**
  - Separated features (`X`) and target labels (`Y`)
  - Train-test split with stratified sampling to maintain class balance
- **Model Training**
  - Implemented Logistic Regression for binary classification
  - Optimized with Scikit-learn defaults for interpretability
- **Model Evaluation**
  - Accuracy measured on both training and testing sets
  - Validated for generalization capability
- **Predictive System**
  - Created a ready-to-use predictive system that accepts new sonar readings and outputs classification result

---

## 📊 Model Performance

| Dataset  | Accuracy Score |
| -------- | -------------- |
| Training | ~83% ✅        |
| Testing  | ~76% ✅        |

> ⚖️ The model demonstrates reasonable predictive capability given the small dataset size and no heavy hyperparameter tuning.

---

## 📦 Tech Stack & Dependencies

- **Languages:** Python 3.x
- **Libraries:**
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Install dependencies:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
## 📂 Repository Structure

```bash
sonar-rocks-vs-mines/
├── sonar_rocks_vs_mines_prediction.py  # 📜 Main script (exported from Colab notebook)
├── Sonar_Data.csv                      # 📊 Dataset file (place in project folder or update path)
├── requirements.txt                    # 📦 Python dependencies
├── README.md                           # 📄 Project documentation
└── .gitignore                          # 🔒 Ignore venv, cache files
```
---
### 🛠️ How to Run

## 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/sonar-rocks-vs-mines.git
cd sonar-rocks-vs-mines
```

## 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

## 3️⃣ Run the Script

```python
python sonar_rocks_vs_mines_prediction.py
```

Or open the notebook in Google Colab:

1. Upload the .ipynb notebook to Colab.

2. Mount Google Drive if the dataset is stored there.

3. Run all cells.
---

## 📚 Key Learnings from This Project

Through this project, I learned to:

- **Load and explore datasets** efficiently using Pandas.  
- **Understand dataset structure** and statistical distributions before modeling.  
- **Split data with stratification** to ensure balanced class distribution in train/test sets.  
- **Implement and train Logistic Regression** for binary classification problems.  
- **Evaluate model performance** with training and testing accuracy to identify overfitting or underfitting.  
- **Build a predictive system** that works on new input data.  
- **Write reproducible, clean, and well-documented ML code** for public repositories.
---

## 🔍 Example Prediction

```python
input_data = (0.0117,0.0069,0.0279,...,0.0062,0.0026,0.0052)
```
✅ Output:

```bash
The object is a Rock
```
or,
```bash
The object is a Mine
```
---
## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
---

## 🙋‍♂️ About the Author

**Samar Ranjit**  
📍 Undergraduate Research Assistant | Texas State University  
🔭 Exploring ML, AI, and Geospatial Analytics in Agriculture  
💡 Enthusiastic ML learner, actively seeking opportunities to collaborate on innovative projects  
🔗 [LinkedIn](https://www.linkedin.com/in/samarranjit)  
📨 Email: [samar.ranjit@txstate.edu](mailto:samarranjit@txstate.edu)  

---

## 🌟 Want to Collaborate?

- ⭐ Star this repository if you found it useful.  
- 🤝 Open to collaborations in **Machine Learning**, **AI**, and **Geospatial Data Science**.  
- 📩 Feel free to connect for internships, research, or open-source projects.

---


