# Integrating Public Transport and Renewable Energy Datasets

## Overview
This project demonstrates how to integrate public transportation usage statistics with renewable energy production data to support urban planning in Abu Dhabi. The integrated dataset provides insights into optimizing public transport systems using renewable energy sources, aligning with sustainability goals.

## Requirements
- Python 3.7+
- Pandas
- json

## Installation
1. Clone the repository:
   bash
   git clone <repository_url>
   
2. Navigate to the project directory:
   bash
   cd <project_directory>
   
3. Install the required packages:
   bash
   pip install pandas
   

## Usage
1. Ensure the `Public_Transportation_Usage_Statistics.csv` and `Renewable_Energy_Production_Data.json` files are in the project directory.
2. Run the integration script:
   bash
   python integrate_datasets.py
   
3. Review the output to analyze the integration results.

## Data Processing
- The public transportation data is read from a CSV file and analyzed to determine peak travel times and popular routes.
- The renewable energy data is loaded from a JSON file and processed to extract monthly production figures.
- The datasets are merged to allow for analysis of public transport usage in conjunction with energy production.

## Analysis
The integration provides insights into potential optimizations in public transport services by aligning them with renewable energy production patterns, supporting sustainable urban development initiatives.

## Contributing
Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details.