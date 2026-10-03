# 🎬 Netflix Content Analytics Dashboard | Power BI

An interactive **8-page Netflix Content Analytics Dashboard** built with **Microsoft Power BI** to explore Netflix movies and TV shows through content, country, region, genre, rating, release-year, and title-level analysis.

The project uses a Netflix titles dataset and combines **Power Query, Power BI visuals, interactive slicers, drill-through pages, KPI cards, and analytical insights** in a Netflix-inspired dark/red dashboard design.

---

## 📌 Project Overview

This project analyzes Netflix's content library and converts raw title-level data into an interactive business intelligence dashboard.

The dashboard allows users to:

- Compare Movies and TV Shows
- Analyze Netflix content growth over the years
- Explore content distribution by country and region
- Analyze ratings and genres/categories
- View title-level details
- Drill through from high-level analysis to detailed country, year, month, category, genre, and title views
- Interactively filter the dashboard using slicers

---

## 🎯 Project Objectives

1. Understand the overall distribution of Netflix content.
2. Compare Movies and TV Shows.
3. Analyze content growth by release year.
4. Identify major Netflix content regions and countries.
5. Explore ratings and genre/category patterns.
6. Provide detailed title-level analysis.
7. Demonstrate interactive Power BI drill-through functionality.
8. Present data-driven insights through a professional dashboard.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Power BI Desktop** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and analytical calculations |
| **CSV Dataset** | Source Netflix titles data |
| **GitHub** | Project versioning, documentation and portfolio |

---

## 📊 Dataset

The dashboard is based on a Netflix titles dataset containing information about movies and TV shows.

### Main Dataset Fields

- `show_id` — Unique identifier for each title
- `type` — Movie or TV Show
- `title` — Title name
- `director` — Director information
- `country` — Country associated with the title
- `date_added` — Date the title was added
- `release_year` — Original release year
- `rating` — Content rating
- `duration` — Movie duration or number of seasons
- `listed_in` — Genre/category information

### Additional Analytical Fields Used in the Power BI Model

- `Region`
- `Region Share %`
- `Movie Share`
- `Selected Year`
- `Total Movies`
- `Total Titles`
- `Year`
- `Yearly Growth %`

---

## 🧹 Data Cleaning & Preparation

The dataset was prepared in **Power Query** before dashboard development.

The data preparation process included:

- Checking column quality
- Identifying errors and incomplete values
- Cleaning relevant fields
- Correcting data types
- Preparing date and year fields
- Creating a date hierarchy for Year, Quarter, Month and Day
- Preparing country and regional fields for geographical analysis
- Preparing genre/category fields for content analysis
- Validating the cleaned dataset before visualization

---

# 📑 Dashboard Pages

## 1️⃣ Page 1 — Content Overview Dashboard

**Purpose:** Provides a high-level overview of the Netflix content library.

### Key KPIs

- Total Titles
- Total Movies
- Total TV Shows
- Average Release Year

### Visuals

- Movies vs TV Shows
- Netflix Content by Release Year
- Top Netflix Genres by Number of Titles
- Release-year distribution
- Type, Release Year and Country slicers

### Highlight

This page acts as the main overview of the complete Netflix dataset and provides quick access to the major content metrics.

---

## 2️⃣ Page 2 — Global Content Insights Dashboard

**Purpose:** Analyzes Netflix content distribution across countries and regions.

### Key KPIs

- Total Countries
- Total Titles
- Total Movies
- Total TV Shows

### Visuals

- Content Distribution by Country
- Top 10 Countries by Number of Titles
- Content by Region
- Content Type by Region
- Key Insights panel

### Interactive Filters

- Type
- Release Year
- Country

### Highlight

The page combines geographical analysis with regional and content-type comparisons.

---

## 3️⃣ Page 3 — Content Growth & Trend Analysis

**Purpose:** Explores how Netflix content has changed over time.

### Key KPIs

- Total Titles
- Average Release Year
- Latest Release Year
- Year Growth

### Visuals

- Netflix Content Growth Over the Years
- Yearly Content by Type
- Content Growth by Region (2010–2021)
- Key Insights

### Interactive Filters

- Release Year
- Type
- Country
- Genre

### Highlight

This page focuses on historical content trends and regional growth patterns.

---

## 4️⃣ Page 4 — Audience & Content Category Intelligence Dashboard

**Purpose:** Provides deeper analysis of ratings, categories, genres and content types.

### Key KPIs

- Total Titles
- Total Movies
- Total TV Shows
- Common Rating

### Visuals

- Content by Rating
- Movies vs TV Shows
- Content by Category & Genre
- Content Growth by Release Year
- Rating-wise Movies vs TV Shows
- Content Growth by Region
- Key Insights

### Interactive Filters

- Type
- Rating
- Release Year
- Country

### Navigation

The page includes navigation sections for:

- Overview
- Audience
- Categories
- Ratings
- Trends
- Insights

---

## 5️⃣ Page 5 — Executive Business Intelligence Dashboard

**Purpose:** Presents the major Netflix metrics and analytical findings in an executive-style dashboard.

### Key KPIs

- Total Titles
- Total Movies
- Total TV Shows
- Movie Share

### Visuals

- Movies vs TV Shows
- Content Growth by Release Year
- Content by Rating
- Content Distribution by Region
- Region Share %
- Content Growth by Type

### Interactive Filters

- Type
- Rating
- Release Year
- Country
- Genre/Category

### Drill-Through Navigation

The dashboard provides drill-through options for:

- **Region → Country → Title**
- **Year → Month → Title**
- **Category → Genre → Title**

### Highlight

This page acts as an executive summary and connects high-level analysis with detailed drill-through exploration.

---

# 🔎 Drill-Through Analysis

The project contains dedicated drill-through pages that allow users to move from summary-level information to detailed title-level analysis.

---

## 6️⃣ Page 6 — Drill-Through Analysis: Region → Country → Title

**Purpose:** Provides detailed analysis after selecting a region, country or title.

### Selected Filters

- Region
- Country
- Title

### KPIs

- Total Titles
- Total Movies
- Total TV Shows
- Average Rating

### Visuals

- Content by Country
- Content by Type
- Content by Country / Genre
- Title Details table

### Title Details Include

- Title
- Country
- Type
- Release Year
- Rating
- Duration
- Director

### Highlight

This page demonstrates Power BI drill-through from regional analysis to country and title-level information.

---

## 7️⃣ Page 7 — Content Analysis: Year → Month → Title

**Purpose:** Provides time-based drill-through analysis.

### Selected Filters

- Year
- Country
- Title

### KPIs

- Total Titles
- Total Movies
- Total TV Shows
- Average Rating

### Visuals

- Content by Rating
- Content by Type
- Movies vs TV Shows Trend
- Title Details

### Highlight

The page allows users to examine how content is distributed across months and explore individual titles within the selected time context.

---

## 8️⃣ Page 8 — Content Analysis: Category → Genre → Title

**Purpose:** Provides detailed category and genre analysis.

### Selected Filters

- Category
- Genre
- Title
- Release Year
- Rating
- Country

### KPIs

- Total Titles
- Total Movies
- Total TV Shows
- Average Rating

### Visuals

- Content by Type
- Genre Distribution
- Top Genres by Title
- Title Details
- Key Insights

### Highlight

This page connects category and genre analysis with individual title-level information.

---

# 📈 Key Metrics

The completed dashboard displays metrics such as:

- **Total Titles:** 8.791K
- **Total Movies:** 6.126K
- **Total TV Shows:** 2.664K
- **Movie Share:** approximately 69.7%
- **Total Countries:** 88
- **Average Release Year:** 2014
- **Latest Release Year:** 2021

> Values can change depending on slicer selections and drill-through context.

---

# 💡 Key Insights

The dashboard enables analysis of several important patterns:

- Movies form the larger share of the Netflix titles represented in the dataset.
- TV Shows represent a smaller portion of the overall title count.
- Netflix content is distributed across multiple countries and regions.
- North America represents a major share of the analyzed regional content.
- The dataset shows a strong increase in content around the later release years.
- Drama-related and documentary-related categories appear prominently in the genre analysis.
- Ratings provide another way to compare and understand Netflix content.
- Drill-through pages allow high-level results to be investigated at country, year, category, genre and title levels.

---

# 🎨 Dashboard Design

The dashboard follows a **Netflix-inspired dark visual theme**.

### Design Elements

- Black/dark background
- Netflix-style red accent elements
- White KPI values
- Red charts and highlights
- Dark slicers and filter panels
- Netflix-themed visual backgrounds
- Consistent page navigation
- Interactive drill-through experience

The design was created to provide a visually consistent experience across all eight report pages.

---

# 🔄 Interactive Features

The Power BI report includes:

- Slicers
- Cross-filtering
- KPI cards
- Interactive charts
- Page navigation
- Drill-through
- Title detail tables
- Country analysis
- Region analysis
- Year and month analysis
- Category and genre exploration

---

# 📂 Repository Structure

```text
Netflix-PowerBI-Dashboard/
│
├── Netflix_Dashboard.pbix
├── netflix_titles.csv
├── README.md
│
└── Screenshots/
    ├── page1-content-overview.png
    ├── page2-global-content-insights.png
    ├── page3-content-growth-trends.png
    ├── page4-audience-content-category.png
    ├── page5-executive-business-intelligence.png
    ├── page6-region-country-title.png
    ├── page7-year-month-title.png
    └── page8-category-genre-title.png
