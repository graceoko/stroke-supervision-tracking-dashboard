# Stroke Supervision & Tracking Database

## Project Overview
This collaborative health informatics project was developed as an elective final project for **HI 2451: Database Design & Big Data Analytics** at the University of Pittsburgh. The goal was to design and implement a centralized stroke supervision and tracking system to support timely clinical decision-making, guideline compliance monitoring, and quality improvement initiatives in a hospital setting.

The system was modeled for a regional medical center specializing in neurology and rehabilitation and focuses on improving data consistency, real-time visibility, and cross-departmental coordination for stroke encounters.

---

## Tools & Technologies
- **SQL Server (SSMS)** – centralized relational database  
- **Microsoft Access** – interactive data entry interface and query execution  
- **Power BI** – dashboard reporting and visualization  
- **SQL** – schema design, relational modeling, and analytics queries  
- **Synthetic data generation (ChatGPT)** – used to simulate realistic clinical workflows  
- **Security considerations** – role-based access control, encryption at rest (TDE), and secure data transfer (SSL/TLS)

---

## System Design
The database supports:
- Longitudinal tracking of patients and stroke encounters  
- Capture of clinical snapshot data at the time of encounter (e.g., BMI, average glucose)  
- Treatment documentation  
- Guideline compliance checks  
- Data quality flagging for audit and reporting purposes  

SQL Server served as the centralized backend database. Microsoft Access was used for structured data entry and query-based reporting, while Power BI provided interactive dashboards for compliance monitoring and trend analysis.

---

## Data Source & Preparation
The dataset used in this project was **synthetic and AI-generated** to simulate realistic stroke encounters while avoiding the use of real patient data or protected health information (PHI).  

Data cleaning and preprocessing were performed to ensure:
- Referential integrity across tables  
- Consistent data types and formats  
- Compatibility across SQL Server, Microsoft Access, and Power BI  

Using synthetic data allowed the team to focus on system architecture, analytics design, and governance considerations without privacy constraints.

---

## Dashboard & Visualization
The final reporting layer includes an interactive Power BI dashboard designed for clinical staff, compliance teams, and leadership.

![Power BI Dashboard Overview](dashboards/powerbi/powerbi_dashboard_overview.jpg)

The dashboard summarizes stroke encounters, guideline compliance trends, and reporting metrics to support quality improvement initiatives.

---

## My Role & Contributions
- Generated a synthetic stroke dataset using ChatGPT  
- Cleaned and preprocessed data for SQL ingestion and cross-tool compatibility  
- Collaborated on SQL schema development and analytics queries  
- Worked with a teammate to connect SQL Server to Power BI  
- Contributed to system documentation and final project presentation  

---

## Key Outcomes
- Designed a relational database to support stroke encounter tracking  
- Built SQL queries for compliance monitoring and encounter reporting  
- Developed an interactive Power BI dashboard for clinical and quality insights  
- Successfully integrated unfamiliar tools under time constraints in a team setting  

---

## Limitations & Future Enhancements
- Scalability limitations of Microsoft Access for high-volume data  
- No direct integration with Electronic Health Record (EHR) systems  
- Limited automation for data ingestion and audit logging  

Future iterations could integrate EHR data feeds, migrate the interface to a web-based application, enhance audit capabilities, and support accreditation and regulatory reporting needs.

---

## Team
- **Grace Okoro**  
- **Supriya Plumley**  
- **Ashley DeNoyer**  
- **Syed Sajjad Ali**  

![Project team presentation photo](images/project_team.jpg)

---

## Acknowledgments
Developed as part of **HI 2451: Database Design & Big Data Analytics**  
University of Pittsburgh
