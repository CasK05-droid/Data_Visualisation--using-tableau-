# Renewable Energy Adoption & Climate Change Response Visualization

## Description
This project focuses on the data integration, dimensional modeling, and interactive visualization of a synthesized **Renewable Energy Adoption Dataset**. The dataset compiles authoritative global energy metrics from sources such as the International Energy Agency (IEA), the World Bank, and the United Nations Environment Programme (UNEP).

The core objective of this project is to transform raw, multi-dimensional data into actionable business intelligence by evaluating trends in renewable investments, energy production capacity, and subsequent job creation across varying geographic regions over time.

### Background & Architecture
To support clean dashboard performance and structured data analytical capabilities, this project implements a complete data warehouse design workflow:
* **Dimensional Modeling:** A Star Schema framework separating informational attributes into specialized dimension tables surrounding a central Fact Table
* **Data Mart Design:** Targeted optimization of data structures to answer two critical operational queries efficiently:
    1. *Total Energy Production by Source by Geography* 
    2. *Trends in Energy Production by Year by Source Type* 
* **Interactive Visualization:** A functional Tableau Dashboard exploring these data marts dynamically via custom filters, tooltips, and calculated fields.

### Key Features
* **Geographic Analysis:** Geographic mapping of total energy production segmented by specific renewable types (e.g., Solar, Wind, Hydro).
* **Temporal Trend Tracking:** Line and area chart timelines analyzing production velocity and investment impacts over sequential years.
* **Interactive Drills:** User-driven dashboard filtering capabilities to slice data down by specific locations or energy inputs.

---

## Usage

Since this project relies on packaged workbook formats for distribution, you can interact with the visualizations through the following workflows:

### Prerequisites
* **Tableau Desktop** (v2024.1 or later recommended) OR **Tableau Public** (Free)
* Alternatively, you can view the workbook online if hosted on a Tableau Public Profile.

### Opening the Project Locally
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/CasK05-droid/Data_Visualisation--using-tableau-.git](https://github.com/CasK05-droid/Data_Visualisation--using-tableau-.git)

2. Alternatively you can download Tableau file.
