🏏 IPL Analysis Dashboard

# Project Objectives

The goal of this project is to:

* Analyze historical **IPL (Indian Premier League)** data to identify patterns, trends, and key performance metrics.
* Provide cricket enthusiasts, analysts, and data scientists with **actionable insights** into team strategies, player performances, and match outcomes.
* Create an **interactive dashboard** to visualize IPL statistics in an intuitive and informative manner.

---

# Methodologies

**Data Collection & Cleaning**:

  * Utilized official IPL datasets: `matches.csv` and `deliveries.csv`.
  * Handled missing values and verified dataset integrity using `pandas`.

* **Exploratory Data Analysis (EDA)**:

  * Visualized season-wise match counts, win distributions, and toss decisions.
  * Analyzed top-performing teams, batsmen, and bowlers using `seaborn` and `matplotlib`.

* **Statistical Inference**:

  * Evaluated win patterns based on toss outcome and batting/chasing strategies.
  * Investigated head-to-head records and venue-based performance.

* **Dashboard Development**:

  * Built a user-interactive dashboard using `Streamlit` for:

    * Team-specific statistics
    * Season filters
    * Head-to-head comparisons
  * Integrated `ngrok` for secure online access to the dashboard.

---

### 🎯 Outcomes

* Uncovered significant insights such as:

  * Teams that win the toss tend to win more often (\~X% correlation).
  * Certain teams (e.g., MI, CSK) consistently outperform others.
  * Batting first vs chasing success rates across seasons.

* Developed a **Streamlit-powered web application** that:

  * Allows users to explore IPL data interactively.
  * Offers dynamic visual insights by season, team, and players.
  * Can be shared via public `ngrok` link for remote access.
