## Contoso High School Library Report

### Lineage View

![Lineage view](https://github.com/user-attachments/assets/07d08e25-685e-4f9b-ac1e-afce187f4479)


1. **Dataverse**:
   - **Source**: The data originates from Dataverse, a scalable data service and app platform.
   - **Function**: Dataverse stores and manages the data used in your Power BI reports.

2. **Power BI Desktop**:
   - **Data Import**: The data from Dataverse is imported into Power BI Desktop.
   - **Data Transformation**: In Power BI Desktop, data is cleaned, transformed, and modeled to prepare it for analysis.
   - **Report Creation**: Reports are created using the transformed data, incorporating various visualizations and analytics.

3. **Power BI Service**:
   - **Publishing**: The reports created in Power BI Desktop are published to the Power BI Service.
   - **Dataset**: The dataset in the Power BI Service is linked to the reports, ensuring that any updates in the data are reflected in the reports.

4. **Reports and Dashboards**:
   - **Reports**: These are detailed, interactive views of your data, created in Power BI Desktop and published to the Power BI Service.
   - **Dashboards**: Dashboards are collections of visuals from multiple reports, providing a high-level overview of key metrics and insights.

### Visual Representation

- **Icons and Arrows**: The image uses icons and arrows to represent the flow of data from Dataverse to Power BI Desktop, and then to the reports and dashboards in the Power BI Service.
- **Connections**: Each arrow indicates a connection or data flow between components, showing how data moves through the system.

### Key Points

- **Data Source**: Dataverse is the primary data source.
- **Transformation**: Data is transformed and modeled in Power BI Desktop.
- **Publishing**: Reports are published to the Power BI Service.
- **Visualization**: Reports and dashboards provide interactive and visual representations of the data.

### Overview

This report provides a comprehensive analysis of the current loans at Contoso High School Library, detailing total loans, overdue loans, and student borrowing patterns over recent years. The data spans multiple school years and includes insights into individual student performance and trends in library usage.

### Current Loans

- **Total Loans**: 5
- **Total Overdue Loans**: 5

#### Detailed Loan Information

| Loan ID   | Book Title                       | Loan Start Date | Due Date       | Borrower         | Is Overdue | Days Overdue |
|-----------|----------------------------------|------------------|----------------|-------------------|------------|--------------|
| Loan-1966 | Macbeth                          | 20 April 2024    | 27 April 2024  | Alex Smith        | True       | 78           |
| Loan-1967 | A Tale of Two Cities            | 21 April 2024    | 28 April 2024  | Michael O'Brien   | True       | 77           |
| Loan-1974 | Winnie-the-Pooh                 | 30 April 2024    | 6 May 2024     | Maria Garcia      | True       | 69           |
| Loan-1973 | Adventures of Huckleberry Finn   | 1 May 2024       | 7 May 2024     | Maria Garcia      | True       | 68           |
| Loan-1971 | Macbeth                          | 8 May 2024       | 15 May 2024    | Maria Garcia      | True       | 60           |

### Student Review

- **Total Loans by Students**: 214
- **Total Days on Loan**: 1173

#### Top Borrowers

| Student Name      | Total Loans | Total Loans Last Year | Change YOY | % Change YOY | Total Days on Loan |
|-------------------|-------------|-----------------------|------------|--------------|---------------------|
| Michael O'Brien   | 27          | 27                    | 0          | 0.0%         | 214                 |
| Raj Patel         | 27          | 27                    | 0          | 0.0%         | 214                 |
| John Lee          | 26          | 24                    | 2          | 8.3%         | 611                 |
| Anna Muller       | 21          | 26                    | -5         | -19.2%       | 264                 |
| Maria Garcia      | 21          | 21                    | 0          | 0.0%         | 214                 |
| Yuki Sato         | 20          | 19                    | 1          | 5.3%         | 214                 |
| Alex Smith        | 20          | 22                    | -2         | -9.1%        | 375                 |
| David Cohen       | 19          | 21                    | -2         | -9.5%        | 1175                |
| Sofia Rossi       | 19          | 19                    | 0          | 0.0%         | 214                 |
| Li Wang           | 13          | 13                    | 0          | 0.0%         | 214                 |

### Monthly Loan Trends

#### Total Loans and Year-Over-Year Change

| Month | Total Loans | % Change YOY |
|-------|-------------|---------------|
| Sep   | 17          | -20%         |
| Oct   | 14          | -10%         |
| Nov   | 18          | 0%           |
| Dec   | 10          | 10%          |
| Jan   | 26          | 20%          |
| Feb   | 15          | -40%         |
| Mar   | 19          | -20%         |
| Apr   | 26          | 0%           |
| May   | 20          | 20%          |
| Jun   | 17          | 0%           |
| Jul   | 16          | 0%           |
| Aug   | 16          | 0%           |

### Summary of Findings

- The library currently has a total of 5 overdue loans, all belonging to different students.
- The total number of loans recorded for the year is 214, indicating a slight decrease compared to the previous year.
- Monthly trends show fluctuations in borrowing patterns, with notable increases in January and April.
- Individual student performance varies, with some students showing significant changes in their borrowing habits year-over-year.

### Recommendations

- Implement reminders for overdue loans to improve return rates.
- Analyze the reasons behind the fluctuations in monthly loans to better understand student engagement.
- Consider targeted programs to encourage reading among students with declining loan numbers.

This report serves as a foundational tool for improving library services and enhancing student engagement with reading materials.

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/15708153/d1bbd7d1-ea5e-4931-9aac-d215c8c8022b/Contoso-High-School-Library-Report.pdf.pdf
