# anime-database-excel-dashboard
Comprehensive Excel dashboard analyzing 21460 anime titles: types, ratings, producers, studios, genres, and airing trends.
# 🎌 Anime Database Excel Dashboard

**Date:**  13th May, 2026  
**Tool:** Microsoft Excel (Power Query + Power Pivot + DAX + VBA Macros)  
**Author:** Reyad Aly  
**Dataset:** [Anime Database 2022 — Kaggle](https://www.kaggle.com/datasets/harits/anime-database-2022)

## Dashboard Highlights
- Total anime count, members, average score, and episode statistics
- Distribution of anime types, airing status, and ratings
- Top anime demographics and most common genres/themes
- Top 5 producers, licensors, and top 10 studios
- Broadcasting days, timeslots, and seasonal trends
- Distribution by decade and episode duration
- Top ranked, most popular, and most favorited anime
  
<img width="1787" height="810" alt="Screenshot 2026-07-05 090336" src="https://github.com/user-attachments/assets/ca168007-19cb-4f52-8989-35b83a181c96" />
<img width="1787" height="803" alt="Screenshot 2026-07-05 090501" src="https://github.com/user-attachments/assets/79725c0b-04b7-46b2-8d91-4af1fc2ff51a" />
<img width="1787" height="802" alt="Screenshot 2026-07-05 090444" src="https://github.com/user-attachments/assets/53f35d77-6822-4d32-b3af-17663650f490" />
<img width="1783" height="803" alt="Screenshot 2026-07-05 090715" src="https://github.com/user-attachments/assets/8ce7d6d0-9be9-44cc-8d26-0b7e2f116300" />

## Data Cleaning Steps (Power Query)
- Promoted headers and changed data types
- Replaced missing/null values with "Unknown"
- Trimmed and cleaned text across all columns
- Removed blank rows and irrelevant columns
- Merged columns for standardization
- Split columns by delimiter and position
- Sorted rows and renamed columns for clarity

<img width="1919" height="834" alt="Screenshot 2026-07-05 082204" src="https://github.com/user-attachments/assets/911c5834-5b60-41ca-800c-0acbde3e5f29" />


## DAX Measures (Power Pivot)
- Most Members
- Average Score
- TV Total Episodes
- Longest Anime Episodes
- Currently Airing count
- AVG TV Total Episodes
- AVG Total Episodes
<img width="1919" height="826" alt="Screenshot 2026-07-05 082448" src="https://github.com/user-attachments/assets/ccbff3b5-9c7e-4427-b611-2461c300ea49" />

---

## Files Included
| File | Description |
|---|---|
| `anime_dashboard.xlsx` | Main Excel dashboard file |
| `anime_summary.pdf` | Summary report (must be in same folder as .xlsx) |
| `anime_recommendation.pdf` | Recommendation report (must be in same folder as .xlsx) |
| `screenshots/` | Dashboard preview images |

> ⚠️ **Important:** The PDF files must be placed in the **same folder** as the 
> Excel file for the macro-linked buttons to work correctly.

## License
MIT License
