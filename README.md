
# Intelligent Classification of Rural Infrastructure Projects 🇮🇳

 **IBM Watson Studio AutoAI** to classify infrastructure projects into PMGSY schemes.

---

## Problem Statement

Develop a machine learning model to automatically classify rural road/bridge construction projects into one of the following PMGSY schemes:
- PMGSY-I
- PMGSY-II
- RCPLWEA
- etc.

Classification is based on physical and financial characteristics such as project length, cost, number of works completed, and expenditure.

---

##  Dataset

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

##  Tools & Technologies Used

- IBM Watson Studio (AutoAI)
- IBM Cloud Object Storage
- IBM Watsonx.ai Deployment Spaces
- Python (for dataset preparation)
- GitHub (for project showcase)

---

##  AutoAI Workflow

- Dataset uploaded to IBM Watson Studio
- AutoAI explored multiple pipelines (Random Forest, Gradient Boosting, etc.)
- Best performing model was automatically selected and evaluated
- Final model deployed via IBM Cloud deployment space

---

##  Deployment

Model deployed on IBM Cloud.  
 `ibm_cloud_link.txt`

---


##  Author

**Siva Prasad**  
3rd Year CSE, Kerala Technological University  
GitHub: [github.com/Sivaprasad2k](https://github.com/Sivaprasad2k)
