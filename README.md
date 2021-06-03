# Employee Database with SQL
## Overview of the Analysis
The purpose of this analysis was to assist the manager of Pewlett Hackard to prepare for the upcoming "silver tsunami" of retirees at the company. To avoid a disastrous employee deficit, we are creating a report to address the following questions: 
1. Which employees will be retiring in the next few years at Pewlett Hackard?
2. How many positions will Pewlett Hackard need to fill?
3. Which employees will be eligible for the retirement package (the mentorship role)?

## Results
### Employees Eligible for Retirement

[Eligible Employees per Title](https://github.com/jpb12002/Pewlett_Hackard_Analysis/blob/main/Data/retiring_titles.csv)

- There are approximately 90,400 employees who will soon be eligible for retirement. This is almost one-third of the approximately 300,000 current employees, which represents a massive personnel loss for the company.
- The positions with the highest risk for employee loss are "senior engineers" (29,414 employees retirement eligible) and "senior staff" (28,254 employees retirement eligible). These are high-ranking positions that represent a lot of experience in their respective fields. Pewlett Hackard will have to spend a significant amount of time and resources to find replacements for these employees. On the other hand, this creates an opportunity for many entry-level employees to be promoted within the company. 
- 2 department managers will be eligible for retirement. These executive roles are crucial to ensuring different departments run seamlessly and will require extensive time and resources to replace. 

### Employees Eligible for Mentorship Role

[Mentorship Eligible Employees](https://github.com/jpb12002/Pewlett_Hackard_Analysis/blob/main/Data/mentorship_eligibility.csv)

- There are 1,549 employees eligible for the proposed mentorship program. This subset represents only 1.7% of the employees eligible for retirement.

## Summary
**"How many roles will need to be filled as the "silver tsunami" begins to make an impact?**

Pewlett Hackard will need to prepare to fill the following roles soon:
- 29414 Senior Engineers
- 28254 Senior Staff
- 14222 Engineers
- 12243 Staff
- 4502 Technique Leaders
- 1761 Assistant Engineers
- 2 Managers

Altogether, a total of 90,398 employees will be ready to retire soon. As stated previously, this is almost one-third of the workforce in the entire company. Pewlett Hackard needs to begin planning as soon as possible so that they are ready to staff these roles with new employees when they become available. If the company cannot fill these roles fast enough, the worker shortage will seriously impact Pewlett Hackard's ability to operate efficiently. 

**Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?**

Let us assume every single employee that is eligible for the mentorship program decides to join (1,549 employees). Let us also assume Pewlett Hackard can fill every single position that becomes available as employees begin to retire (90,398 positions). In this best-case scenario, every mentor in the program would be responsible for training 58 or 59 new employees. It is not feasible or effective to expect each mentor to handle such a large group of potential new hires and be able to train them appropriately. If the mentorship program is to be successful, the criterion for the program needs to be expanded to allow more retirement-ready employees to become mentors for the next generation. 

### Additional Queries
- Another useful query would be to count the remaining number of non-retirement eligible employees in each role (i.e., create a table that counts the number of employees per title born after 1955). Using this table, Pewlett Hackard could determine if there are enough remaining employees in each department for the company to continue to operate. This table would highlight the roles and departments most in need of new employees. 
- A second future query would be to group the remaining non-retirement eligible employees by birth date decades (i.e., create a table that counts the number of employees born in the 1960s, the 1970s, etc.). Using this table, Pewlett Hackard could look ahead and anticipate if there will be another "silver tsunami" after surviving this first mass retirement. This table would also show if future disaster will be avoided should the ages of the remaining employees be distributed equally.  
