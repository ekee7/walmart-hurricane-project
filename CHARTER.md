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
- We will have constant communication via the group chat that we created the first day of group work called "Walmart Midterm"
- We will assign tasks and update each other on changes made/questions we have/future work. If specific questions are asked of a group member, they are expected to acknowledge the message within 24 hours. 
- We will meet at least once a week outside of class time on Wednesdays at 10am. If we need more time outside of class to work, we will schedule to meet Fridays during the normal class time from 9-9:50am.
- If we disagree on the direction of our project, we will at the data first to try to resolve the conflict. If we still disagree and need an ultimate decision maker, the owner of that part decides. All decisions (especially ones that we made after a disagreement) will be logged in our notebook.
- If someone is not being a responsive and responsible group member, we will bring it to light as soon as we figure it out to not delay the progress of our work. We will all make sure to hold each other accountable. For instance, if someone is taking more than 24 hours to respond to a directed question in the group chat, we will check in with the person by calling or when we see them the next class in a polite manner. If the person is still not responsive after 48 hours, we will have a group meeting to re-evaluate and check in. If this issue is still not resolved, we will email Professor Williamson. 
