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
   - Re-check the stds
   - Add the date dimension
   - Build the measures
   - Add row-level security
   - Final validation

#### Project Rules
1. Build a galaxy schema: Never connect Facts together!
2. Always do a grain analysis.
3. Every column earns it’s place.
4. Protect the numbers: Know your totals, re-check after every change so that they don’t break.

#### Modeling Standards 
1.	Define the language: English.
2.	Naming: snake_case
3.	Tables: Define the prefixes.
     fact_ for Fact Tables
     dim_ for Dimension Tables.
4.	Keys: Suffix for the columns.
     _key for every column we make/create e.g product_key.
     _id for every column from the source file e.g customer_id.
5.	Friendly/professional  names
Readable meaningful names, not cryptic codes or technical short/abbreviations for table names, column names, values inside our tables. 
6.	Capitalization 
Capitalize each word in all the text values.





