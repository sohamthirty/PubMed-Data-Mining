# PubMed-Data-Mining

## Data
**[PubMed | National Library of Medicine](https://pubmed.ncbi.nlm.nih.gov/download/)**

PubMed contains citations and abstracts of biomedical literature from several NLM literature resources, including MEDLINE—the largest component of the PubMed database.

## Tasks
**Part 1:**
- • Design relational schema: Create a normalized schema for articles, journals, and authors. Extract and transform XML data, and store relevant attributes in the SQLite database.
- • R Notebook and ERD: Utilize an R Notebook to organize code and incorporate an Entity-Relationship Diagram (ERD) displaying the relational schema.
- • SQLite implementation: Realize the relational schema in SQLite, including the creation of tables using SQL statements and loading data from the XML source.

**Part 2:**
- • New R Notebook and MySQL database: Begin a fresh R Notebook and establish a MySQL database, either locally or in the cloud, for the next phase.
- • Star schema creation: Design and implement a star schema for author facts, considering factors such as ID, name, number of articles, and average articles published per year. Load data from the SQLite database into the fact table using SQL commands executed from R.
- • Scalability and performance: Ensure the code is designed to handle large datasets, taking into account the potential of millions of rows per table. Focus on scalability and efficient execution to optimize performance.

**Other Tasks:**
- • Data exploration and mining: Employ queries in the MySQL data warehouse to generate insights for a fictitious dashboard. Focus on understanding the seasonal pattern and publication cycle, particularly by identifying the top ten authors based on publication numbers.
- • Documentation and changes: Document any modifications made to the fact table and provide clear explanations for the reasons behind those changes.
- • Creative analysis and best practices: Apply creative thinking to address the project goals effectively, prioritizing scalability, performance, and avoiding overreliance on SQL GROUP BY or COUNT statements for analysis. Emphasize innovative approaches that can yield valuable insights from the data.

## Structure
**ERD:**

<img align="center" height="340px" src="https://github.com/sohamthirty/PubMed-Data-Mining/blob/main/Images/ERD.png" alt="image" />

**Star Schema:**

<img align="center" height="340px" src="https://github.com/sohamthirty/PubMed-Data-Mining/blob/main/Images/StarSchema.png" alt="image" />


## Conclusion
The SQL data analysis project on bird strike data covered essential tasks, including schema design, data extraction, and transformation. It utilized SQLite and MySQL to realize the schema and create a star schema for author facts. The project's focus on scalability, performance, and creative analysis provided valuable insights into bird strike incidents and their impact on aviation safety.
