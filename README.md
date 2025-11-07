# India Census 2011 Data Analysis with Python

**Project from:** *13 Python Data Analytics Real World Hands-on Projects* (Udemy)  
**Dataset:** `India Census 2011.csv` – District-level census data from **2011**

---

## Project Overview
This project performs **in-depth demographic analysis** of **India's 2011 Census** using **Pandas**. The dataset covers **640 districts** across all states and union territories, with detailed insights into population, literacy, workers, religion, age groups, and education.

---

## Dataset Columns (Key)
| Column                        | Description |
|-------------------------------|-----------|
| `District`                    | Name of the district |
| `State_name`                  | State/UT |
| `Population`                  | Total population |
| `Male` / `Female`             | Gender split |
| `Literate` / `Illiterate`     | Literacy status |
| `Workers` / `Non_Workers`     | Employment status |
| `Hindus`, `Muslims`, etc.     | Religious composition |
| `Age_Group_0_29`, `30_49`, `50+` | Population by age group |
| `Primary_Education`, `Graduate_&_Above` | Education levels |

---

## Key Analysis Performed
- Loaded and explored **district-level census data**
- Aggregated metrics by **state** and **district**
- Analyzed:
  - **Literacy rate** by gender and region
  - **Worker participation** across age groups
  - **Religious demographics**
  - **Education attainment** (primary to graduate+)

> **Sample Insight:**  
> Kerala leads in **literacy rate**; Uttar Pradesh has the **largest population**

---

## Tools & Libraries
```python
pandas
```

### Insights Gained

- **Urban districts** show **higher literacy and graduate rates**  
- **Gender gap in literacy** is **significant in northern states**  
- **Worker participation** peaks in the **30–49 age group**  
- **Religious diversity** varies **sharply by region** (e.g., Jammu & Kashmir vs Kerala)  
- **Ideal for policy planning, education reforms, and demographic forecasting**
