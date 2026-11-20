# Kerala Gyms Data Collection & ETL (Python)

A paginated API pipeline that collects gym listings across **8 Kerala cities** via the Google Maps API (SerpApi), then cleans, deduplicates and profiles the data before analysis.

## Pipeline

1. **Collect**: 57 paginated API requests across Ernakulam, Kannur, Kochi, Kollam, Kozhikode, Malappuram, Thiruvananthapuram and Thrissur
2. **Clean**: 1,092 raw records deduplicated to **891 unique listings**
3. **Profile**: data-quality profiling in Pandas (for example, 65% of listings had no website)
4. **Analyse**: city-level analysis of gym supply and engagement in Matplotlib

## Findings

- Kochi has the most unique gym listings (172), Kannur the fewest (38)
- Review counts are heavily concentrated: the top gyms cross 3,000 reviews while most listings sit far below

![Unique gym listings by city](assets/gyms-by-city.png)
![Top 10 gyms by number of reviews](assets/top-gyms-reviews.png)

## Tools

Python (Pandas, SerpApi, Matplotlib), Jupyter Notebook

## What it demonstrates

Real-world API data collection with pagination and deduplication, honest data-quality profiling, and exploratory analysis that answers a concrete question.
