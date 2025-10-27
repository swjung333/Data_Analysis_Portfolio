## Introduction
Welcome to my first report, using PowerBi. This project visualizes the average temperature trends in Seoul, South Korea, over the past 100 years (1924–2023) to identify long-term patterns and evidence of climate change.

## Objectives
Identify the warmest, coldest year over the past 100 years and their respective temperatures.

Analyze average temperature by year and season to understand trends.

## Data Processing & Cleaning
To visualize with graphs, a few changes were made in dataset:

- **Remove rows & Use First Row as Headers.**
- **Remove columns**: Removed `지점`, `평균최저기온(℃)` and `평균최고기온(℃)`.
- **Create new columns**: Created `Month`, `Month Name`, `Year`, `Season` and `Season_Index`. 
- **Convert the language from Korean to English for readability**: Converted `년월` to `Date` and `년월(℃)` to `Average Temperature(℃)`.

---
## Dashboard Page 1
<img width="1430" height="801" alt="image" src="https://github.com/user-attachments/assets/19ab8613-df62-47ec-96ae-43fd715bed1e" />

## Dashboard Page 2
<img width="1416" height="795" alt="image" src="https://github.com/user-attachments/assets/4f697f8d-1d0c-4157-9d6a-d99af0c48459" />

--

## Findings

The average temperature **steadily increased over time**.
The average temperature in **autumn was almost always higher** than in spring.

## Conclusion

This analysis shows that it appears to be true how global warming impacts the temperature change in Korea. So we should all pay attention more to how to protect our mother nature for future generation.

