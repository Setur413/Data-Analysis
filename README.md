# 🦠 COVID-19 Global Data Tracker

> Exploratory data analysis of global COVID-19 trends across **Kenya, USA, and India** —  
> tracking confirmed cases, deaths, and vaccination progress over time.

---

## 📌 Project Overview

This project analyzes real-world COVID-19 data to uncover how the pandemic evolved differently across three countries with vastly different population sizes, healthcare systems, and geographic contexts. The analysis covers the full arc of the pandemic — from early outbreaks through vaccine rollouts — and presents findings through clear, informative visualizations.

**Countries Analyzed:** 🇰🇪 Kenya &nbsp;|&nbsp; 🇺🇸 USA &nbsp;|&nbsp; 🇮🇳 India

---

## 🎯 Project Objectives

- Import, clean, and preprocess COVID-19 global time-series data
- Analyze trends in total cases, daily new cases, deaths, and vaccinations
- Compare pandemic trajectories across Kenya, USA, and India
- Visualize key metrics using line plots and bar charts
- Summarize findings in a structured, report-style notebook

---

## 📁 Repository Structure

```
Data-Analysis/
│
├── covid_19.ipynb        # Main analysis notebook
└── README.md
```

---

## 🌍 Country Comparison Snapshot

| Metric | 🇰🇪 Kenya | 🇺🇸 USA | 🇮🇳 India |
|--------|-----------|---------|----------|
| Population | ~55M | ~331M | ~1.4B |
| Peak case period | Mid-2021 | Winter 2020–21 | Apr–May 2021 |
| Vaccination impact | Moderate rollout | Strong & early | Large-scale but gradual |
| Overall case count | Lowest of the three | Highest total cases | Highest single-day spikes |

---

## 📊 Key Insights

- 🇺🇸 **USA** recorded the highest total confirmed COVID-19 cases across all dates analyzed, driven by its large population and early widespread transmission.
- 🇮🇳 **India** experienced dramatic case spikes during the devastating Delta wave in April–May 2021, but subsequently launched one of the world's largest vaccination campaigns.
- 🇰🇪 **Kenya** showed lower overall case counts but exhibited clear pandemic waves that aligned with global trends.
- 💉 **Vaccination rollouts** across all three countries correlated with a significant decline in reported deaths, reinforcing the real-world impact of immunization programs.
- 📈 Time-series visualization revealed that wave patterns differed notably by country, reflecting differences in policy response, population density, and variant timing.

---

## 🧰 Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| Pandas | Data loading, cleaning, and manipulation |
| Matplotlib | Line plots, bar charts, time-series visualization |
| Seaborn | Enhanced statistical visualizations |
| Jupyter Notebook | Interactive analysis and reporting |
| Plotly / GeoPandas *(optional)* | Interactive and geographical maps |

---

## 📥 Dataset

- **Source:** [Our World in Data — COVID-19 Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)
- **File:** `owid-covid-data.csv`
- **Coverage:** Global daily data including cases, deaths, vaccinations, and population metrics
- **How to get it:** Download directly from the link above and place `owid-covid-data.csv` in the project root folder before running the notebook.

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Setur413/Data-Analysis.git
   cd Data-Analysis
   ```

2. **Install dependencies**
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. **Download the dataset**  
   Get `owid-covid-data.csv` from [Our World in Data](https://github.com/owid/covid-19-data/tree/master/public/data) and place it in the project root.

4. **Launch the notebook**
   ```bash
   jupyter notebook
   ```
   Open `covid_19.ipynb` and run all cells.

5. *(Optional)* Export to PDF via `File → Download As → PDF via LaTeX`

---

## 📌 Potential Improvements

- [ ] Add interactive Plotly charts for dynamic trend exploration
- [ ] Include a choropleth world map showing case density by country
- [ ] Extend analysis to more countries or continents
- [ ] Add a death rate and case fatality rate (CFR) comparison
- [ ] Automate data refresh by pulling directly from the OWID API

---

*Author: Jonah Tarus*  
*Date: May 2025*
