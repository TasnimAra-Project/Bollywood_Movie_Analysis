# 🎬 Lights, Camera, Ratings! What Makes Bollywood Movies a Hit

This data storytelling project explores the **factors influencing Bollywood movie success**, with a focus on **IMDB ratings**. By analyzing genres, star power, and time periods, this project uncovers the hidden patterns that contribute to a blockbuster hit in Indian cinema.

---
## 🧠 Built With

- Quarto (.qmd)
- Language: **R**

![R](https://img.shields.io/badge/Language-R-blue.svg)

## 🎯 Project Objective

To answer the question:  
**What makes a Bollywood movie a hit?**  
We explore:
- The impact of **genre** on ratings
- The influence of **lead actors**
- The trends over time from **2000 to 2023**

---

## 📊 Data Sources

- 📁 [IMDB Movie Dataset (1951–2023)] — Contains metadata, cast, and ratings  
- 📁 [Bollywood Movies Dataset] — Movie titles, years, and relevant identifiers  
- 🧭 Data sourced from GitHub and The Movie Database (TMDb)

---

## 🧰 Tools & Libraries

The analysis is performed in **R** using:

```r
tidyverse       # Data wrangling
ggplot2         # Visualization
ggcharts        # Quick insights
ggupset         # UpSet plots for combinations
patchwork       # Layout multiple plots
tidytext        # (Optional) Text processing for cast or genre
```
## 🧪 Analysis Steps

### 🔹 Data Cleaning
- Filtered movies between **2000–2023**
- Extracted **primary genre** and **lead actor**
- Merged datasets by **movie title** and **year**

### 🔹 Genre Impact
- Grouped **IMDB ratings** by genre
- Visualized **average rating by genre** to identify top-performing categories

### 🔹 Star Power
- Analyzed **lead actor appearances** and their correlation with higher-rated movies
- Identified **actors frequently associated** with top-rated films

### 🔹 Trend Over Time
- Examined how **ratings changed over decades**
- Visualized **genre popularity shifts** and evolving **audience preferences**

---

## 📌 Key Findings

- 🎭 **Genres like Drama and Biography** consistently earned higher IMDB ratings  
- 🌟 Movies starring **Shah Rukh Khan, Deepika Padukone, and Aamir Khan** often outperform the average  
- 📽️ The **2010s** marked a shift toward more diverse and nuanced storytelling  
- 🎬 Ratings are **strongly influenced by the combination of genre + lead actor**, rather than either alone

---

## 📄 Output

The final output is a polished **HTML report** containing:

- 📈 **Visualizations** for genre trends  
- 🧑‍🎤 **Actor vs. Rating** performance charts  
- 📆 **Timeline insights** from 2000 to 2023
