# Agriculture Disease Analysis Dashboard

A simple, visual dashboard that helps people understand crop disease patterns across different regions and seasons.

Agriculture is the backbone of food production, but crop diseases can damage harvests and reduce income. This project turns raw agricultural disease data into easy-to-read charts, maps, and tables so that farmers, agricultural officers, researchers, and students can quickly understand what is happening and make better decisions.

## Why this project matters

Crop diseases can spread quickly and affect large areas if they are not noticed early. This dashboard helps people:

- see where disease outbreaks are happening
- understand which crops are most affected
- identify trends over time
- explore data without needing advanced technical skills
- make early decisions for prevention and treatment

## What the dashboard does

The project gives users an interactive view of crop disease data through:

- charts showing disease trends over time
- maps highlighting affected areas
- comparison of disease patterns by crop or region
- searchable tables with detailed information
- a clean and user-friendly interface

In simple terms, it turns a large amount of agricultural data into information that is easy to understand at a glance.

## Who is this for?

This dashboard is useful for:

- farmers who want to monitor crop health
- agricultural extension officers
- researchers studying disease patterns
- students learning about agriculture and data analysis
- anyone working to improve crop protection and food security

## How it works

1. Disease data is collected from different locations and crop types.
2. The app organizes and processes that data.
3. The dashboard creates visual summaries such as charts and maps.
4. Users can explore the information and identify problem areas quickly.

This makes it easier to spot disease hotspots before they become larger problems.

## Main features

- Data visualization with interactive charts
- Geographic map showing affected regions
- Filterable and searchable data tables
- User-friendly dashboard designed for exploration
- Real agricultural disease information for practical understanding

## Technologies used

This project is built using common tools for data analysis and interactive web apps:

- R Shiny: for the dashboard interface
- Plotly and Highcharter: for interactive charts
- Leaflet: for map-based visualization
- DT: for searchable and sortable tables
- Tidyverse: for cleaning and organizing data

These tools help turn raw data into a useful decision-support dashboard.

## How to run the project locally

If you want to run this dashboard on your own computer, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/legion0069/Agriculture-Disease-Analysis-Dashboard.git
cd Agriculture-Disease-Analysis-Dashboard
```

### 2. Install the required R packages

```r
install.packages(c("shiny", "plotly", "highcharter", "leaflet", "DT", "tidyverse"))
```

### 3. Start the dashboard

```r
shiny::runApp()
```

## Project goal

The goal of this project is to make agricultural disease information more understandable and actionable. Instead of looking at raw spreadsheets or scattered reports, users can see patterns clearly and respond faster.

## In one sentence

This project helps people understand where crop diseases are happening, how serious they are, and what patterns may need attention before they spread further.

## Contributing

Contributions are welcome. If you want to improve the dashboard, add better visualizations, or improve the user experience, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For questions or collaboration, reach out through the project owner on GitHub.
