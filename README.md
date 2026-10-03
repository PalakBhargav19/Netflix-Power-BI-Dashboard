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

![Page 1 - Overview](Page-1%20Overview.png)


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

![Page 2 - Content Analysis](Page-2%20Content%20-Analysis.png)

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

![Page 3 - Trends](Page-3%20Trends.png)


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

![Page 4 - Regional Analysis](Page-4%20Regional-Analysis.png)

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

![Page 5 - Insights](Page-5%20Insights.png)

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

![Page 6 - Country Analysis](Page-6%20Country%20Analysis.png)

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

**🔍 Drill-Through:**  
Users can select a country from the dashboard and **drill through to the detailed Country Analysis page** to explore country-specific content, including content type, genres, and title-level information.

### Highlight

This page demonstrates Power BI drill-through from regional analysis to country and title-level information.

---

## 7️⃣ Page 7 — Content Analysis: Year → Month → Title

**Purpose:** Provides time-based drill-through analysis.

![Page 7 - Title Analysis](Page-7%20Title-%20Analysis.png)

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

**🔍 Drill-Through:**  
Users can select a specific title from the dashboard and **drill through to the Title Analysis page** to view detailed information related to that selected title.

The drill-through functionality makes it possible to move from **high-level dashboard insights to detailed title-level analysis** without manually searching through the dataset.

### Highlight

The page allows users to examine how content is distributed across months and explore individual titles within the selected time context.

---

## 8️⃣ Page 8 — Content Analysis: Category → Genre → Title

**Purpose:** Provides detailed category and genre analysis.

![Page 8 - Content Details](Page-8%20Content-Details.png)

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

# 🚀 How to Use

### Option 1 – Open the Power BI Dashboard

1. Download the `NETFLIX PROJECT.pbix` file from this repository.
2. Open the file using **Microsoft Power BI Desktop**.
3. Explore the interactive dashboard using slicers, filters, charts, and drill-through pages.
4. Use the different dashboard pages to analyze Netflix content by category, genre, country, region, year, rating, and title.

### Option 2 – Explore Dashboard Screenshots

Open the `Dashboard-Screenshots` folder to view all 8 dashboard pages without opening Power BI.

---

# 📊 Dashboard Page Summary

| Page | Analysis |
|---|---|
| Page 1 | Content Overview |
| Page 2 | Global Content Insights |
| Page 3 | Content Growth & Trends |
| Page 4 | Audience & Content Category |
| Page 5 | Executive Business Intelligence |
| Page 6 | Region → Country → Title |
| Page 7 | Year → Month → Title |
| Page 8 | Category → Genre → Title |

---

# 📁 Repository Structure


Netflix-Power-BI-Dashboard/
│
├── Dataset.csv
├── NETFLIX PROJECT.pbix
├── README.md
│
└── Dashboard-Screenshots/
    ├── Page-1-Overview.png
    ├── Page-2-Content-Analysis.png
    ├── Page-3-Trends.png
    ├── Page-4-Regional-Analysis.png
    ├── Page-5-Insights.png
    ├── Page-6-Country-Analysis.png
    ├── Page-7-Title-Analysis.png
    └── Page-8-Content-Details.png
---


## 👩‍💻 Author

**Palak Bhargav**  
B.Tech Computer Science & Artificial Intelligence

- 🔗 **GitHub:** [{https://github.com/PalakBhargav19}]
- 💼 **LinkedIn:** [https://linkedin.com/in/palak-bhargav-1296a42]

---

## ⚠️ Disclaimer

This project is created for **educational, portfolio, and data analytics practice purposes**.

The Netflix dataset used in this project is publicly available and is used only for learning and visualization purposes. The analysis, insights, and visualizations presented in this dashboard are based on the available dataset and should not be considered official Netflix statistics.

This project is an independent work and is **not affiliated with, endorsed by, or officially associated with Netflix, Inc.**

All trademarks, logos, and brand names belong to their respective owners.
