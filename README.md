# 🐾 Employee Leaving Predictor With Dashboard

This repository delivers a complete workflow to **predict the likelihood of employee attrition** and visualise those risks in a rich, interactive Power BI dashboard.  It is designed both as a practical HR‑analytics solution and as a showcase project for data‑science portfolios.

---

## 📌 What does this project do?

- Trains a supervised learning model that assigns every employee a **probability of resignation**.
- Presents the predictions, sliced by department and seniority, in a **Power BI dashboard**.
- Helps HR teams quickly identify roles at risk and design targeted **retention initiatives**.

---

## 📁 Dataset source

The model is trained with an AI-made fake employee dataset

---

## 🧠 How does it work?

| Layer     | Technology                                         | Purpose                                         |
| --------- | -------------------------------------------------- | ----------------------------------------------- |
| Data prep | **Pandas**, **Numpy**                              | Cleaning, feature engineering, train‒test split |
| Modelling | **Gradient Boosting Classifier, Random Forest...** | Predict leave probability                       |
| Reporting | **Power BI**                                       | Interactive dashboard                           |
|           |                                                    |                                                 |

---

## 🚀 How to run the project locally

> **Prerequisites:** Power BI Desktop, Python 3.9+

1. **Clone the repo**
   ```bash
   git clone https://github.com/your‑username/employee‑leaving‑predictor.git
   cd employee‑leaving‑predictor
   ```
2. **Create & activate a virtual environment** (optional but recommended)
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS / Linux
   source venv/bin/activate
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Train / refresh the model**
   ```bash
   Change the csv name in the jupyter notebook and run it all
   ```
   A pickled model (`employee_attrition_model.pkl`) and metrics report will be saved to `/models`.
5. **Open the dashboard**
   - Launch Power BI Desktop.
   - Open the file `HR_Dashboard.pbix`.
   - Hit **Refresh** ➜ the dashboard will load the latest predictions.

---

## 🧪 Example use case

1. HR uploads the latest employee table to `data/latest_employees.csv`.
2. Run `Resignate_predictor.ipynb`.
3. Open the dashboard ➜ instantly see **“High‑risk” employees (> 40 % probability)** highlighted, with drill‑through to department and role level.

---

## 📁 Files in this project

| Path                                  | Description                                        |
| ------------------------------------- | -------------------------------------------------- |
| `HR_Dashboard.ipbx`                   | Power BI PBIP                                      |
| `Resignate_predictor.ipynb`           | EDA and modelling notebook                         |
| `requirements.txt`                    | Python dependencies                                |
| `Dataset_RRHH.csv`                    | Dataset csv                                        |
| `README.md`                           | Project documentation (this file)                  |

---

## 👨‍💻 Author

Created with care and curiosity by **Agustin Gorrin**.

---

## 📫 Contact

- GitHub: [https://github.com/gus12green](https://github.com/gus12green)
- LinkedIn: [https://linkedin.com/in/agustín-gorrín-santana/](https://linkedin.com/in/agustín-gorrín-santana/)

---

## ⚠️ Disclaimers

- This repository is **educational / demonstrative** and not intended for production HR decisions.
- All sample data is **synthetic** and contains **no personally identifiable information**.
- The author **does not profit** from the dataset or its usage.

