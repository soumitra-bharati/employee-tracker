# Employee Offboarding & HR Analytics Dashboard

An interactive HR dashboard built entirely in Microsoft Excel to track and analyze the employee offboarding process and overall workforce composition. This project transforms raw employee data into a powerful, interactive tool for data-driven decision-making.

<img width="1374" height="720" alt="Screenshot 2025-09-25 022625" src="https://github.com/user-attachments/assets/cef5df79-a057-4230-a5a4-955f1ee9e2ee" />

---

## 🚀 Features

-   **Interactive Dashboard:** A single-view dashboard with multiple charts providing a comprehensive overview of HR metrics.
-   **Dynamic Filtering:** Use slicers to filter the entire report by Department, Designation, Manager, and various offboarding statuses (Exit Interview, Asset Return, etc.).
-   **Key Metrics at a Glance:** Visualizations for:
    -   Number of Employees by Department
    -   Breakdown by Designation
    -   Offboarding Clearance Status
    -   Asset Return Status
    -   Final Settlement Completion
-   **Data-Driven Analysis:** Built on a structured Excel Table, allowing for easy data updates and automatic report refreshing.
-   **Modular Design:** Separate sheets for the dashboard, raw data, pivot tables, and helper lists for clarity and easy maintenance.

---

## 🛠️ Tools & Technologies Used

-   **Microsoft Excel**
    -   **Excel Tables:** For structured and dynamic data storage.
    -   **PivotTables:** As the core engine for data aggregation and analysis.
    -   **PivotCharts:** To create a variety of data visualizations.
    -   **Slicers:** For providing interactive controls on the dashboard.

---

## 📂 Project Structure

The Excel workbook is organized into the following sheets:

-   `dashboard`: The main user interface with all charts and slicers.
-   `data`: The raw dataset containing all employee and offboarding information. This acts as the single source of truth.
-   `pivot tables`: The backend sheet where all the pivot tables that feed the charts are located.
-   `lists`: A helper sheet containing unique lists (e.g., departments, managers) used for consistency and potential data validation.
-   `welcome`: A user-friendly landing page for navigation.

---

## ⚙️ How to Use

1.  **Download** the `.xlsx` file from this repository.
2.  **Open** the file in Microsoft Excel (2013 or later recommended).
3.  If prompted, click **"Enable Editing"** and **"Enable Content"**.
4.  Navigate to the `dashboard` sheet.
5.  Use the slicers on the left-hand side to filter the data. The charts will update automatically in real-time.
6.  To add new data, navigate to the `data` sheet and add a new row to the table. Go to the `Data` tab in the Excel Ribbon and click **"Refresh All"** to update the dashboard.

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
