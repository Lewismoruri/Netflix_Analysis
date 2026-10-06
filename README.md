# A Data Story of Netflix's Movies and TV Shows

An exploratory data analysis and interactive Excel dashboard examining how Netflix's library of movies and TV shows changed over time, where titles came from, and how the mix of content evolved between 2010 and 2021.

## Project Overview

Netflix has grown into one of the world's largest streaming platforms, with a library spanning movies and TV shows from many countries and genres.

But what does that growth actually look like in the data?

This project explores the Netflix Titles dataset to answer a few simple questions:

- How did the number of movies and TV shows released change over time?
- Is Netflix's library more heavily made up of movies or TV shows?
- Which countries are most represented in the dataset?
- What ratings are most common across the library?
- What happened to release activity around 2020 and 2021?

The goal was not just to build charts, but to turn a raw dataset into a clear and interactive data story.

---

## Dashboard

The final dashboard was built in Microsoft Excel using PivotTables, PivotCharts, and slicers.

It allows the user to explore Netflix's library between **2010 and 2021** and compare release trends, the movie/TV show mix, countries, and ratings.

### Dashboard Preview

![Netflix Dashboard](images/netflix-dashboard.png)

> Replace `images/netflix-dashboard.png` with the actual path to your dashboard screenshot in the repository.

---

## Key Questions

The analysis was guided by four main questions:

### 1. How did Netflix's releases change over time?

The number of titles increased considerably throughout the 2010s, with release activity reaching its highest levels around 2018–2019.

A noticeable decline appears in 2020 and 2021. This period coincided with the disruption caused by the COVID-19 pandemic, when film and television productions were paused, delayed, and pushed back.

The data alone cannot establish COVID-19 as the only cause of the decline, but the timing is consistent with the wider disruption to global film and television production.

### 2. What makes up most of Netflix's library?

Movies make up the larger share of the dataset, accounting for roughly **71%**, while TV shows account for approximately **29%** in the analyzed data.

This gives a useful picture of the balance between the two types of titles represented in the dataset.

### 3. Which countries are most represented?

The United States stands out as the largest country associated with titles in the dataset, followed by other major contributors such as India, the United Kingdom, and Japan.

This highlights the international nature of Netflix's library and the range of countries represented across its catalog.

### 4. What ratings are most common?

The rating distribution shows a strong presence of mature audiences categories, including ratings such as **TV-MA, TV-14, and R**.

This provides another way to understand the type of audience the titles in the dataset are intended for.

---

## Data Source

The dataset used for this project is the **Netflix Titles Dataset**, sourced from Kaggle.

The dataset contains information about Netflix titles including:

- Title
- Type
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

The analysis focuses primarily on:

- `type`
- `release_year`
- `country`
- `rating`

---

## Data Cleaning & Preparation

Before building the dashboard, the dataset required cleaning and preparation.

Some of the work included:

- Reviewing missing and inconsistent values
- Cleaning fields used in the analysis
- Preparing the release year for the dashboard
- Filtering the analysis to the 2010–2021 period
- Preparing fields for PivotTables
- Creating a dashboard-specific year field
- Reviewing country and rating categories
- Building calculated summaries for the dashboard

An important part of the process was recognizing that different analyses required different cleaning and filtering steps.

Because of this, some headline figures in the dashboard are calculated from differently prepared subsets of the data and should not necessarily be expected to reconcile directly.

This is an important part of working with real-world datasets: understanding how the data was prepared is just as important as building the final visualizations.

---

## Tools & Techniques

### Tools

- Microsoft Excel
- PivotTables
- PivotCharts
- Slicers
- Excel formulas

### Techniques

- Data cleaning
- Data preparation
- Exploratory data analysis
- Aggregation
- Trend analysis
- Categorical analysis
- Dashboard design
- Data storytelling

---

## Dashboard Components

The dashboard includes:

### Release Trends
A line chart showing how movie and TV show releases changed over time.

### Movies vs TV Shows
A donut chart showing the overall distribution between movies and TV shows.

### Countries
A comparison of the countries most represented across Netflix titles.

### Ratings
A breakdown of titles by their assigned rating categories.

### Year Filter
An interactive slicer allowing the analysis to be explored between 2010 and 2021.

---

## Key Findings

A few patterns stood out during the analysis:

**Netflix's library expanded rapidly during the 2010s.**

Release activity increased significantly toward the end of the decade, reaching a peak around 2018–2019.

**Movies make up the majority of titles.**

Movies account for roughly 71% of the analyzed dataset, compared with around 29% for TV shows.

**The United States is the largest contributor.**

US-associated titles represent a substantial portion of the Netflix library captured in the dataset.

**Release activity declined around 2020–2021.**

The decline coincided with the COVID-19 pandemic and the resulting disruption to film and television production and release schedules.

**The dataset has a strong representation of mature-rated titles.**

TV-MA, TV-14, and R are among the most prominent rating categories.

---

## What I Learned

This project reinforced something important about data analysis:

**The dashboard is only the final step.**

A good visualization depends on understanding the data behind it.

During this project, I worked through the process of taking a raw dataset, deciding what questions were worth exploring, cleaning the data, preparing it for analysis, and then choosing visualizations that could communicate the results clearly.

I also learned that not every number in a dataset should automatically be combined with every other number. Different questions can require different filters and preparation steps, and those decisions need to be understood before interpreting the results.

Most importantly, the project helped me think beyond simply creating charts and focus more on **telling a story with data**.

---

## Project Structure

```text
netflix-data-story/
│
├── README.md
│
├── data/
│   └── netflix_titles.csv
│
├── dashboard/
│   └── Netflix_Dashboard.xlsx
│
├── images/
│   └── netflix-dashboard.png
│
└── analysis/
    └── ...
