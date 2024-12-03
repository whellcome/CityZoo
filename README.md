---

# Data Engineering Project: Modernizing Zoo Operations

This repository contains the results of a Data Engineering project aimed at modernizing the operational and analytical systems of the City Zoo. The project was conducted as part of a professional assignment to design and implement IT-supported processes for a long-established organization undergoing a comprehensive modernization effort.

## Project Overview

The project addresses key tasks required for implementing integrated data systems in the zoo's operations, focusing on database design, implementation, and data quality assurance. The deliverables are structured into the following objectives:

1. **Operational Database Design (ERM)**  
   - Develop a complete Entity-Relationship Model (ERM) for the zoo's operational database.  
   - Normalize all many-to-many (M:N) relationships and define primary keys, foreign keys, and cardinalities.

2. **Relational Database Implementation & export in SQL format**  
   - Implement the operational MS Access database based on the ERM.  
   - Provide comprehensive documentation, including a detailed data dictionary.
   - Python-Based Export Algorithm to export MS Access data into an SQL format
   
3. **Data Warehouse Design and Architecture**  
   - Propose and justify a Data Warehouse schema (e.g., Star, Snowflake, or Data Vault).  
   - Create a corresponding data model and IT architecture to support Business Intelligence (BI) capabilities.

4. **Data Quality Concept**  
   - Develop a strategy to maintain data quality above 97%.  
   - Ensure sustainable processes for data maintenance and error handling.

5. **Project Presentation**  
   - Summarize project results in a structured presentation for stakeholders.  
   - Highlight methodologies, decisions, and best practices.

---

## Deliverables

The following artifacts are included in this repository:

1. **Operational Database Design**  
   - [ERM Diagram](https://github.com/whellcome/CityZoo/blob/master/Design/ERM_City_Zoo.png)
   - [Relational Database File](https://github.com/whellcome/CityZoo/blob/master/Design/CityZoo.accdb)  
   - [Data Dictionary](https://github.com/whellcome/CityZoo/blob/master/Design/Data_Dictionary_Zoo.xlsx)
   - [SQL script to create Relational Database Prototyp](https://github.com/whellcome/CityZoo/blob/master/Code/export-msaccess-sql.py)

2. **Data Warehouse Components**  
   - [Data Warehouse Model](https://github.com/whellcome/CityZoo/tree/master/Design)  
   - [IT Architecture Diagram](https://github.com/whellcome/CityZoo/blob/master/Concept/IT-Infrastruktur_City_Zoo.pptx)

3. **Data Quality Concept**  
   - [Documentation](https://github.com/whellcome/CityZoo/tree/master/Concept)

4. **Presentation**  
   - [Project Presentation](https://github.com/whellcome/CityZoo/blob/master/Concept/City%20Zoo.pptx)

---

## Methods and Tools

The project utilized the following tools and methodologies:

- **Database Management**: Microsoft Access for database prototyping.  
- **Modeling**: ERM and Data Warehouse schema design with tools supporting PNG and PDF exports.  
- **Data Quality**: A structured approach to ensure accuracy and consistency in the dataset.  
- **Collaboration**: Stakeholder interviews and iterative feedback loops to refine deliverables.

---

## Future Steps

The project paves the way for further enhancements in the zoo's IT infrastructure:

- Deployment of the operational database and Data Warehouse in a production environment.
- Continuous data quality monitoring and improvement.
- Expansion of analytical capabilities with advanced BI tools.

---

## License

This repository is made available for educational purposes and is shared under **CC BY-NC-ND 4.0.** For details, see the [LICENSE](LICENSE.md) file.

---
