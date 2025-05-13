# CNAVendorTypeStats

CVE Stats By CNA Vendor Type

## Overview

This project analyzes Common Vulnerabilities and Exposures (CVE) data to generate statistics based on CNA (CVE Numbering Authority) vendor types. It processes CVE data from a GitHub repository and merges it with a CNA list to produce insights such as the frequency of CVEs by CNA type.

## Features

- Downloads and processes CVE data from the [CVEProject GitHub repository](https://github.com/CVEProject/cvelistV5).
- Merges CVE data with a CNA list to categorize and analyze CVEs by vendor type.
- Generates visualizations for CVE statistics, including frequency by CNA type.

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/CNAVendorTypeStats.git
   cd CNAVendorTypeStats
   ```

2. **Install Dependencies**
   Ensure you have Python installed. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib tqdm requests
   ```

3. **Download CVE Data**
   Run the notebook `Data.ipynb` to download and process CVE data from the GitHub repository.

4. **Process and Analyze Data**
   Use the notebook `CNAStatsByType.ipynb` to process the data and generate statistics.

## Usage

1. Open the notebooks in your preferred Jupyter environment (e.g., VS Code, JupyterLab).
2. Run the cells in `Data.ipynb` to download and prepare the CVE data.
3. Run the cells in `CNAStatsByType.ipynb` to analyze the data and generate visualizations.

## Output

- **Processed Data**: Merged and cleaned data in a Pandas DataFrame.
- **Visualizations**: Bar charts showing CVE frequency by CNA type.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
