# Data Wrangling Examples

This repository contains practical examples of data wrangling using Python. The Jupyter notebooks in this repository demonstrate techniques for cleaning, restructuring, and transforming messy datasets into analyzable formats.

## Repository Structure

- **`data/`**: Contains datasets used in the examples:
  - `Badly-Structured-Sales-Data-*.xlsx` (1 to 4): Sales data with inconsistent formats.
  - `Hospital-Data-with-Mixed-Numbers-and-Characters.xlsx`: Mixed numerical and textual data.
  - `Invoices-with-Merged-Categories-and-Merged-Amounts.xlsx`: Invoices with merged fields.
  - `Jumbled-up-Customers-Details.xlsx`: Disorganized customer details.
  - `Medicine-Data-with-lumped-Quantity-and-Measure.xlsx`: Data with combined quantity and measurements.

- **Notebooks**: Jupyter notebooks showcasing data wrangling techniques:
  - `Data-Wrangling-Example-1.ipynb`: Data Transformation (Rows, Columns, and Merge) with `Badly-Structured-Sales-Data-1.xlsx`
  - `Data-Wrangling-Example-2.ipynb`: Data Transformation (Rows, Columns, and Merge) with `Badly-Structured-Sales-Data-2.xlsx`
  - `Data-Wrangling-Example-3.ipynb`: Data Transformation (Rows, Columns, and Merge) with `Badly-Structured-Sales-Data-3.xlsx`
  - `Data-Wrangling-Example-4.ipynb`: Data Transformation (Rows, Columns, and Merge) with `Badly-Structured-Sales-Data-4.xlsx`
  - `Data-Wrangling-Example-5.ipynb`: Data Cleaning (Mixed numbers and Characters) with `Hospital-Data-with-Mixed-Numbers-and-Characters.xlsx`
  - `Data-Wrangling-Example-6.ipynb`: Data Transformation (Combined categories and amounts) with `Invoices-with-Merged-Categories-and-Merged-Amounts.xlsx`
  - `Data-Wrangling-Example-7.ipynb`: Data Transformation (All details in a single column) with `Jumbled-up-Customers-Details.xlsx`
  - `Data-Wrangling-Example-8.ipynb`: Data Cleaning (Combined characters and measures) with `Medicine-Data-with-lumped-Quantity-and-Measure.xlsx`

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy openpyxl jupyter
   ```
3. Open and run the notebooks:
   ```bash
   jupyter notebook
   ```

## Techniques Demonstrated

- Data Transformation: Handling rows, columns, and merging datasets.
- Data Cleaning: Managing mixed numbers and characters, dealing with merged fields, and fixing combined quantities and measures.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
