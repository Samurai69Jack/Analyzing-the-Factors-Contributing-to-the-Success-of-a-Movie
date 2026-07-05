# 🎬 Analyzing the Factors Contributing to the Success of a Movie


Identifying what actually makes a movie successful — using correlation analysis, hypothesis testing, and EDA on a dataset of movies released between 1980 and 2022.




## 🌍 What This Project Does

What makes a movie a blockbuster? Is it the budget? The cast? The genre? Or just good timing?

This project analyses decades of movie data to find out which factors — budget, votes, studio, genre, release date — actually correlate with gross earnings, and which ones turn out to be irrelevant despite popular belief.

The short answer? Budget and audience votes are what matter most. The studio producing the film? Almost irrelevant.


## 📌 Project Overview

This project covers:


🧹 Data cleaning and preprocessing of movie metadata
📊 Exploratory Data Analysis across budget, genre, ratings, and gross earnings
🔗 Correlation matrix to identify key success factors
📐 Pearson's correlation statistical analysis
💡 Actionable insights for understanding what drives box office performance



## 📂 Dataset Description

Source: Kaggle — Movie Industry Dataset
Coverage: Movies released between 1980 and 2022

ColumnDescriptionnameMovie titleratingAge rating (G, PG, R, etc.)genrePrimary genreyearRelease yearreleasedFull release datescoreIMDb user scorevotesNumber of user votes on IMDbdirectorDirector namebudgetProduction budget (USD)grossWorldwide gross earnings (USD)companyProduction companyruntimeMovie duration in minutes


## ⚙️ Tools & Technologies

ToolPurpose🐍 Python (Pandas, NumPy)Data manipulation and cleaning📊 Matplotlib, SeabornVisualisation and correlation heatmaps📐 SciPyPearson's correlation and hypothesis testing📓 Jupyter NotebookDevelopment environment


## 🧹 Data Cleaning & Preprocessing


Handled missing values across budget, gross, and rating columns
Converted budget and gross columns to numeric format
Removed rows with null values in key analysis columns
Extracted release year from full date field
Sorted and filtered dataset for valid budget and gross entries



## 📈 Key Findings

### 🔗 What Correlates Most with Gross Earnings?

FactorCorrelation with GrossVerdictVotes (audience engagement)High ✅Strong predictorBudgetHigh ✅Strong predictorScore (IMDb rating)ModeratePartial predictorCompany (studio)Low ❌Not a reliable predictorRuntimeLowMinimal impact

### 💡 The Biggest Surprise

The production company — whether a movie is made by a major studio or a smaller one — has no significant correlation with gross earnings. A big studio name doesn't guarantee box office success.

### 📅 Genre Trends

Action, Adventure, and Animation consistently appear among the highest-grossing genres across decades, while Drama and Documentary perform well on ratings but not on revenue.

### 📊 Budget vs Gross

There is a clear positive relationship between budget and gross earnings — but it's not linear. High-budget films more consistently turn a profit, while low-budget films have a wider spread — some become massive hits (horror genre especially), others barely break even.


### 💡 Business Recommendations


Prioritise audience engagement over critic scores — votes on IMDb correlate more with gross earnings than critical ratings do.
Budget is a commitment, not a guarantee — higher budgets reduce downside risk but don't eliminate it.
Don't pay a premium for a big studio name — company has no significant correlation with earnings; the content matters more.
Action and Animation are the safest genre bets for consistent gross revenue.
Horror is the highest ROI genre — low production cost, high potential upside when it connects with audiences.



### 🔑 Key Technical Takeaway


Correlation analysis cuts through assumptions. The movie industry is full of beliefs about what makes a film successful — stars, studios, sequels. The data shows that audience engagement and budget are the real drivers, while many assumed factors turn out to be statistically insignificant.
