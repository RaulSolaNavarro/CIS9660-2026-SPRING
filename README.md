# Customer Churn Prediction — CIS/STA 9660 Term Project Proposal

> **Course:** CIS/STA 9660 — Data Mining  
> **Due:** March 20, 2026  
> **Presentation:** March 16, 2026

## 📋 Project Summary

This repository contains the proposal and presentation slides for our term project on **customer churn prediction** using the [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) from Kaggle.

**Research Question:**  
Can we predict whether a telecom customer will churn based on their contract type and monthly charges? We also investigate the interaction (synergy) effect between internet service type and customer tenure.

**Method:** Binary Logistic Regression with Interaction Terms (`ContractType × InternetService`)

---

## 📁 Repository Structure

```
churn-proposal/
├── index.qmd          # Main Quarto presentation source
├── custom.scss        # Custom RevealJS theme
├── README.md          # This file
└── _quarto.yml        # Quarto project config (optional)
```

---

## 🚀 Viewing the Slides

### Option 1 — GitHub Pages (recommended)
Once deployed, slides are available at:  
`https://<your-username>.github.io/<repo-name>/`

### Option 2 — Render locally
Make sure you have [Quarto](https://quarto.org/docs/get-started/) installed, then:

```bash
# Clone the repo
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# Render the presentation
quarto render index.qmd

# Preview with live reload
quarto preview index.qmd
```

This will open the slides in your browser at `http://localhost:4848`.

---

## 🌐 Deploying to GitHub Pages

### One-time setup
1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set Source to **GitHub Actions**
4. Push any commit — the workflow will auto-deploy

The included `.github/workflows/publish.yml` handles rendering and deployment automatically.

### Manual deploy (alternative)
```bash
quarto publish gh-pages index.qmd
```

---

## 📊 Dataset

- **Source:** [Kaggle — Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Observations:** 7,043 customers
- **Variables:** 21 features
- **Target:** `Churn` (Yes / No)

---

## 👥 Team Members

| Name | Role |
|------|------|
| [Team Member 1] | Contact Person |
| [Team Member 2] | |
| [Team Member 3] | |

---

## 🗓️ Project Timeline

| Milestone | Date |
|-----------|------|
| In-Class Presentation | March 16, 2026 |
| Project Proposal Due | March 20, 2026 |
| Final Presentation | May 11, 2026 |
| Final Report + Code + Data | May 15, 2026 |
| Peer Evaluation | May 15, 2026 |
