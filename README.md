# hubspot-powerbi

The ultimate PowerBI report template for your sales data from HubSpot

---

### Table of Contents

1. **Introduction**
2. **Getting Started: Setting Up the Connection**
    - Prerequisites
    - Step-by-Step Connection Guide
3. **Using the Template**
    - Overview of Predefined Measures and Visuals
    - Practical Use Cases
4. **Additional Notes and Troubleshooting**
5. **FAQs**

---

### 1. Introduction

This document provides a comprehensive guide to using the RevOS Power BI Template designed for analyzing HubSpot data. The template enables users to visualize and analyze deals, contacts, companies, and deal pipelines, facilitating data-driven business decisions with ease. It includes predefined relationships, measures, and visualizations tailored for deal analysis. Additionally, the template serves as a flexible foundation, allowing users to integrate new data and create customized visuals for personalized reporting.

---

### 2. Getting Started: Setting Up the Connection

### Prerequisites

Before using the template, ensure the following:

1. Power BI Desktop is installed on your computer.
2. **Placeholder:** Where to get the template - [Insert link or instructions for obtaining the template]
3. A service account email, service account JSON key and Dataset Name are available. You can find all this information on RevOS site under Integrations.

![Image](https://github.com/user-attachments/assets/e23cc59c-d654-4b3a-9967-411ba0e45be2)

You have access to HubSpot data, including the required tables (deals, contacts, companies, and deal_pipelines).

<aside>
💡

You are not limited to this data. The template is preconfigured with these tables, but you can always load additional data from your data source to extend and customize your reports. 

</aside>

### Step-by-Step Connection Guide

1. **Open the Template**:
    - Launch Power BI Desktop.
    
    <aside>
    💡
    
    **Please Note:** Ensure you have the latest version of Power BI Desktop installed. Using an outdated version may lead to compatibility issues and unexpected problems.
    
    </aside>
    
    - Open the RevOS HubSpot template file.
2. **Enter Dataset Details**:
    - Upon opening the template, you will be prompted to specify:
        - **Dataset Name**: Enter the name of your HubSpot dataset.
        - **HubSpot_UID**: Provide your unique HubSpot identifier.
3. **Provide Service Account Credentials**:
    - Input the service account email.
    - Input the service account JSON key.
4. **Wait for Data Loading**:
    - After connection setup, data connection may take up to 15 minutes.
    - Data loading can take longer. It is depending on size of your data.
5. **Verify the Connection**:
    - Check the imported data tables and relationships to confirm successful setup.

---

### 3. Using the Template

### Overview of Predefined Visuals

The template includes multiple useful visuals. All visuals are interconnected, allowing users to filter page elements dynamically based on selections made in tables or other visuals. Key visuals include:

- **Dates Filter**: Focus on the required time period to refine your analysis.
- **Net Revenue, Lost Amount, and Pipeline Revenue Metrics**: Summarize key revenue data at a glance.
- **New vs. Existing Business Pie Chart**: Display the proportion of new and existing business deals.
- **Won vs. Lost Deals Pie Chart**: Highlight the count of deals that were won or lost.
- **Deal Path to Success Funnel**: Visualize the journey of deals from initial stages to closure, including the success rate of closed deals.
- **Revenue Trends Over Time Line Chart**: Track Net Revenue, Lost Amount, and Pipeline Revenue over a defined period.
- **Companies Table**: Provide details on the number of deals per company, along with their won/lost percentages.
- **Deals Table**: List individual deals with contact information and current statuses.

![Image](https://github.com/user-attachments/assets/bcbef07c-2dbc-4726-875d-37eff398f45a)

### Practical Use Cases

1. **Performance Analysis**:
    - Identify your most profitable clients and top-performing companies.
    - Analyze the win rate to optimize sales strategies.
2. **Revenue Tracking**:
    - Monitor revenue trends and assess the impact of lost deals.
3. **Company-Specific Insights**:
    - Compare deal performance across different companies.
    - Use visual breakdowns to focus on high-priority clients.

---

### 4. Additional Notes and Troubleshooting

- **Data Refresh**:
    - Ensure periodic refresh to keep the data up to date.
- **Known Issues**:
    - **Problem**: Data not loading after 15 minutes.
    **Solution**: This is a rare issue. Power BI will notify you if there is invalid data or table errors. If the connection process continues for more than 30 minutes, check the following:
    - Verify your internet connection.
    - Ensure you are using the latest version of Power BI Desktop.

---

### 5. FAQs

**Q: Can I modify the template after setup?**
A: Yes, you can customize visuals and measures to suit your specific needs. You can also get more data from your datasource.

**Q: How often should I refresh the data?**
A: It is recommended to refresh the data daily or as per your business requirements.

**Q: What if I encounter issues during setup?**
A: Refer to the troubleshooting section or contact [Insert support details].
