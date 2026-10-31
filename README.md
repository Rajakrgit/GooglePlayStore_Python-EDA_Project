# GooglePlayStore_Python-EDA_Project
# 1. Project Overview

The Google Play Store App Insights project explores app-market data
to understand application popularity, user ratings, downloads, app size,
pricing, categories, update activity, and customer feedback.

The business case describes a technology company that wants to use
Google Play Store data to improve app development strategies, enhance
user experience, increase downloads, and identify revenue opportunities.

# 2. Business requirements
• Find popular app categories and most-installed apps.

• Understand factors associated with high app ratings.

• Compare free and paid apps.

• Explore app size, price, installs and reviews.

• Analyse update activity and review sentiment.

• Present findings with visualisations and recommendations.

# 3. Tools and technologies
• Python: main analysis language.

• Jupyter Notebook: execute and document the analysis.

• Pandas: load, clean, filter, group and aggregate data.

• NumPy: numerical operations.

• Matplotlib / Seaborn: charts and statistical visualisations.

# 4. Challenges faced
• Mixed formats in installs, price, reviews and app size.

• Missing ratings, app metadata and review sentiment.

• Malformed category value and duplicate records.

• Highly skewed install counts.

• Interpreting correlations without claiming causation.

• Comparing review sentiment when many labels are missing.

# 5. Key results from the notebook
• Average app rating: 4.19 / 5

• Unique categories: 33

• Free / Paid app records: 9,591 / 765 (1 missing type)

• Apps rated: 4.0+	6,947

• Most common content rating:	Everyone (8,382 records)

• Average app size / median: 21.29 MB / 13 MB

• Largest average app size by category:	Games (44.13 MB)

• Top category by listed installs: Game (31.54 billion)

• Apps last updated in 2018: 6,934

• Installs–rating correlation: 0.051 (very weak positive)

• Size–installs correlation: 0.169 (weak positive)

# 6. Review sentiment results
• Positive: 23,998

• Negative: 8,271

• Neutral: 5,163

• Missing sentiment: 26,863

# 7. Recommendations
• Use negative review themes to prioritise fixes and improve user experience.

• Benchmark high-performing categories, while checking app counts and review volume.

• Optimise app size alongside speed and functionality; size alone does not explain installs.

• Evaluate free/paid pricing using adequate sample sizes.

• Monitor update activity and user feedback after releases.

• Improve sentiment coverage and report missing sentiment separately.
