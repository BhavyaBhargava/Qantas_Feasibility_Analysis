# Qantas Airlines Strategic Analysis: Air Traffic and Bird Population  

This repository documents a case study conducted for **Qantas Airlines**, focusing on two critical strategic decisions:  

1. **Expanding flight connectivity in the USA**: Evaluating the suitability of Denver (DEN) and Atlanta (ATL) airports for a new route to enhance Qantas Airlines' connectivity to other parts of the USA.  
2. **Establishing a storage facility in Australia**: Assessing the ecological impact of potential locations (Toowoomba, QLD, and Geelong, VIC) for a storage facility, with a focus on minimizing interaction with the local swift parrot population (2023 Australian Bird of the Year).  

## Motivation and Objectives  

Qantas Airlines, as a leading player in the aviation industry, seeks to expand its operational capabilities while maintaining ecological responsibility.  

- **Need for the Study**:  
  - The airline aims to strengthen its position in the US market by selecting an airport that optimizes passenger connectivity while minimizing delays.  
  - Domestically, Qantas requires a cost-effective and environmentally conscious solution for storing aircraft during non-operational periods. The swift parrot, an endangered species, makes ecological considerations crucial for site selection.  

This case study was undertaken to provide actionable insights into these two key decisions, using data-driven methods and robust analysis.  

---

## Project Overview  

### 1. **Air Traffic Analysis**  
- **Objective**: Compare Denver (DEN) and Atlanta (ATL) airports for their potential to serve as Qantas' next hub in the USA.  
- **Data Source**: Bureau of Transportation Statistics (https://transtats.bts.gov).  
- **Key Metrics Analyzed**:  
  - Flight volume.  
  - On-time performance and delays.  
  - Number of connecting flights.  
- **Outcome**: Recommendations based on connectivity and operational efficiency are detailed in the [Air Traffic Analysis report](./reports/Air%20Traffic%20Analysis.pdf).  

### 2. **Bird Population Analysis**  
- **Objective**: Evaluate the suitability of Toowoomba and Geelong as storage facility locations, minimizing impact on swift parrots.  
- **Data Source**: Atlas of Living Australia (https://www.ala.org.au).  
- **Key Metrics Analyzed**:  
  - Swift parrot population density.  
  - Geographical and ecological factors.  
- **Outcome**: Findings on ecological risks and recommendations for the site are detailed in the [Bird Population Analysis report](./reports/Bird%20Population%20Analysis.pdf).  

---

## Repository Structure  

- **`/data`**: Raw and processed datasets used in the analysis.  
- **`/scripts`**: Code for data extraction, cleaning, and analysis.  
- **`/reports`**: Final reports documenting findings and recommendations.  
- **`/results`**: Outputs and visualizations generated during the analysis.  

---

## Technical Details  

### Tools and Technologies  
- **Programming Language**: R (version >= 4.1.0).  
- **Packages Used**:  
  - `galah`: For downloading ecological data from the Atlas of Living Australia.  
  - `tidyverse`, `data.table`: For data wrangling.  
  - `ggplot2`: For visualization.  

### Reproducibility  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
2. Run scripts in /scripts to reproduce datasets or extend the analysis.
3. View the reports in /reports for detailed findings.

### Key Findings
1. Air Traffic Analysis:
- Atlanta (ATL) demonstrates superior connectivity compared to Denver (DEN), with higher flight volumes and more connections to major hubs in the USA.

2. Bird Population Analysis:
- Geelong poses a higher ecological risk due to a larger presence of swift parrots compared to Toowoomba. This makes Toowoomba the preferable location for Qantas' storage facility.

### Acknowledgments
This study leverages open data from the Bureau of Transportation Statistics and the Atlas of Living Australia, along with R packages like galah and tidyverse. The analysis and insights presented are independently derived for Qantas Airlines' strategic planning purposes.

Licensing and Usage
This repository and its contents are strictly protected under copyright law. Unauthorized use, copying, distribution, or modification is prohibited without prior written consent from the owner.

### License Terms
- No License Granted:
  - This repository is not licensed for public or private use unless explicitly stated.
  - Unauthorized use constitutes copyright infringement.

- Prohibited Actions:
  - Forking, cloning, or replicating the repository without permission.
  - Copying or reusing code, files, or reports for any purpose.

- Legal Consequences:
  - Violators will face legal actions under applicable intellectual property laws.
