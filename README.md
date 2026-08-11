# PowerBI-Data-Modeling-Project
This project rebuilds a chaotic data model with bad shapes and bad relationships into a clean galaxy schema data model, which is ready for reliable analytics and reporting. 

## Project Requirements
### Building the Data Model
#### Objective
Use a systematic approach to clean and restructure a disorganized model that has a dataset of 23 messy tables, and rebuild it into a healthy data model that is ready for reliable analytics and reporting.

#### Project Phases
1. Prepare and Explore:
   - Understand the data.
   - Prepare the workspace in power query.
   - Spot dimensions vs facts.
     
2. Dimensions:
   - Group tables that describes the same thing.
   - Reshape them into one clean dimension.
   - Polish the dimension to make sure we are following the stds that we set at the beginning of the project.
   - Build them clean one by one.
     
4. Facts:
   - Pick an event, read it’s grain.
   - Build the fact from the details.
   - Connect every dimension.
   - Test so the numbers never break.

6. Polish:
   - Re-check the standards. 
   - Add the date dimension.
   - Build the measures.
   - Add row-level security.
   - Final validation.

#### Project Rules
1. Build a galaxy schema: Never connect facts together!
2. Always do a grain analysis.
3. Every column earns it’s place.
4. Protect the numbers: Know your totals, re-check after every change so that they don’t break.

#### Modeling Standards 
1.	Language: English.
2.	Naming: snake_case.
3.	Tables: Define the prefixes.
    - fact_ for Fact Tables.
    - dim_ for Dimension Tables.
5.	Keys: Suffix for the columns.
    - _key for every column we make/create e.g product_key.
    - _id for every column from the source file e.g customer_id.
5.	Readable meaningful names, not cryptic codes or technical abbreviations for table names, column names and values inside the tables. 
6.	Capitalize each word in all the text values.

### Preview  
![Model View Screenshot](https://github.com/Doreen-Njathi-Portfolio/Power-BI-Data-Modeling-Project/blob/main/Power%20BI%20files/Galaxy%20Schema%20Model_Screenshot%20.jpg)


## About Me
Hi there! I'm Doreen Njathi. I am a self taught data analyst building impactful projects in Excel, SQL and Power BI. This is one of my projects. My career started as a borehole geologist analyzing Olkaria's geothermal reservoir for electricity generation. I pivoted into sustainability and I hold a MSc in Environment and Natural Resources. 

