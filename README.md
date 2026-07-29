# Beyond Economic Growth

### Climate Resilience, Agriculture, and Trade as Drivers of Food Security

**Data Visualization**  

---

## Project Overview

Economic growth is often viewed as the primary driver of food security. This project investigates whether wealth alone is sufficient to explain food availability across countries.

Using integrated datasets from **FAOSTAT** and the **World Bank**, the analysis explores how **climate change**, **agricultural capacity**, and **trade** contribute to resilient food systems.

The analytical findings are presented through an interactive **Streamlit dashboard**, enabling users to explore global trends as well as country-level insights.

---

## Project Objectives

The project addresses the following objectives:

- Evaluate the relationship between GDP and food availability.
- Examine the influence of climate change on food security.
- Assess the contribution of agricultural land and food production.
- Analyse long-term food security trends.
- Develop a composite Food System Resilience Index.
- Build an interactive dashboard for exploratory analysis.

---

## Data Sources

| Source | Dataset |
|---------|---------|
| FAOSTAT | Food Balance Sheets |
| FAOSTAT | Temperature Change on Land |
| World Bank | GDP per Capita |
| World Bank | Population |
| World Bank | Agricultural Land (%) |

**Coverage**

- 178 Countries
- 2010–2023

---

## Repository Structure

```text
beyond-economic-growth/

├── Home.py
├── config.py
├── utils.py
├── requirements.txt
├── README.md
│
├── pages/
│
├── data/
│   └── raw/
|   └── processed/
│
├── notebooks/
│   ├── 01_Data_Preparation.ipynb
│   ├── 01_Data_Preparation.html
│   ├── 02_Analytical_Questions_v4.ipynb
│   └── 02_Analytical_Questions_v4.html
│
└── presentation/
    └── Beyond_Economic_Growth.pdf
```

---

## Analytical Framework

The project investigates **twelve analytical questions** organised into four themes:

- Economy & Prosperity
- Climate & Resilience
- Agriculture & Trade
- Change & Composite Analysis

---

## Interactive Dashboard

The Streamlit application provides:

- Executive Overview
- Global Trends
- Economy & Food
- Climate Impact
- Agriculture & Production
- Country Explorer
- Resilience Rankings

### Dashboard Features

- Interactive sidebar filters
- Country-level exploration
- KPI cards
- Plotly visualisations
- Accessible colour palette
- Responsive layout

---

## Technologies

- Python
- Streamlit
- Plotly
- Pandas
- NumPy

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Anupriya-Segar/beyond-economic-growth
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the dashboard:

```bash
streamlit run Home.py
```

---

## Project Deliverables

- Data Preparation Notebook
- Analytical Questions Notebook
- Interactive Streamlit Dashboard
- Final Project Presentation (PDF)

---

## Future Improvements

Potential extensions include:

- Additional climate indicators
- Forecasting models
- Scenario analysis
- Policy simulation
- Automated data updates

---

## Author

**Anupriya Segar**

M.Sc. Data Science

University of Europe for Applied Sciences

---

## License

This project was developed for academic purposes as part of the Data Visualization course.
