# INFS2608-Database-Management-and-Big-Data-Infrastructure

Project: INFS 2608 assignment (Johnny Ho, 2023 T1)

## Built with …
•	SQL 

•	Miro

•	Excel

•	Power BI 


## File Dictionary 
•	ERD diagram.png: ERD diagram for WPH private hospital 

•	Group assignment brief.pdf:  PDF on the assessment task

•	INFS 2608 T11A-02 presentation.pdf: Presentation on the WPH case study

•	INFS 2608 T11A-02-Report B.pdf:  Final report with proposed solutions

•	Snowflake schema: Snowflake schema for WPH

## Motivation
**Requirement Summary:**

•	Design and implement a database management system for WPH Private Hospital to enhance data management and healthcare service delivery.

•	Create an Entity-Relationship Diagram (ERD) to model the hospital’s data environment, covering relationships between patients, staff, administrators, and key healthcare processes.

•	Develop a Relational Schema for the database to ensure proper data storage and retrieval.

•	Construct a Snowflake Schema for the data warehouse, designed for efficient data analytics.

•	Generate data visualizations using Microsoft Power BI to provide insights into hospital operations and patient demographics.

## Summary of the assignment:
•	Entity-Relationship Diagram (ERD): Developed using Draw.io, the ERD models complex relationships within WPH, including patient interactions, staff roles, and administrative processes. The diagram ensures that data flows between entities are clear and logically structured.

•	Relational Schema: The schema was created to support the ERD by structuring the database into normalized tables, ensuring data integrity and efficient storage. Key tables include Appointment_Fact, Employee_Dimension, Patient_Dimension, among others.

•	Snowflake Schema: Used to structure the data warehouse, this schema allows for efficient data storage and retrieval. It includes key dimensions like Calendar_Dimension, Location_Dimension, and Treatment_Plan_Dimension.

•	Power BI Visualizations: Developed visualizations to analyze big data, including maps showing patient distribution, tables highlighting healthcare fund usage, and pie charts illustrating patient demographics and allergies.

## Summary of Results 
•	Entity-Relationship Diagram (ERD): The ERD effectively captures the necessary relationships within the hospital, focusing on the flow of data between entities such as patients, staff, and healthcare services. Improvements from previous iterations include enhanced legibility and the consolidation of entities to avoid redundancy.

•	Relational Schema: The schema successfully implements the ERD into a relational database model, facilitating the tracking of key hospital operations. It ensures that all data relationships are maintained with proper foreign key constraints, enhancing data accuracy and reliability.

•	Snowflake Schema: This schema was chosen for its ability to support complex queries needed for healthcare data analysis. The structure ensures that WPH can perform detailed data analytics, which is crucial for decision-making and resource allocation.

•	 **Power Bi insight:**

  -	Patient Distribution: Visualizations revealed that most patients are concentrated in inner Sydney, with some outliers in other states, providing insights into patient demographics.
    
  - Healthcare Fund Usage: The data showed that HCF is the most popular healthcare fund among patients, which could inform future negotiations with insurance providers.
    
  - Patient Demographics: Gender ratio analysis highlighted a male-dominated patient base, prompting considerations for addressing gender disparities in healthcare access.
    
### Recommendations:
  -	Data Management: WPH should adopt the proposed database model to enhance data management, ensuring that critical patient and operational data are consistently and accurately recorded.
    
  - Data Analytics: The use of Power BI for data visualization is recommended to enable WPH management to make informed decisions based on real-time data insights, improving the hospital’s operational efficiency.

