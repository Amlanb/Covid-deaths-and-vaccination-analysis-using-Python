# Covid-deaths-and-vaccination-analysis-using-Python

This project analyzes COVID-19 case data using different algorithms to evaluate sorting performance, trend identification, and pattern detection. I used structured data from the Covid Combined dataset and implemented efficient sorting techniques to gain insights into pandemic trends.

# Algorithms Used:

I implemented and analyzed:

•	Heap Sort – Used to efficiently sort the dataset by total_cases in descending order. It is ideal for ranking countries/regions based on case counts.
•	Sliding Window Technique – Applied to compute the 7-day moving average of new cases as it provides a smoothed trendline for new cases.
•	Kadane’s Algorithm – Used to find the period with the highest surge in cases as it efficiently finds periods of peak outbreaks.
•	Longest Increasing Subsequence (LIS) – Identified the longest period of continuous case increase because it helps determine the longest phase of continuous increase.
•	Topological Sorting – Applied for analyzing the chronological order of peak cases. It organizes events based on dependencies in case spikes.

# Dataset

The dataset consists of:
•	total_cases, new_cases, deaths_location, date.
•	Time-series data for multiple regions, requiring cleaning and transformation.
•	Missing values were handled using data imputation strategies, ensuring accurate trend analysis.

# Graphical Analysis:

The graphs generated illustrate performance trends across different regions and timeframes. Case spikes, prolonged surges, and vaccination impact were visually analyzed.

# Inference & Learning Outcomes

•	Sorting Techniques Enhance Data Insights: Heap Sort proved optimal for case ranking.
•	Time-Series Algorithms Provide Meaningful Trends: The Sliding Window technique smoothed fluctuations.
•	Peak Detection is Critical: Kadane’s Algorithm efficiently highlighted surge periods.
•	Pandemic Phases are Identifiable: LIS and Topological Sorting structured pandemic shifts.

# Conclusion

This project provided valuable insights into pandemic trends using algorithmic approaches. Understanding how sorting and analysis techniques apply to real-world data has strengthened my ability to work with structured datasets, revealing key takeaways about outbreak patterns and data optimization strategies.
