# Hooplytics - Understanding Basketball, Defense & Shooting
## Team Members
- Jada 
- Avnoor 
- Bennett
- Alyssa 

---

# Project Overview

Hooplytics is a basketball analytics project focused on understanding how scoring in the NBA has evolved over time, particularly the rise of the three point shot.

Our research looks through whether NBA players are primarily scoring through two point shots or three point shots in the modern era of basketball. By analyzing player shooting statistics from the 2024 NBA season, we explore how offensive strategies have shifted toward efficiency based scoring and perimeter shooting.

This project highlights how modern basketball differs from earlier eras and how analytics continue to influence gameplay, roster construction, and player development.

---

# Research Question

## What percentage of shots are primarily being made in the NBA?
- Three pointers
- Two pointers

---

# Why This Matters

Basketball has changed significantly over time. Earlier eras emphasized physical play and scoring near the basket, while modern basketball prioritizes spacing, shooting efficiency, and three point scoring.

The rise of players like Stephen Curry transformed the three point shot into one of the most important offensive weapons in basketball. Understanding these trends helps:
- Coaches develop strategies
- Teams improve roster building
- Players optimize shot selection
- Fans better understand the evolution of the game

---

# Dataset Information

## Source
NBA Player Totals Dataset (2024 NBA Season)

The dataset was publicly sourced from:
- Basketball Reference
- Similar NBA statistical databases

## Participants
Approximately 735 NBA players were included in the analysis.

## Timeline
This is a one time statistical analysis focused on the 2024 NBA season rather than a longitudinal study.

---

# Data Cleaning & Preparation

The dataset was cleaned by:
- Removing missing values
- Converting statistical columns to numeric formats
- Removing duplicate or invalid rows
- Standardizing statistical categories for consistency

---

# Feature Selection

## Independent Variables
The following variables were selected to analyze shot volume and shooting efficiency:

- FGA (Field Goal Attempts)
- 3PA (Three Point Attempts)
- FG% (Field Goal Percentage)
- 3PT% (Three Point Percentage)

These variables measure:
- Shot volume
- Shot efficiency
- Scoring opportunities

## Dependent Variable
- PTS (Total Points)

PTS was used as the primary scoring output variable.

---

# Feature Engineering

Additional variables were created to improve analysis:

- Points Per Game (PPG)
- Field Goal Percentage
- Three Point Percentage
- Three Point Attempt Share

These features helped break down:
- Scoring efficiency
- Shot selection
- Offensive tendencies

---

# Statistical Analysis

The following statistical methods were used:

## Descriptive Statistics
- Mean
- Median
- Standard Deviation
- Range

## Correlation Analysis
We analyzed relationships between:
- Scoring output
- Shooting efficiency
- Shot volume

## Data Visualizations
Visualizations included:
- Histograms
- Scatter plots
- Shot distribution comparisons

These visualizations helped identify trends and patterns in player scoring behavior.

---

# Key Findings

Our analysis demonstrates a major transformation in basketball strategy.

The data supports the idea that:
- NBA teams are taking more three point shots than ever before
- Offensive systems now prioritize efficiency and spacing
- Modern basketball emphasizes maximizing points per possession

The increase in three point shooting reflects a leagu -wide shift toward analytics driven decision making.

Players such as Stephen Curry played a major role in reshaping how basketball is played by proving that high volume three point shooting can be both efficient and highly effective.

---

# Conclusion

This project visualizes how basketball has evolved over the past century into a game heavily influenced by analytics and efficiency.

The rise of three point shooting has changed:
- Offensive strategy
- Defensive schemes
- Player development
- Team roster construction

Understanding these statistical trends provides valuable insight into why today’s NBA looks significantly different from earlier generations of basketball.

---


# Future Directions

Future research could expand this analysis by including:
- Shot location tracking
- Play by play analysis
- Defensive coverage data
- Positional comparisons
- Historical multi season comparisons

This would provide deeper insight into:
- Shot quality
- Offensive decision making
- Tactical evolution in basketball

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# References

Zając, T., Mikołajec, K., Chmura, P., Konefał, M., Krzysztofik, M., & Makar, P. (2023).  
*Long-Term Trends in Shooting Performance in the NBA: An Analysis of Two- and Three-Point Shooting across 40 Consecutive Seasons.*  
International Journal of Environmental Research and Public Health, 20(3), 1924.  
https://doi.org/10.3390/ijerph20031924

Freitas, L. (2021).  
*Shot Distribution in the NBA: Did we see when 3-point shots became popular?*  
German Journal of Exercise and Sport Research.  
https://pmc.ncbi.nlm.nih.gov/articles/PMC7712598/

Foteinakis, P. F., & Pavlidou, S. P. (2025).  
*A Decade of Evolution: Comparative Analysis of Shooting Trends and Offensive Efficiency in the NBA and EuroLeague.*  
https://www.mjssm.me/clanci/MJSSM_September_2025_Foteinakis.pdf

Hu, Q. (2024).  
*The Three-Point Revolution: A Profound Impact on NBA Game Strategy.*  
https://www.deanfrancispress.com/index.php/te/article/view/944
