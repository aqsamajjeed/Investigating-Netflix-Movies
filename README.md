# 🎬 Investigating Netflix Movies – A 1990s Exploration

## 📌 Project Overview

This project explores Netflix’s movie catalog to investigate trends and insights specifically from the **1990s** — a decade known for its nostalgic cinematic gems. The focus is to understand movie durations and genre patterns during this era, helping a production company interested in reviving nostalgic formats make data-informed decisions.

---

## 📁 Dataset Summary

The dataset `netflix_data.csv` includes all titles available on Netflix with the following attributes:

| Column Name    | Description                                  |
|----------------|----------------------------------------------|
| `show_id`      | Unique identifier for each title             |
| `type`         | Either Movie or TV Show                      |
| `title`        | Name of the movie/show                       |
| `director`     | Director of the title                        |
| `cast`         | Main cast involved                           |
| `country`      | Country of origin                            |
| `date_added`   | Date the title was added to Netflix          |
| `release_year` | Year the movie/show was originally released  |
| `duration`     | Duration in minutes (movies) or seasons (TV) |
| `description`  | Short description of the title               |
| `genre`        | Primary genre of the title                   |

---

## 🔍 Key Questions Explored

### 🕒 What was the most common movie duration in the 1990s?
By filtering titles that are classified as **Movies** and released between **1990 and 1999**, we analyzed the distribution of movie durations.  
📌 **Insight**: The most frequent movie duration in the 1990s was **100 minutes**.

---

### 🎯 How many short action movies were released in the 1990s?
We focused on **Action** genre films from the 1990s and counted how many were considered "short" (i.e., less than 90 minutes).  
📌 **Insight**: Only **7 short action movies** were released during this decade, suggesting a preference for longer storytelling formats in the action genre.

---

## 📈 Learning Outcomes

- Practiced **data filtering** using multiple conditions in Pandas  
- Applied **logical operators** for time-based and genre-specific segmentation  
- Analyzed **distribution of numeric data** through histograms  
- Gained experience in **genre-focused exploratory analysis**  
- Produced actionable insights for entertainment industry decisions

---

## 🧰 Tools & Technologies

- **Python** for data analysis  
- **Pandas** for data manipulation  
- **NumPy** for logical filtering  
- **Matplotlib** for data visualization

---


