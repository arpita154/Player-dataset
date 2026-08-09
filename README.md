# API Data Fetching & Processing with Python

A lightweight Python/Pandas project demonstrating how to fetch paginated data from an external REST API, process JSON payloads, and aggregate the structured results into a pandas DataFrame and CSV file.

## 📌 Project Overview

This notebook demonstrates a practical workflow for consuming web APIs using Python:
1. **API Requests**: Using `requests.get()` to query endpoints.
2. **JSON Parsing**: Extracting nested data structures (`response.json()['data']`).
3. **Pagination Handling**: Looping through multiple API pages to retrieve complete datasets.
4. **Data Manipulation**: Converting raw API payloads into structured [pandas](https://pandas.pydata.org/) DataFrames and selecting target fields (`id`, `name`, `country`).
5. **Data Export**: Concatenating paginated data into a unified dataset and exporting it to `players.csv`.

---

## 🛠️ Tech Stack & Requirements

- **Python 3.x**
- **Libraries**:
  - `requests`
  - `pandas`

Install the required packages:

```bash
pip install requests pandas
