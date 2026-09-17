# Database-and-API-aseessment-practice

## 13.11
1.
select c."Day", s."Subject_Name", c."Start_Time", c."End_Time"
FROM "Class" c
join "Subject" s ON s."Subject_Code" = c."Subject_Code"
order by CASE c."Day" 
WHEN 'Monday' Then 1 
When 'Tuesday' Then 2
When 'Wednesday' then 3
When 'Thursday' then 4
When 'Friday' then 5 
else 6 end
LIMIT 10;

| Day    | Subject_Name             | Start_Time | End_Time |
| ------ | ------------------------ | ---------- | -------- |
| Monday | Applied Mathematics      | 08:30:00   | 10:00:00 |
| Monday | Database Fundamentals    | 08:30:00   | 10:00:00 |
| Monday | Business Essentials      | 08:30:00   | 10:00:00 |
| Monday | Visual Arts              | 08:30:00   | 10:00:00 |
| Monday | Programming Fundamentals | 10:15:00   | 11:45:00 |
| Monday | Environmental Science    | 10:15:00   | 11:45:00 |
| Monday | Project Management       | 10:15:00   | 11:45:00 |
| Monday | Modern History           | 10:15:00   | 11:45:00 |
| Monday | User Experience Design   | 10:15:00   | 11:45:00 |
| Monday | English Foundations      | 08:30:00   | 10:00:00 |

2.
select c."Day", s."Subject_Code", s."Subject_Name", c."Start_Time", c."End_Time"
FROM "Class" c
join "Subject" s ON s."Subject_Code" = c."Subject_Code"
WHERE c."Day" ILIKE 'Monday'
order by "Start_Time"
LIMIT 5;

| Day    | Subject_Code | Subject_Name          | Start_Time | End_Time |
| ------ | ------------ | --------------------- | ---------- | -------- |
| Monday | MAT201       | Applied Mathematics   | 08:30:00   | 10:00:00 |
| Monday | ICT301       | Database Fundamentals | 08:30:00   | 10:00:00 |
| Monday | BUS101       | Business Essentials   | 08:30:00   | 10:00:00 |
| Monday | ART101       | Visual Arts           | 08:30:00   | 10:00:00 |
| Monday | ENG101       | English Foundations   | 08:30:00   | 10:00:00 |

3.
  select s."Subject_Code", s."Subject_Name"
  FROM "Subject" s
  order by s."Subject_Name" asc
| Subject_Code | Subject_Name                        |
| ------------ | ----------------------------------- |
| ENG201       | Academic Writing                    |
| MAT201       | Applied Mathematics                 |
| AI101        | Artificial Intelligence Foundations |
| HIS201       | Australian History                  |
| BUS101       | Business Essentials                 |
| ICT301       | Database Fundamentals               |
| DES101       | Design Thinking                     |
| ART201       | Digital Media                       |
| ICT101       | Digital Technologies                |
| ENG101       | English Foundations                 |
| SCI201       | Environmental Science               |
| MAT101       | General Mathematics                 |
| SCI101       | General Science                     |
| BUS201       | Marketing Principles                |
| HIS101       | Modern History                      |
| ICT201       | Programming Fundamentals            |
| BUS301       | Project Management                  |
| ROB101       | Robotics Fundamentals               |
| DES201       | User Experience Design              |
| ART101       | Visual Arts                         |

