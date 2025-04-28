# Crash Data Analysis Project

## Description

This project analyzes a provided dataset related to vehicle crashes. The primary goal was to address 8 specific analytical questions posed in a business request simulation, demonstrating data cleaning, manipulation, analysis, and interpretation skills using Python. Additional insights beyond the specific requests were also explored.

The analysis covers various aspects including:
*   Fatalities and injuries associated with crashes.
*   Vehicle types and makes involved.
*   Contributing factors (e.g., alcohol, speeding).
*   Demographic factors (gender, driver license status).
*   Geographic proxies (driver ZIP code, vehicle license state).
*   Vehicle damage and insurance status.

## Data Source

The analysis utilizes multiple CSV files provided for the project, including (but not limited to):

*   `Units.csv`
*   `Primary_Person.csv`
*   `Charges.csv`
*   `Damages.csv`
*   `Endorse.csv`
*   `Restrict.csv`

**Note:** The code expects these data files to be located within a `/data/` subdirectory relative to the main Jupyter Notebook file. A data dictionary explaining the fields was also provided and used for understanding the data structure and codes.

## Requirements

To run the analysis notebook, you need Python and several libraries. It's recommended to use a virtual environment.

*   Python 3.8+
*   Libraries:
    *   pandas
    *   numpy
    *   matplotlib
    *   seaborn

You can install the required libraries using pip:
```bash
pip install -r requirements.txt
