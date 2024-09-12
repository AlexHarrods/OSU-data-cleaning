# The Ohio State University 2023 Combined Earnings Dataset Cleaning

This repository contains scripts and notebooks for cleaning the dataset of The Ohio State University's combined earnings for the year 2023. The purpose of this project is to prepare the data for further analysis and visualization by addressing inconsistencies, formatting issues, and missing values.

## Dataset

The dataset includes detailed earnings information for employees across various departments at Ohio State University. Key columns include:
**It contains the following columns:**
- `Last Name - Legal`: Employee's first name
- `First Name - Preferred`: Employee's last name
- `Job Profile Name`: Job title
- `Cost Center`: Cost centers
- `Cost Center Hierarchy CCH6`: Groups of cost centers
- `Position Group`: Positions associated with the Wexner Medical Center/Health System, Athletics, and the rest of the university.
- `Regular Pay (Base Pay + Paid Time Off + Premium)`: Regular pay received
- `Bonus`: Bonus amount received
- `Overtime`: Overtime pay received
- `Other (Allowance + Supplemental + Uncategorized)`: Other compensations
- `Gross Pay`: Total gross pay received
  

## Project Structure

1. **Import Necessary Libraries**: Scripts to load the required Python libraries.
2. **About the Dataset**: Description and metadata of the dataset.
3. **Load the Dataset**: Script to load data from CSV files.
4. **Overview of the Dataset**: Initial exploration and structure of the dataset.
5. **Rename Columns**: Standardizing column names for ease of use.
6. **Numerical Values Analysis**: Detailed analysis of the numerical columns in the dataset.
7. **Find Duplicates**: Script to identify and remove duplicate entries.
8. **Names Consistency Check**: Ensuring all names are consistent and properly formatted.
9. **Create New Data Fields**: Scripts to create new fields such as full name and inferred gender.
10. **Drop Columns and Change Order**: Final adjustments to the dataset structure.

## Usage

To use these scripts:
1. Clone the repository to your local machine.
2. Ensure you have Python installed.
3. Run the scripts in the order specified above to perform the full cleaning process.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
