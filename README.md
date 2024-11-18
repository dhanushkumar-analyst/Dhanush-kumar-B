# Healthcare Analysis Project

#### Dashboard link:                              https://app.powerbi.com/groups/me/reports/58bad0db-99f9-4e16-8b28-5aac62bda108/54e254632dc3a42b7219?experience=power-bi

This repository contains a Power BI project that analyzes key trends and insights in the healthcare sector. The analysis includes visualizations and metrics to assist stakeholders in making data-driven decisions.

## 🚀Features
- Interactive dashboards for healthcare insights
- Key metrics on patient demographics, hospital performance, and service quality
- Data visualizations showcasing trends and anomalies
- Exported reports for sharing with decision-makers

## 📈Step by Step Process
### Load Data:

- Navigate to the Transform Data tab.
- Connect to the dataset or update file paths for local data sources.
- Validate and refresh data.
### Data Cleaning:

- Remove duplicate or inconsistent records.
- Handle missing data by appropriate methods (e.g., imputation or removal).
### Data Analysis:

- Create calculated columns or measures using DAX (e.g., patient recovery rates).
- Filter and sort data to identify key trends.
### Dashboard Creation:

#### Design visualizations for:
#### Summary:
- **Total Waiting List Commparison:** Commparison between Latest Month Waiting List and Previous Latest Month Waiting List
  
![WhatsApp Image 2024-11-18 at 6 29 00 PM](https://github.com/user-attachments/assets/9ab0d5d2-41de-4ff7-a33c-80459bf9c397)
- **Case Type Spilt:** There are three types of case spilt.
  
![WhatsApp Image 2024-11-18 at 6 29 02 PM](https://github.com/user-attachments/assets/b5f4a69b-7ed0-42d5-beeb-045b0264a1a5)

- **Key Indicators:** It's showing a Average and Median patients waiting lists
  
![WhatsApp Image 2024-11-18 at 6 29 03 PM](https://github.com/user-attachments/assets/ac61a471-09b1-4db5-a45d-fb55d2f6470f)

- **Time band vs. Age Profile:** The chart uses a stacked bar format to display the average number of patients on the waitlist across different Time Bands (waiting durations) and segmented by 
  - Age Profiles:

      Time Bands (x-axis): 0–3 months, 3–6 months, etc., up to 18+ months.

      Age Profiles (color-coded): 0–15 years (Blue)16–64 years (Orange)65+ years (Purple)

      The y-axis represents the number of patients waiting (count). 

![WhatsApp Image 2024-11-18 at 6 29 03 PM (1)](https://github.com/user-attachments/assets/63790015-580d-4a31-b6aa-c15894b65392)

- **Top 5 Specify cases:** Accident&Emergency, Paed Cardiology, Paed Orthopaedic, Paediatric Dermatology, Paediatric ENT

- **Monthly Trend Analysis: Day Case / Inpatient vs. Outpatients:**
  The visual is divided into two line charts, displaying trends for Day Case, Inpatient, and Outpatient categories over time.

  **Left Chart:** 
  Day Case and Inpatient 
  
  - **Blue Lines:** Upper Blue Line: Represents the Day Case trend.

       - Shows patient counts for scheduled day procedures.
       - Peaks around July 2020 (62K) and then declines slightly in subsequent months.
       -  Consistent baseline before and after the peak.
  -  Orange Line: Represents the Inpatient trend.

      - Represents patients admitted for overnight stays.
     - Displays smaller fluctuations, with consistent counts around 20K–25K.
     - Slight increase in July 2020, possibly due to seasonal factors or increased capacity.
  **Right Chart:** Outpatient
   - LowerBlue Line: Represents the Outpatient trend.
     - Displays significantly higher volumes (measured in millions).
     - Shows a steady upward trend from 0.50M (July 2018) to 0.62M (January 2021).
     -  Indicates growth in outpatient visits, which could reflect improvements in accessibility or follow-up care.

![WhatsApp Image 2024-11-18 at 8 41 41 PM](https://github.com/user-attachments/assets/04f3a0de-7966-4da6-b822-ce6a2aee1346)

#### Detailview:
- **Filter Criteria:** The provided image shows a filter panel commonly used in healthcare data analysis dashboards. Here’s a detailed explanation:

  - **Purpose:**
    This filter allows users to refine and customize the data they want to view, often to identify patterns or analyze specific metrics in healthcare projects.

  - **Key Components:**
     - Archive_Data (Date Range): A date range slider and fields enable the user to filter records based on the data's archive period. The range here is from January 31, 2018, to February 27, 2021.

     - Case_Type: A dropdown for selecting specific types of healthcare cases (e.g., inpatient, outpatient, emergency) or viewing all case types.

    - Specialty_Name: Another dropdown to filter data based on medical specialties (e.g., cardiology, neurology) or include all specialties.

    - Age_Profile: Filters data by age groups. In this instance, the selected profile is 0-15 age categorie to  16–64 age categorie, likely representing working-age adults.

    - Time_Bands: This filter categorizes data by time intervals, such as the duration of cases or treatments. The selection here is 0-3 Months to 18+ Months, which might reflect cases lasting over 18 months.
  
![WhatsApp Image 2024-11-18 at 9 22 20 PM](https://github.com/user-attachments/assets/36730220-ef46-4188-a732-1d8ae7211186)

- **Detial Drid View:**
#### DrilDown:
- The chart you provided appears to show a summary of a healthcare project’s total patient waitlist categorized by specialty groups.

  - Key Observations:
    - Total Waitlist Count: The total waitlist across all specialties is 24,641,000 patients.
    - Specialty Group Breakdown: 
      - The specialty with the highest number of patients on the waitlist is Bones, with 3,673,000 patients.
      - General care follows closely with 3,401,000 patients on the waitlist.
      - ENT (Ear, Nose, and Throat) has 3,103,000 patients waiting.
      - Eyes and Skin specialties have significant waitlists as well, with 2,018,000 and 1,879,000 patients, respectively.
      - Other notable categories include Heart (1,600,000), Urine (1,611,000), and Reproductive System (1,320,000).
   - Smaller Waitlists:
      - The smallest waitlists are for categories like Infant (1,000), X-ray (3,000), and Cancer (18,000).
     - There is no waitlist reported for Pain Relief (0).
   - Moderate Waitlists:
     - Brain (1,106,000), Respiratory (803,000), and Cosmetic (770,000) are in the mid-range.
  - Other Observations:

    - Child Care, Digestive, and Hormonal issues have similar waitlists, each around 330,000-350,000.
    -  Specialized categories like Blood (270,000), Dental (220,000), and Immune System (157,000) show moderate levels of patient demand.
   
## 📚Technologies Used
- **Tool:** Power BI Desktop
- **Data Sources:** CSV files and public healthcare datasets
- **Languages:** DAX for data modeling
## 📚 Further Improvements
  - Integration with live data sources for real-time updates
  - The provided image shows a detailed grid view from a healthcare analytics dashboard, most likely created using Power BI. The view includes a breakdown of patient data by medical specialties and age groups for a specific archive date (January 31, 2018). 
## 📝 License
This project is open-source under the MIT License. Feel free to contribute or suggest improvements!

## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request for review.


