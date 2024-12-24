# Project Resources Overview

Below is an overview of the files and datasets used for the **DOHMH NYC Restaurant Inspection Analysis** project:

---

## 1. **ri-violation-penalty.pdf**
- **Content**: This file contains a comprehensive list of violations, penalties, and conditions as defined in the NYC Health Code for food service establishments.  
- **Purpose**: Used to identify the specific violation codes, categorize them (e.g., Public Health Hazard or Critical), and understand the associated penalties for each condition level (I-V).  
- **Relevance**: Helps link violation types to their severity and monetary penalties in the analysis.

---

## 2. **blue-book.pdf**
- **Content**: A guide for food service operators that outlines the NYC health inspection process, scoring system, and sanitation guidelines.  
- **Purpose**: Provides detailed explanations of critical and general violations, scoring parameters, and the restaurant grading system (A, B, or C).  
- **Relevance**: Serves as a reference to interpret inspection scores, understand what inspectors look for, and analyze how violations impact grades.

---

## 3. **About_NYC_Restaurant_Inspection_Data_on_NYC_OpenData_050222.docx**
- **Content**: A technical guide explaining the structure of the NYC Restaurant Inspection dataset, including the meaning of fields, adjudication processes, and grading logic.  
- **Purpose**:  
   - Clarifies how the dataset is updated and structured.  
   - Provides SQL and R examples for calculating grades from the dataset.  
   - Explains key concepts like gradable inspections, adjudication, and score-to-grade mapping.  
- **Relevance**: Essential for cleaning and preparing the dataset, ensuring accurate analysis and correct interpretation of results.

---

## 4. **RestaurantInspectionDataDictionary_09242018.xlsx**
- **Content**: A data dictionary explaining each column and allowable values in the NYC restaurant inspection dataset.  
- **Purpose**: Used to identify and understand the meaning of fields such as violation codes, inspection scores, grades, inspection types, and other metadata.  
- **Relevance**: Guides the data cleaning and preparation process for analysis.

---

## 5. **DOHMH_New_York_City_Restaurant_Inspection_Results_20241118.csv**
- **Content**: The primary dataset containing inspection results for NYC restaurants, including scores, violation details, and grades.  
- **Purpose**: Serves as the core dataset for analysis, enabling you to analyze trends, identify violations, and assess restaurant performance.  
- **Relevance**: Provides raw data to generate insights, such as the most common violations, grade distributions, and borough-level comparisons.

---

## 6. **dohmh_nyc_report.pdf**
- **Content**: A comprehensive report analyzing NYC’s restaurant health inspections over the past five years, detailing key trends, operational inefficiencies, and actionable insights.  
- **Purpose**:  
   - Highlights common violations, borough trends, cuisine-specific insights, and seasonal patterns.  
   - Provides recommendations to improve compliance, streamline inspections, and enhance public health.  
- **Relevance**: Serves as an analytical summary for policymakers, restaurant owners, and public health officials, complementing the dataset analysis with narrative insights and visualization.

---

This overview documents the key resources utilized for analyzing NYC restaurant inspections, linking data sources, technical guides, and violation references to ensure an accurate and insightful analysis.
