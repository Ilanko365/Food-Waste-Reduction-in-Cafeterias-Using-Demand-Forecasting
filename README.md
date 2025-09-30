# Food-Waste-Reduction-in-Cafeterias-Using-Demand-Forecasting
Optimize food production and minimize waste in cafeterias using forecasting and newsvendor algorithms. Upload sales data (CSV), analyze trends, and generate optimal daily production plans—all through an interactive Shiny dashboard.
## Table of Contents
1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Technologies](#technologies)  
4. [Installation & Running](#installation--running)  
5. [CSV Format](#csv-format)  
6. [Usage Guide](#usage-guide)  
7. [Contributing](#contributing)  
8. [License](#license)
## Project Overview
This Shiny app helps cafeteria managers reduce food waste by forecasting demand and optimizing production. Users upload historical sales data in CSV format, input cost parameters for over-producing or under-producing, and the app generates actionable recommendations and charts. Output data can be downloaded as CSV for reporting or operational use.[7][2]
## Features
- Upload sales data in CSV format  
- Choose forecast horizon and cost parameters  
- Per-item and per-cafeteria analysis  
- Interactive tables and plots  
- Download optimized production schedules as CSV  
## Technologies
- R (Shiny, tidyverse, lubridate, forecast, randomForest)  
- CSV input/output  
- ggplot2 for visualization  
## Installation & Running
1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Install required R packages (from R console):
   ```r
   install.packages(c('shiny', 'tidyverse', 'lubridate', 'forecast', 'randomForest'))
   ```
3. Run the app locally:
   ```r
   shiny::runApp()
   ```
## CSV Format
**Input:**  
CSV file must have columns:
- `date` (YYYY-MM-DD)
- `cafeteria`
- `item`
- `sales`
**Output:**  
Optimized production table, downloadable as CSV with forecasted values and suggested production.
***
## Usage Guide
1. Launch the app with `shiny::runApp()`.  
2. Upload your sales CSV file.  
3. Set forecast horizon and cost parameters.  
4. Click “Run Forecast & Optimization”.  
5. View and download results from the dashboard.
***
## Contributing
Contributions welcome! Please open an issue for feature requests or bugs. Fork the repo and create a pull request for any changes.[5]
***
## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
***
**Tip:** Customize the repository name at the top and update links/usernames as needed. Expand the documentation with screenshots and sample CSV files for smoother onboarding.Here’s a complete `README.md` file example for your cafeteria food waste reduction Shiny app project:[2][7]
***
