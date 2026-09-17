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

3.
select c."Day", s."Subject_Code", s."Subject_Name", c."Start_Time", c."End_Time"
FROM "Class" c
join "Subject" s ON s."Subject_Code" = c."Subject_Code"
WHERE c."Day" ILIKE 'Monday'
order by "Start_Time"
LIMIT 10;

| Day    | Subject_Code | Subject_Name             | Start_Time | End_Time |
| ------ | ------------ | ------------------------ | ---------- | -------- |
| Monday | ENG101       | English Foundations      | 08:30:00   | 10:00:00 |
| Monday | MAT201       | Applied Mathematics      | 08:30:00   | 10:00:00 |
| Monday | ICT301       | Database Fundamentals    | 08:30:00   | 10:00:00 |
| Monday | BUS101       | Business Essentials      | 08:30:00   | 10:00:00 |
| Monday | ART101       | Visual Arts              | 08:30:00   | 10:00:00 |
| Monday | ICT201       | Programming Fundamentals | 10:15:00   | 11:45:00 |
| Monday | SCI201       | Environmental Science    | 10:15:00   | 11:45:00 |
| Monday | BUS301       | Project Management       | 10:15:00   | 11:45:00 |
| Monday | HIS101       | Modern History           | 10:15:00   | 11:45:00 |
| Monday | DES201       | User Experience Design   | 10:15:00   | 11:45:00 |

