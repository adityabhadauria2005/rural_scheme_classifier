# rural_scheme_classifier
Classifies PMGSY rural projects using IBM AutoAI. Built with IBM Cloud Lite, Watson Studio &amp; Object Storage. No-code model (XGBoost) deployed for predicting project scheme. Done under Edunet Foundation &amp; IBM SkillsBuild mentorship.
# Rural Infrastructure Project Classifier

Automatically classify rural road and bridge construction projects into the correct PMGSY scheme using machine learning on IBM Cloud Lite. Built using IBM AutoAI with no-code development.

## 🔍 Problem Statement

The Pradhan Mantri Gram Sadak Yojana (PMGSY) aims to improve rural road connectivity across India. Projects under this scheme vary by objective and funding (PMGSY-I, PMGSY-II, RCPLWEA, etc.). Manual classification is inefficient and error-prone. This project leverages machine learning to classify projects based on financial and physical parameters.

## 🛠️ Tools & Technologies

- **IBM Cloud Lite**
- **IBM Watson Studio**
- **IBM AutoAI**
- **IBM Cloud Object Storage**
- **XGBoost Classifier (AutoAI selected model)**

## 📂 Dataset

The dataset includes:
- State, District
- Sanctioned & Completed Road/Bridge Length
- Expenditure & Cost details
- Scheme Label (Target column)

Source: [AI Kosh - PMGSY Dataset](https://aikosh.indiaai.gov.in/web/datasets/details/pradhan_mantri_gram_sadak_yojna_pmgsy.html)

## 🔄 System Workflow

1. **Upload Dataset** to IBM Cloud Object Storage.
2. **AutoAI Training**: Watson Studio's AutoAI selects features, trains models.
3. **Best Model**: XGBoost Classifier automatically chosen.
4. **Deployment**: Model saved and deployed via Watson Machine Learning.

## 📈 Output

- Predicts the correct `PMGSY_SCHEME` for new project data.
- Ready for integration via API or dashboard.

## 🤝 Acknowledgment

Project developed under **Edunet Foundation** & **IBM SkillsBuild** internship. Special thanks to our mentors for guidance on IBM Cloud, AutoAI, and ML tools.

---

## 📸 Screenshots

(Screenshots folder contains key visuals of model training, selection & deployment steps.)

## 📄 License

For educational and non-commercial use.

