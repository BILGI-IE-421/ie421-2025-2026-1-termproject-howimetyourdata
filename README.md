# IE 421 - Data Science for Engineers Term Project

## US Flight Data Analysis: Delay Propagation and Operational Congestion
This project investigates operational inefficiencies and delay propagation within the aviation industry using the extensive 2015 U.S. Flight Delays and Cancellations dataset. By analyzing over 5.8 million flight records, our team explores how minor disruptions escalate into systemic issues across major transportation hubs. The research is structured around three primary questions: the cumulative "Snowball Effect" during daily aircraft rotations, the identification of temporal bottlenecks through high-density traffic windows, and the development of predictive frameworks for arrival delays. Utilizing advanced Python libraries and Git LFS for efficient large-scale data management, we implemented a dual-visualization strategy consisting of static hexagonal jointplots and interactive dashboards to monitor monthly congestion thresholds. Furthermore, we constructed a Multiple Linear Regression (OLS) model to quantify the relationship between departure metrics and arrival punctuality. Our findings demonstrate a strong predictive power with a remarkably high R-squared value of 0.926, indicating that arrival delays are highly predictable based on early-stage departure indicators like taxi-out time and initial gate delays. Ultimately, this repository serves as a comprehensive demonstration of data science methodologies applied to real-world engineering challenges, offering actionable insights for optimizing flight schedules and enhancing operational flexibility.

## Student Names
* Alp Deniz Batuhan (123203096)
* Emir Buğra Çakır (123203102)
* Beste Eren (122203049)
* Tuana Şen (122203052)

## Files
- `data/`: Contains the 2015 U.S. Flight Delays and Cancellations dataset, managed using Git LFS due to its 600MB size.
- `visuals/`: Includes generated visualization images such as the RQ1 snowball effect matrix, RQ2 temporal jointplot, and RQ3 regression results.
- `scripts/`: Python scripts that utilize the `kagglehub` library for automated data acquisition and perform the OLS regression analysis.
- `index.html`: The main webpage designed for GitHub Pages hosting, providing an interactive dashboard and report for our project analysis.

## Hosting
The project is hosted using GitHub Pages: (https://bilgi-ie-421.github.io/ie421-2025-2026-1-termproject-howimetyourdata)
