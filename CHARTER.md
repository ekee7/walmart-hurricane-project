# Charter

### Goals
Overall result: A final, consolidated notebook that runs from start to finish without any compilation errors that Walmart can use to stock up the store before the hurricane comes to maximize profits. We will do this by cleaning the data, to find trends/correlations in the data to 

How we will get there:
Set up repository

Profile the data

Fully clean the data for...
- Duplicate records
- Missing values
- Dates/times in different formats
- The same product under several SKUs and names
- Inconsistent capitalization and spacing
- Category names that don't match
- Numbers stored as text, and prices with $ signs
- Negative quantities
- Store ids written different ways across files
- Weather data in a different timezone than the sales data

Data cleaning decision logging

Weather API and join
- API call with retries
- Parsing it into a DataFrame
- Timezone alignment
- Checked join to sales

Analysis
- Create at least 6 plots
- Find correlations and relationships

Presentation

Add a README.md file

### Who Does What/Who Owns Each Question
- Emma/Kylie: cleaning and decision logging
- Raffaella/Miriam: weather API and join
- All: analysis, charts/presentations

### How You Work Together
- We will all come to every class
- We will have constant communication via text
- We will assign tasks and update each other
- We will meet at least once a week outside of class time (more often for group work)
