# IS537 Final Project: Evaluating Data Quality in EPA Air Quality Data

## 📌 Overview

This project analyzes the quality and reliability of EPA Air Quality System (AQS) datasets. The goal is to evaluate how data quality issues affect the **fitness-for-use** of pollution data used for environmental and public health analysis.

We focus on identifying inconsistencies, missing data, and integration challenges across datasets, and assess how these issues impact downstream analysis.

---

## 📊 Datasets Used

1. **Annual Concentration by Monitor (2025)**

   * Contains annual pollution measurements across monitoring sites in the U.S.
   * Includes pollutant statistics, geographic identifiers, and measurement details

2. **EPA Monitoring Site Metadata (aqs_sites.csv)**

   * Contains metadata about monitoring locations
   * Includes latitude, longitude, land use, and site characteristics

---

## 🎯 Project Objectives

* Evaluate data quality across five key dimensions:

  * **Completeness** (missing values)
  * **Consistency** (matching identifiers across datasets)
  * **Validity** (plausible pollutant values)
  * **Uniqueness** (duplicate records)
  * **Coverage** (geographic distribution)

* Perform dataset integration and assess:

  * Matching success between datasets
  * Impact of missing or inconsistent data

---

## ⚙️ Methods & Workflow

1. **Data Profiling**

   * Summary statistics and structure analysis
   * Missing value assessment

2. **Quality Assessment**

   * Duplicate detection
   * Outlier and invalid value checks
   * Identifier consistency checks

3. **Data Integration**

   * Merging datasets using State, County, and Site identifiers
   * Evaluating match rates across datasets

4. **Impact Analysis**

   * Measuring how data cleaning decisions affect results
   * Identifying limitations in geographic and environmental analysis

---

## 🔍 Key Findings (So Far)

* Approximately **78% of records successfully matched** across datasets
* Around **22% of pollution records lack corresponding site metadata**
* Data inconsistencies (naming conventions and data types) required preprocessing before integration

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy

---

## 📁 Repository Structure

* `IS537_FirstDraftCleaning.ipynb` → First Draft of cleaning datasets
* `aqs_sites.csv` → Site metadata dataset
* `annual_conc_by_monitor_2025.csv` → Pollution dataset
* `IS537_Progress_UpdatedCode.ipynb` → Organised cleaning and analysis of the datasets
* `IS537_Progress_Report.pdf` → Current Progress Report of the Project

---

## 👩‍💻 Authors

* Smruti Singh
* Anupama Singh

---

## 📎 References

* U.S. Environmental Protection Agency (EPA) – Air Quality System (AQS) Data
  https://aqs.epa.gov
