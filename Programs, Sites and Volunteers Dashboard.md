# Programs, Sites, Volunteers Dashboard ⭐

## Table of Contents: 
- Process
- Reports Use Case/Reports
- Dashboard 


## Process 
Goal: The aim of the project is to create a dashboard with five different graphs and one table. 
To be able to do this I first need to know what information and data I want to use. In this case I decided to go with the schema of the organization I currently work for. 

Now that I have an understanding of what I want to do, I then have to create reports. 
This includes inserting the data and data types. 
     1.Creating custom object in salesforce playground. 
     2.Creating data types in those custom objects. 
     3.Using Data wizard to insert records into the custom object. 
     4.Once it says that all records have uploaded, then create reports. 
         - If none or a few records were uploaded, then find where a error occured. 

After creating all reports I believe I needed, then I created a dashboard. 
     1. Make sure in the reports I created that the chart toggle was on. 
     2. Move around data types from columns to rows in the report section. 
     3. Create a dashboard, and insert which report I want to make the charts on. 
     4. Choose the appropriate chart that showcases the data perfectly. 
     5. Do this for the rest of the reports and create a table. 


## Reports Use Case and Reports 

### Sites & Programs Report: 
The sites and programs are an important part of keeping track of the school sites we are currently providing programs for. This report is important because it contains data of the names of the schools, the names of the programs from the past few years. As well as their start and end date, which is important in keeping track of. This report also includes the number of volunteers that were on these sites. With this data I believe I can create charts that show all the school sites that participated in the most recent Fall 2023 program. I can also create a line chart that shows the number of volunteers throughout the past few years in these programs and school sites. 

<img width="600" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/9d78b661-ff43-4320-b76b-3c59722ee3e0">

### Volunteers Placed in Site Report: 
We keep track of volunteers from the past years that have been part of our programs. This is so we can have their contact information in case they want to return in the future. Besides their name, address, email address and phone, there is also a column named Placed in Site. In our database we must manually put volunteers on the school site and program they are currently in. By keeping track of who is placed on site and who is not, we know what work needs to be done, which makes the report valuable. I also plan on adding more columns that include whether a volunteer has completed their training, and which has completed their background check. 

<img width="600" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/510742df-ba3b-4e76-9adb-6cf98cd8c3df">

### Active Semesters Report:
This report is important in keeping track of how long school sites have been a part of our program. As well as seeing which schools we have a current program in. This keeps track of all our sites that we have ever had a program on, as well as their address, city, and zip code. With this data and report I will create charts that focus on finding the number of schools that have a specific number of total semesters, as well as finding the number of schools that have programs and the number that don’t. With this we can see if we need to push for more programs on school sites. 

<img width="600" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/333cab93-55c4-446c-ab85-8a105dfd1681"> 

### Yearly Applicants Report: 
This report is made up of data that tracks yearly applicants from the past two decades. Since there are two semesters in a school year, I used both Fall applicants and Spring applicants as columns and then created a formula to add these two columns as Total Applicants for the specified year. With this data we can track how many applicants we receive yearly and how many returns we receive each semester. We can use this data to understand what years their applicants were fewer and can draw conclusions as to what happened that specific semester/year and what needs to be changed. 
<img width="400" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/cd37583d-d247-4ca9-8026-7d114bb8f1d8">


## Dashboard
![Final Project (3)](https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/dc517b9e-a7a5-4df5-9bab-0521f0f6611e)

F23 Active Semesters 
<img width="764" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/dfa4803c-eaa7-48eb-9105-80e63a5419ca">

Sites & Programs
<img width="776" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/d6fa1445-4d5d-475c-8a54-8c1583e89642">

Volunteers Placed In Site
<img width="522" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/a5466b77-bf6b-4841-a4e5-61f5b1017734">

Head Mentors, Mentors, Actors
<img width="502" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/df216bff-7edd-421b-90f3-44af9b69d8da">

Yearly Volunteers
<img width="764" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/461ce549-421a-466e-a7eb-e810ec1e0ae4">

Volunteer Info
<img width="797" alt="image" src="https://github.com/LuseroNajera/Salesforce-Projects/assets/155403528/2a0eb3f1-c0cc-4edd-ba86-d17db88299d3">



