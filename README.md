# Team 1 Mist 4610 Group Project 1

## Team Members 
1) Jessie Wong [@jw35468](https://github.com/jw35468)
2) Jessica Wang [@jw34666](https://github.com/jw34666)
3) Jayla Porter [@jaycporter](https://github.com/jaycporter)

## Problem Description 
The main task of this project is to build a relational database for the workings of a tennis club. The central entity we are interested in studying is the Members that make up our tennis club. Along with this centeral entity, there are many other entities that operate alongside the Members, such as the Coaching Services, Staff, Maintenance and Repairs, etc. We are interested in modeling the relationships shared between these entities in order to generate sample data and populate the entities with the sample data in order to perform functioning queries on the data so that we may gain valuable insight to the innerworkings of the tennis club and its operations. From these insights, we can plan for the future of the tennis club and see if there are areas that need special attention. 

## Data Model
Our data model depicts the entities and relationships that make up the operations of "Ace Haven Tennis Club." Our club is located in a suburban area of a medium-sized city, and we offer a variety of tennis-related services and activities to our members. We have both recreational and competitive tennis programs, and we host tournaments and events throughout the year. Our goal is to provide a welcoming and inclusive environment for tennis enthusiasts of all ages and skill levels.
 
Our tennis club has a membership system, coaching services, court rentals, and a pro shop where members can purchase tennis equipment and apparel. We also have a cafe and lounge area for socializing and relaxation. We are proud of our vibrant tennis community, and we want to improve the overall experience for our members, coaches, and staff through the implementation of a robust relational database.
To provide you with more information about our organization, here are some key aspects that the MIST 4610 class students should consider when building the database:

Members: We have a diverse membership base with different types of memberships (e.g., individual, family, student). Each member has a unique ID, contact information, and payment history. Some members may have specific preferences or requirements, such as coaching programs or court reservations.

Coaching Services: We offer coaching services with various coaches, each with their own specialization and availability. Coaches have profiles, schedules, and qualifications. Members can book coaching sessions, and we need to track these bookings and payments.
Court Reservations: Members can book tennis courts for specific dates and times. We need to manage court availability, reservations, and any fees associated with court bookings.

Tournaments and Events: We host tennis tournaments and events throughout the year. These events have specific dates, locations, and categories. Onlyst participants can register for these events, and we need to keep track of their registration status and payments.

Pro Shop: We sell tennis equipment and apparel in our pro shop. We need to track inventory, sales, and customer purchases.

Cafe and Lounge: The cafe and lounge offer food and beverages. We want to keep a record of orders and payments made by our members and guests.

Staff: We have a team of employees, including coaches, front desk staff, and cafe employees. Each employee has a profile with contact information, employment history, and schedule.

Financial Records: We need to manage financial records, including membership fees, coaching fees, court rental fees, event registration fees, and expenses related to staff salaries and inventory.

Maintenance and Repairs: Tennis courts and equipment require maintenance and occasional repairs. Create an entity to track maintenance schedules, repair requests, costs, and the status of maintenance tasks.

Membership Renewals: Keep track of when memberships are due for renewal, send reminders to members, and manage the renewal process. This entity should include renewal dates and payment history.
![SQLFINAL](https://github.com/jw35468/sql_project1/assets/149987218/fb26f0b6-8fb8-4e48-981d-a14c7a5cc19e)


## Data Dictionary 








## Queries 
1) Query 1
   Query 1 (SIMPLE) retrieves the count of members in each membership type category. 
Managers can use this information to understand the distribution of members across different membership types, which can help in planning marketing strategies and membership offerings.


3) Query 2
Query 2 (COMPLEX) counts the total coaching sessions booked with each coach. Managers can assess the popularity and workload of coaches to allocate resources effectively and optimize scheduling. 


4) Query 3
Query 3: (SIMPLE) Shows how much people spend on average at the cafe and in total

Managers can use this data to see how much revenue they are making from other areas of the tennis club and if they should continue to keep the Cafe open. 

 
5) Query 4
 Query 4: (SIMPLE) Shows which coach has “saturday” in their availability 
As saturday is likely the most busy day of the week, managers can use this information to efficiently schedule coaches and can see which classes to offer on weekends and who they may need to hire (ie a beginner tennis coach for saturday) 

7) Query 5
Query 5 (COMPLEX) lists the coaches who specialize in "Pro Tennis," display the number of coaching sessions they conducted in 2023, and order the results in descending order of coaching sessions. Managers can use this information to assess the popularity and performance of coaches in that specialization.

   
8) Query 6
Query 6 (COMPLEX) retrieves information about the Proshop purchases made by members who have also enrolled in tournaments. This query helps managers identify members who are both Proshop customers and tournament participants, allowing them to analyze the intersection of these two aspects of membership.
This information can be valuable for marketing and sales strategies, as managers can target these members with promotions related to both Proshop products and tournament participation.
   
9) Query 7
Query 7 (COMPLEX/RECURSIVE) creates a list of employees and their associated managers, allowing you to see the reporting structure within the organization.This information can be valuable for understanding how employees are organized, who their supervisors are, and how the managerial hierarchy is structured within the tennis club.
   
10) Query 8
 Query 8(COMPLEX) retrieves a list of tournaments and counts the number of participants registered for each tournament in descending order. Query 8 provides valuable insights into the performance and success of different tournaments, enabling managers to make informed decisions related to resource allocation, marketing, financial planning, member engagement, and competitiveness in the tennis club industry.

  
11) Query 9
 Query 9 (COMPLEX) calculates the total sales made by each employee in the Proshop and orders the results by sales in descending order. This information is valuable for managers to assess the performance of Proshop employees in terms of sales and make informed decisions regarding staffing and performance evaluations.
   
12) Query 10
 Query 10(Simple) lists the tournaments with registration fees greater than $50. This query helps managers make informed decisions about tournament pricing, resource allocation, and revenue generation within the tennis club.



   

## Database Information 
Name of database: cs_g7p1
