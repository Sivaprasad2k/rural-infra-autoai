
# Intelligent Classification of Rural Infrastructure Projects 🇮🇳

This project was developed as part of the **IBM SkillBuild Internship via AICTE (2025)**.  
It uses **IBM Watson Studio AutoAI** to classify infrastructure projects into PMGSY schemes.

---

## 🔍 Problem Statement

Develop a machine learning model to automatically classify rural road/bridge construction projects into one of the following PMGSY schemes:
- PMGSY-I
- PMGSY-II
- RCPLWEA
- etc.

Classification is based on physical and financial characteristics such as project length, cost, number of works completed, and expenditure.

---

## 📁 Dataset

- **Source**: [India AI Kosh – PMGSY Dataset](https://aikosh.indiaai.gov.in/web/datasets/details/pradhan_mantri_gram_sadak_yojna_pmgsy.html)
- **Columns**:
  - STATE_NAME
  - DISTRICT_NAME
  - NO_OF_ROAD_WORK_SANCTIONED
  - LENGTH_OF_ROAD_WORK_SANCTIONED
  - COST_OF_WORKS_SANCTIONED
  - ...and other project-specific details

Target column: **`PMGSY_SCHEME`**

---

## ⚙️ Tools & Technologies Used

- IBM Watson Studio (AutoAI)
- IBM Cloud Object Storage
- IBM Watsonx.ai Deployment Spaces
- Python (for dataset preparation)
- GitHub (for project showcase)

---

## 🧠 AutoAI Workflow

- Dataset uploaded to IBM Watson Studio
- AutoAI explored multiple pipelines (Random Forest, Gradient Boosting, etc.)
- Best performing model was automatically selected and evaluated
- Final model deployed via IBM Cloud deployment space

---

## 📊 Model Performance

> AutoAI generated the leaderboard of models with their accuracy, precision, recall, and F1 scores.  
> *(See `model_performance.png` for details.)*

---

## 🚀 Deployment

Model deployed on IBM Cloud.  
**Link (if public):** See `ibm_cloud_link.txt`

---

## 📎 Project Files

| File | Description |
|------|-------------|
| `PMGSY_DATASET.csv` | Dataset used (partial/sample) |
| `deployment_screenshot.png` | IBM Watsonx.ai deployment screenshot |
| `model_performance.png` | AutoAI leaderboard screenshot |
| `result.pdf` | Summary of the project result |
| `final_ppt.pdf` | Final PPT submitted for IBM Internship |
| `ibm_cloud_link.txt` | Public deployment URL (if applicable) |

---

## 🙋‍♂️ Author

**Siva**  
3rd Year CSE, Kerala Technological University  
GitHub: [github.com/Sivaprasad2k](https://github.com/Sivaprasad2k)
