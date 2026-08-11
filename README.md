# Unemployment Analysis in India

## About the Project

This is a Data Science project where I analyzed unemployment data in India using Python.

The main purpose of this project is to understand how unemployment changed over time and how it differed between states, rural and urban areas, and different regions of India.

I also looked at the changes in unemployment during the COVID-19 period.

---

## What I Wanted to Find

Through this project, I wanted to answer questions like:

- How did unemployment change over time?
- Which states had the highest and lowest unemployment?
- Is unemployment different in rural and urban areas?
- What happened to unemployment during COVID-19?
- Which regions of India were more affected?
- Is there a relationship between unemployment and labour participation?

---

## Dataset

I used two unemployment datasets for this project.

### Dataset 1: Unemployment in India

This dataset contains information about unemployment in different Indian states and areas.

Some of the important columns are:

- Region
- Date
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

### Dataset 2: Unemployment Rate up to November 2020

This dataset contains unemployment information along with geographical regions and coordinates.

Important columns include:

- Region
- Date
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Geographical Region
- Longitude
- Latitude

---

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## What I Did

### 1. Data Cleaning

First, I loaded both datasets and checked them for:

- Missing values
- Empty rows
- Duplicate records
- Incorrect date formats

The first dataset contained 28 completely empty rows, which were removed.

After cleaning, the first dataset had 740 valid rows.

---

### 2. Overall Unemployment Trend

I calculated the monthly average unemployment rate and plotted it over time.

The unemployment rate was relatively stable before 2020 but increased sharply during April and May 2020.

---

### 3. State-wise Analysis

I calculated the average unemployment rate for each state.

Some of the results were:

| State | Average Unemployment |
|---|---:|
| Tripura | 28.35% |
| Haryana | 26.28% |
| Jharkhand | 20.59% |
| Bihar | 18.92% |
| Meghalaya | 4.80% |

Tripura had the highest average unemployment rate in the analysis, while Meghalaya had the lowest.

---

### 4. Rural vs Urban Analysis

I compared unemployment between rural and urban areas.

| Area | Average Unemployment |
|---|---:|
| Urban | 13.67% |
| Rural | 10.32% |

In this dataset, the average unemployment rate was higher in urban areas than in rural areas.

---

### 5. Unemployment and Labour Participation

I also checked the relationship between unemployment and labour participation.

The correlation was approximately:

**0.003**

This means that there was almost no linear relationship between the two variables in this dataset.

---

## COVID-19 Analysis

One of the main parts of this project was studying the effect of COVID-19 on unemployment.

The unemployment rate changed significantly during this period.

| Month | Unemployment Rate |
|---|---:|
| March 2020 | 10.78% |
| May 2020 | 23.24% |
| October 2020 | 8.03% |

The unemployment rate increased by approximately **115.57%** from March to May 2020.

After reaching the peak in May, unemployment decreased significantly and reached 8.03% by October 2020.

---

## Regional Analysis

I also compared unemployment across geographical regions.

| Region | Average Unemployment |
|---|---:|
| North | 15.86% |
| East | 13.92% |
| Northeast | 10.95% |
| South | 10.45% |
| West | 8.23% |

The North had the highest average unemployment rate among the regions in the dataset, while the West had the lowest.

---

## Some Interesting Findings

- Unemployment increased sharply during the COVID-19 period.
- The unemployment rate more than doubled between March and May 2020.
- Urban unemployment was higher than rural unemployment in the dataset.
- There was a large difference in unemployment rates between different states.
- Tripura had the highest average unemployment rate among the states analyzed.
- Meghalaya had the lowest average unemployment rate.
- The North had the highest average unemployment among the geographical regions.
- The unemployment rate started falling after the May 2020 peak.

