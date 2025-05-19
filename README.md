# 📊 Quattrofy

## 🧭 Overview
**Quattrofy** is a robust enterprise-grade web application built for **Quattro Constructors**, designed to centralize reporting, operations, and project insights across departments. Developed in **C#** using **ASP.NET MVC**, hosted on **Microsoft Azure**, and integrated with an **Azure SQL Database**, Quattrofy is actively maintained and expanded as part of the company’s digital transformation initiative.

Originally conceived to automate the generation of LEM (Labour, Equipment, and Materials) reports by pulling data from HeavyJob via Open API, it has evolved into a powerful internal platform supporting various modules for employees, equipment, procurement, forecasting, dashboards, and more.

## ✨ Features & Functionality
- **LEM Report**: Dynamic grid of employees and equipment by timecard, job site, cost code, and notes with sign-off flow.
- **Dynamic Login & Roles**: Access and navigation based on user roles from system admin panel.
- **Dashboard Homepage**: Includes weather data, rotating project photos, and embedded Power BI dashboards.
- **Operations Reports**:
  - LEM (Labour, Equipment, Materials)
  - LPR (Labour Productivity Report)
  - JCV (Job Cost Variance)
  - FRC (Forecast)
  - WCR (Weekly Cost Report)
  - WIP (Work In Progress)
  - ACT (Active Projects)
  - CSF (Cashflow)
  - QTY (Quantities)
- **Procurement**:
  - Purchase Orders
  - Payment Applications
- **Employee**:
  - Employee List
  - Pay Classes
  - Internal Rates
  - Force Account Rates
  - Employee Dispatch
- **Equipment**:
  - Equipment List
  - Equipment Dispatch
  - Internal & Force Account Rates
- **System Admin**:
  - User Management
  - Role-based Access & Module Mapping
  - API Sync & Permissions
- **Profile Page**: User photo and profile management.

## ⚙️ Tech Stack
| **Category**             | **Tools & Technologies** |
|--------------------------|--------------------------|
| **Backend**              | ![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white) |
| **Frontend**             | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat&logo=jquery&logoColor=white) ![Razor](https://img.shields.io/badge/Razor-512BD4?style=flat&logo=.net&logoColor=white) |
| **Data Format**          | ![JSON](https://img.shields.io/badge/JSON-000000?style=flat&logo=json&logoColor=white) |
| **Framework**            | ![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=flat&logo=.net&logoColor=white) |
| **Security & Identity**  | ![Microsoft Identity](https://img.shields.io/badge/Microsoft%20Identity-00A4EF?logo=microsoft&logoColor=white&style=for-the-badge) ![Azure AD](https://img.shields.io/badge/Azure%20AD-0078D4?logo=azure-active-directory&logoColor=white&style=for-the-badge) |
| **Database**             | ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white) ![Azure SQL](https://img.shields.io/badge/Azure%20SQL-0078D4?style=flat&logo=microsoftazure&logoColor=white) |
| **Cloud & Hosting**      | ![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white) ![Azure App Services](https://img.shields.io/badge/Azure_App_Services-0078D4?style=flat&logo=windows&logoColor=white) ![Slot Deployment](https://img.shields.io/badge/Azure_Slot_Deployment-0078D4?style=flat&logo=azuredevops&logoColor=white) |
| **APIs & Integrations**  | ![Google Maps API](https://img.shields.io/badge/Google%20Maps%20API-4285F4?style=flat&logo=googlemaps&logoColor=white) ![Acumatica API](https://img.shields.io/badge/Acumatica%20API-2D9CDB?style=flat&logo=data&logoColor=white) ![DayForce API](https://img.shields.io/badge/DayForce%20API-1E90FF?style=flat&logo=data&logoColor=white) ![HCSS HeavyJob API](https://img.shields.io/badge/HCSS%20HeavyJob%20API-FFA500?style=flat&logo=api&logoColor=white) ![SiteDocs API](https://img.shields.io/badge/SiteDocs%20API-4CAF50?style=flat&logo=api&logoColor=white) |
| **APIs Protocols**     | ![REST API](https://img.shields.io/badge/REST%20API-025669?style=flat&logo=api&logoColor=white) ![OData](https://img.shields.io/badge/OData-EE4C2C?style=flat&logo=odata&logoColor=white) |
| **Analytics & BI**       | ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) ![Google Analytics](https://img.shields.io/badge/Analytics-e37400?logo=googleanalytics&logoColor=white&style=for-the-badge) |
| **Automation**           | ![Power Automate](https://img.shields.io/badge/Power%20Automate-0066FF?style=flat&logo=powerautomate&logoColor=white) |
| **DevOps & Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D4?style=for-the-badge&logo=azuredevops&logoColor=white) |
| **Project Management**   | ![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white) |

## 🏗 Architecture & Deployment

- **Frontend**: ASP.NET MVC Views with Razor, HTML, CSS, JavaScript, jQuery
- **Backend**: C# Controllers, Microsoft Identity, Service Layer, API integrations
- **Database**: Azure SQL Server
- **Hosting**: Microsoft Azure App Service with Deployment Slots (Staging/Production)
- **Authentication**: Microsoft Identity with role-permission mapping
- **Monitoring**: Azure Application Insights (planned)

## 🚀 Deployment & Access

- Hosted in Azure Web Services
- Staging and Production slots
- App auto-start and monitoring enabled

> Access restricted to internal corporate users with valid roles assigned.

## 🔒 Security

- All API calls secured via Power Automate and token-based authentication
- Role-based access control per module
- Deployment security hardening on Azure

## 📌 Current Status

- **Status**: Actively maintained and developed
- **Version**: v1.x (multi-module)

## 📈 Future Enhancements

- Add mobile support
- Expand integrations with SharePoint and OneDrive
- Improved user analytics and audit logs
- Automated notifications for LEM signoffs and Procurement steps
