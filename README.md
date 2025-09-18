# Gender Representation in Media Headlines: Power BI Dashboard

## Project Overview
This repository hosts a comprehensive Power BI dashboard analyzing gender representation in media headlines across five major Nigerian newspapers. The project examines how men and women are portrayed in media coverage, focusing on tone, occupational framing, regional distribution, and temporal trends. 

### Key Insight
Analysis of 150 headlines across five newspapers shows that female representation in media headlines is consistently lower than male representation. This finding aligns with existing research on gender disparities in news coverage and highlights areas for further investigation.


This dashboard serves as a research tool for scholars, journalists, and policymakers interested in gender equity in media representation. It combines high-level metrics with detailed visualizations for evidence-based insights.

---

## Dataset
- **Newspapers:** Punch, Guardian, Vanguard, Premium Times, [Fifth Newspaper]  
- **Coverage:** 10 headlines per newspaper per day, across 3 days  
- **Total Headlines:** 5 × 10 × 3 = **150 headlines**  

### Variables Captured
- Newspaper source  
- Date of publication  
- Gender of the subject (male/female)  
- Tone of coverage (positive, neutral, negative)  
- Region  
- Occupation or role mentioned in the headline  

> **File:**
>The dataset can be downloaded [here](https://github.com/Janetkomaiya/E-commerce-Projects/blob/main/Newspaper%20Headlines.csv)


---

## Key Performance Indicators (KPIs)
The dashboard provides four high-level KPIs for quick insights:

| KPI | Description |
|-----|-------------|
| **Total Headlines** | Total number of headlines analyzed: 150 |
| **Female Count** | Number of headlines referencing female subjects |
| **Male Count** | Number of headlines referencing male subjects |
| **Number of Newspapers** | Distinct newspapers included: 5 |

---

## Visualizations
The dashboard includes seven interactive charts:

| Visualization | Description |
|---------------|-------------|
| **Tone of Coverage by Gender** | Measures positive, neutral, and negative tone in headlines by gender. |
| **Headline Count by Newspaper** | Displays the number of headlines per newspaper. |
| **Headlines by Gender Count** | Comparative count of male vs. female-focused headlines. |
| **Timeline of Coverage** | Tracks gendered coverage across the 3 days. |
| **Regional Distribution by Gender** | Shows geographic distribution of coverage by gender. |
| **Occupational Frame by Gender** | Examines which occupations are associated with male or female subjects in headlines. |
| **Gender Representation Summary Table** | Tabular overview of headline counts by newspaper, gender, and tone. |

---

## Methodology
1. **Data Collection:** Headlines were collected from five major Nigerian newspapers (Punch, Guardian, Vanguard, Premium Times, [Fifth Newspaper]) over three consecutive days, 10 headlines per newspaper per day.  
2. **Data Cleaning:** Gender coding, tone analysis, and occupational categorization were standardized.  
3. **Analysis:** Power BI was used to compute KPIs, generate interactive visualizations, and identify patterns in gender representation.  
4. **Validation:** Data accuracy and consistency were cross-checked to ensure reliability.

---

### Dashboard Preview

![Gender Representation Dashboard](https://raw.githubusercontent.com/Janetkomaiya/Gender-Representation-in-Media-Headlines/d28c469bbc0bfb6b40fa9b059e4f52d05b68ecf2/gender_representation_Dashboard.png)

*Figure: Power BI dashboard showing gender representation in media headlines across five newspapers.*

## How to Use the Dataset

1. **Download the dataset**  
   Click [here](https://raw.githubusercontent.com/Janetkomaiya/E-commerce-Projects/main/Newspaper%20Headlines.csv) to download the CSV file.

2. **Open the dataset**  
   You can open the CSV in Excel, Google Sheets, or load it directly into Power BI, Python (pandas), or R for analysis.

3. **Understand the columns**  
   The dataset includes the following fields:
   - `NewspaperName` – Name of the newspaper (Punch, Guardian, Vanguard, Premium Times, etc.)
   - `Date` – Date of publication
   - `Headline` – Text of the headline
   - `Gender` – Gender of the subject referenced in the headline (Male/Female)
   - `Tone` – Sentiment of the headline (Positive, Neutral, Negative)
   - `Region` – Geographic location referenced in the headline
   - `Occupation` – Occupation or role mentioned in the headline

4. **Perform analysis**  
   - **Power BI:** Load the CSV into Power BI to reproduce the dashboard or create new visualizations.  
   - **Python/R:** Use this dataset for statistical analysis, charts, or machine learning on gender representation in media headlines.  

5. **Interpret results**  
   - KPIs in the dashboard show high-level insights (total headlines, male/female counts, newspaper counts).  
   - Charts allow deeper analysis: tone of coverage, occupational framing, regional distribution, timeline trends, and newspaper comparisons.  

6. **Cite the dataset**  
   If you use this dataset in your research, please cite:

   > Ifidon Komaiya, J. (2025). *Gender Representation in Media Headlines: Dataset and Dashboard*. [GitHub Repository](https://github.com/Janetkomaiya/Gender-Representation-in-Media-Headlines)


## Significance
This dashboard provides a **rigorous, data-driven perspective** on gender representation in media headlines. It is suitable for:  
- Academic research in media and gender studies  
- Editorial decision-making  
- Public awareness initiatives  
- Comparative studies over time or across regions  

