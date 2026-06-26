# Renewable Energy Adoption & Climate Change Response Visualization

## Description
This project focuses on the data integration, dimensional modeling, and interactive visualization of a synthesized **Renewable Energy Adoption Dataset**[cite: 10, 21]. The dataset compiles authoritative global energy metrics from sources such as the International Energy Agency (IEA), the World Bank, and the United Nations Environment Programme (UNEP)[cite: 13].

The core objective of this project is to transform raw, multi-dimensional data into actionable business intelligence by evaluating trends in renewable investments, energy production capacity, and subsequent job creation across varying geographic regions over time[cite: 11, 14].

### Background & Architecture
To support clean dashboard performance and structured data analytical capabilities, this project implements a complete data warehouse design workflow[cite: 30, 33]:
* **Dimensional Modeling:** A Star Schema framework separating informational attributes into specialized dimension tables surrounding a central Fact Table[cite: 27].
* **Data Mart Design:** Targeted optimization of data structures to answer two critical operational queries efficiently[cite: 29]:
    1. *Total Energy Production by Source by Geography* [cite: 16]
    2. *Trends in Energy Production by Year by Source Type* 
* **Interactive Visualization:** A functional Tableau Dashboard exploring these data marts dynamically via custom filters, tooltips, and calculated fields[cite: 32, 33].

### Key Features
* **Geographic Analysis:** Geographic mapping of total energy production segmented by specific renewable types (e.g., Solar, Wind, Hydro)[cite: 14, 16].
* **Temporal Trend Tracking:** Line and area chart timelines analyzing production velocity and investment impacts over sequential years[cite: 14, 17].
* **Interactive Drills:** User-driven dashboard filtering capabilities to slice data down by specific locations or energy inputs[cite: 14, 33].

---

## Usage

Since this project relies on packaged workbook formats for distribution, you can interact with the visualizations through the following workflows:

### Prerequisites
* **Tableau Desktop** (v2024.1 or later recommended) OR **Tableau Public** (Free)
* Alternatively, you can view the workbook online if hosted on a Tableau Public Profile.

### Opening the Project Locally
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)