# part 1

# part 2

## General information
1.
select *
from "printjobs"
| job_id | print_start_time | duration_min | student_id | course_code | printer_id |
| ------ | ---------------- | ------------ | ---------- | ----------- | ---------- |
| 1      | 8/1/2026 13:30   | 416          | 100012     | DES101      | P0001      |
| 2      | 8/1/2026 16:30   | 265          | 100024     | DES101      | P0003      |
| 3      | 8/1/2026 17:45   | 226          | 100010     | DES101      | P0002      |
| 4      | 8/2/2026 9:30    | 41           | 100000     | DES101      | P0006      |
| 5      | 8/2/2026 10:30   | 123          | 100007     | ENG202      | P0007      |
| 6      | 8/2/2026 17:30   | 354          | 100014     | DES101      | P0009      |
| 7      | 8/2/2026 20:00   | 235          | 100028     | DES101      | P0008      |
| 8      | 8/3/2026 9:30    | 415          | 100027     | ENG202      | P0003      |
| 9      | 8/3/2026 16:30   | 29           | 100013     | ENG202      | P0009      |
| 10     | 8/4/2026 7:00    | 126          | 100003     | ENG202      | P0009      |
| 11     | 8/4/2026 7:45    | 448          | 100001     | ENG202      | P0009      |
| 12     | 8/4/2026 10:30   | 376          | 100022     | DES101      | P0010      |
| 13     | 8/4/2026 12:00   | 444          | 100012     | DES101      | P0002      |
| 14     | 8/4/2026 13:30   | 357          | 100007     | ENG202      | P0005      |
| 15     | 8/4/2026 16:30   | 389          | 100020     | DES101      | P0001      |
| 16     | 8/4/2026 20:30   | 51           | 100022     | DES101      | P0001      |
| 17     | 8/5/2026 7:00    | 85           | 100019     | ENG202      | P0009      |
| 18     | 8/5/2026 8:45    | 191          | 100003     | ENG202      | P0005      |
| 19     | 8/5/2026 11:45   | 371          | 100022     | DES101      | P0006      |
| 20     | 8/5/2026 13:00   | 250          | 100017     | ENG202      | P0006      |
| 21     | 8/5/2026 13:30   | 361          | 100022     | DES101      | P0010      |
| 22     | 8/5/2026 18:30   | 329          | 100022     | DES101      | P0008      |
| 23     | 8/5/2026 18:45   | 289          | 100011     | ENG202      | P0006      |
| 24     | 8/6/2026 9:15    | 401          | 100011     | ENG202      | P0005      |
| 25     | 8/6/2026 11:45   | 320          | 100006     | DES101      | P0010      |
| 26     | 8/6/2026 13:30   | 135          | 100014     | DES101      | P0006      |
| 27     | 8/6/2026 15:30   | 372          | 100017     | ENG202      | P0003      |
| 28     | 8/7/2026 10:45   | 214          | 100010     | DES101      | P0009      |
| 29     | 8/7/2026 11:45   | 382          | 100025     | ENG202      | P0009      |
| 30     | 8/7/2026 14:45   | 413          | 100004     | DES101      | P0007      |
| 31     | 8/7/2026 14:45   | 338          | 100020     | DES101      | P0006      |
| 32     | 8/7/2026 20:15   | 315          | 100010     | DES101      | P0004      |
| 33     | 8/8/2026 9:45    | 252          | 100006     | DES101      | P0003      |
| 34     | 8/8/2026 11:15   | 340          | 100007     | ENG202      | P0006      |
| 35     | 8/8/2026 14:30   | 188          | 100023     | ENG202      | P0003      |
| 36     | 8/8/2026 15:15   | 274          | 100014     | DES101      | P0010      |
| 37     | 8/8/2026 16:00   | 92           | 100026     | DES101      | P0002      |
| 38     | 8/8/2026 16:15   | 67           | 100021     | ENG202      | P0007      |
| 39     | 8/8/2026 16:15   | 286          | 100014     | DES101      | P0006      |
| 40     | 8/8/2026 19:15   | 80           | 100018     | DES101      | P0002      |
| 41     | 8/9/2026 7:30    | 348          | 100029     | ENG202      | P0010      |
| 42     | 8/9/2026 11:30   | 62           | 100006     | DES101      | P0009      |
| 43     | 8/9/2026 16:15   | 194          | 100008     | DES101      | P0010      |
| 44     | 8/9/2026 16:45   | 332          | 100021     | ENG202      | P0003      |
| 45     | 8/9/2026 17:45   | 84           | 100012     | DES101      | P0010      |
| 46     | 8/9/2026 18:45   | 55           | 100015     | ENG202      | P0006      |
| 47     | 8/10/2026 7:30   | 211          | 100008     | DES101      | P0008      |
| 48     | 8/10/2026 11:15  | 222          | 100022     | DES101      | P0008      |
| 49     | 8/10/2026 12:45  | 175          | 100010     | DES101      | P0008      |
| 50     | 8/10/2026 13:45  | 138          | 100028     | DES101      | P0005      |
| 51     | 8/10/2026 15:45  | 160          | 100020     | DES101      | P0006      |
| 52     | 8/10/2026 17:30  | 293          | 100014     | DES101      | P0008      |
| 53     | 8/10/2026 17:45  | 275          | 100025     | ENG202      | P0006      |
| 54     | 8/10/2026 21:15  | 433          | 100014     | DES101      | P0009      |
| 55     | 8/11/2026 8:45   | 64           | 100008     | DES101      | P0003      |
| 56     | 8/11/2026 10:45  | 316          | 100022     | DES101      | P0006      |
| 57     | 8/11/2026 13:30  | 422          | 100026     | DES101      | P0001      |
| 58     | 8/11/2026 18:15  | 154          | 100003     | ENG202      | P0003      |
| 59     | 8/11/2026 19:30  | 83           | 100025     | ENG202      | P0002      |
| 60     | 8/12/2026 8:15   | 294          | 100022     | DES101      | P0007      |
| 61     | 8/12/2026 9:00   | 34           | 100026     | DES101      | P0008      |
| 62     | 8/12/2026 13:15  | 145          | 100023     | ENG202      | P0006      |
| 63     | 8/12/2026 15:15  | 478          | 100010     | DES101      | P0003      |
| 64     | 8/12/2026 16:15  | 253          | 100004     | DES101      | P0004      |
| 65     | 8/12/2026 18:15  | 113          | 100007     | ENG202      | P0002      |
| 66     | 8/12/2026 20:45  | 320          | 100020     | DES101      | P0010      |
| 67     | 8/13/2026 7:15   | 229          | 100024     | DES101      | P0005      |
| 68     | 8/13/2026 8:15   | 413          | 100004     | DES101      | P0010      |
| 69     | 8/13/2026 13:00  | 440          | 100026     | DES101      | P0009      |
| 70     | 8/13/2026 14:30  | 359          | 100012     | DES101      | P0001      |
| 71     | 8/13/2026 16:00  | 479          | 100021     | ENG202      | P0007      |
| 72     | 8/13/2026 18:30  | 274          | 100013     | ENG202      | P0002      |
| 73     | 8/13/2026 19:30  | 238          | 100024     | DES101      | P0001      |
| 74     | 8/14/2026 15:45  | 61           | 100018     | DES101      | P0007      |
| 75     | 8/14/2026 17:00  | 477          | 100020     | DES101      | P0004      |
| 76     | 8/14/2026 19:45  | 356          | 100017     | ENG202      | P0004      |
| 77     | 8/14/2026 20:00  | 156          | 100004     | DES101      | P0007      |
| 78     | 8/15/2026 11:45  | 15           | 100017     | ENG202      | P0001      |
| 79     | 8/15/2026 13:15  | 36           | 100001     | ENG202      | P0006      |
| 80     | 8/15/2026 14:45  | 191          | 100023     | ENG202      | P0005      |
| 81     | 8/15/2026 18:00  | 61           | 100004     | DES101      | P0010      |
| 82     | 8/16/2026 7:45   | 245          | 100007     | ENG202      | P0003      |
| 83     | 8/16/2026 8:30   | 447          | 100015     | ENG202      | P0004      |
| 84     | 8/16/2026 9:15   | 440          | 100024     | DES101      | P0010      |
| 85     | 8/16/2026 14:00  | 79           | 100010     | DES101      | P0008      |
| 86     | 8/16/2026 14:30  | 275          | 100026     | DES101      | P0002      |
| 87     | 8/16/2026 18:45  | 189          | 100014     | DES101      | P0010      |
| 88     | 8/16/2026 19:00  | 210          | 100029     | ENG202      | P0007      |
| 89     | 8/16/2026 19:45  | 320          | 100024     | DES101      | P0001      |
| 90     | 8/16/2026 20:30  | 310          | 100027     | ENG202      | P0010      |
| 91     | 8/17/2026 9:30   | 378          | 100003     | ENG202      | P0009      |
| 92     | 8/17/2026 17:30  | 446          | 100020     | DES101      | P0003      |
| 93     | 8/17/2026 18:45  | 297          | 100000     | DES101      | P0006      |
| 94     | 8/18/2026 8:00   | 82           | 100004     | DES101      | P0003      |
| 95     | 8/18/2026 10:30  | 407          | 100011     | ENG202      | P0001      |
| 96     | 8/18/2026 11:00  | 377          | 100006     | DES101      | P0005      |
| 97     | 8/18/2026 14:30  | 294          | 100015     | ENG202      | P0009      |
| 98     | 8/18/2026 19:45  | 40           | 100024     | DES101      | P0002      |
| 99     | 8/18/2026 19:45  | 440          | 100003     | ENG202      | P0007      |
| 100    | 8/18/2026 20:45  | 371          | 100001     | ENG202      | P0006      |
___
2.
select *
from "students"
ORDER BY "last_name" asc
| student_id | first_name | last_name | email                            |
| ---------- | ---------- | --------- | -------------------------------- |
| 100014     | Amelia     | Adams     | amelia.adams@kangalife.edu.au    |
| 100012     | Charlotte  | Baker     | charlotte.baker@kangalife.edu.au |
| 100003     | Noah       | Brown     | noah.brown@kangalife.edu.au      |
| 100021     | James      | Campbell  | james.campbell@kangalife.edu.au  |
| 100016     | Harper     | Carter    | harper.carter@kangalife.edu.au   |
| 100008     | Isabella   | Chen      | isabella.chen@kangalife.edu.au   |
| 100025     | Thomas     | Collins   | thomas.collins@kangalife.edu.au  |
| 100024     | Zoe        | Edwards   | zoe.edwards@kangalife.edu.au     |
| 100023     | Benjamin   | Evans     | benjamin.evans@kangalife.edu.au  |
| 100011     | Jack       | Green     | jack.green@kangalife.edu.au      |
| 100010     | Mia        | Hall      | mia.hall@kangalife.edu.au        |
| 100001     | Liam       | Jones     | liam.jones@kangalife.edu.au      |
| 100007     | Mason      | Kelly     | mason.kelly@kangalife.edu.au     |
| 100017     | Oscar      | Mitchell  | oscar.mitchell@kangalife.edu.au  |
| 100027     | Samuel     | Morris    | samuel.morris@kangalife.edu.au   |
| 100015     | Leo        | Nelson    | leo.nelson@kangalife.edu.au      |
| 100006     | Sophia     | Nguyen    | sophia.nguyen@kangalife.edu.au   |
| 100022     | Chloe      | Parker    | chloe.parker@kangalife.edu.au    |
| 100020     | Grace      | Phillips  | grace.phillips@kangalife.edu.au  |
| 100029     | Daniel     | Reed      | daniel.reed@kangalife.edu.au     |
| 100018     | Evelyn     | Roberts   | evelyn.roberts@kangalife.edu.au  |
| 100028     | Lily       | Rogers    | lily.rogers@kangalife.edu.au     |
| 100013     | Henry      | Scott     | henry.scott@kangalife.edu.au     |
| 100000     | Olivia     | Smith     | olivia.smith@kangalife.edu.au    |
| 100026     | Ella       | Stewart   | ella.stewart@kangalife.edu.au    |
| 100005     | Ethan      | Taylor    | ethan.taylor@kangalife.edu.au    |
| 100019     | William    | Turner    | william.turner@kangalife.edu.au  |
| 100009     | Lucas      | Walker    | lucas.walker@kangalife.edu.au    |
| 100002     | Emma       | Williams  | emma.williams@kangalife.edu.au   |
| 100004     | Ava        | Wilson    | ava.wilson@kangalife.edu.au      |
***
3.
select *
from "courses"
ORDER BY "course_name" asc

| course_code | course_name                 | course_description                                                            | coordinator    |
| ----------- | --------------------------- | ----------------------------------------------------------------------------- | -------------- |
| ENG202      | Engineering Systems         | Applied mechanical and systems engineering with a focus on rapid prototyping. | Mr. James Cole |
| DES101      | Product Design Fundamentals | Introductory principles of product design, prototyping and 3D modelling.      | Mrs. Lisa Chen |
###

## Find specific Records:

1.
select *
from "printjobs" pj
where "duration_min" > '179'

| job_id | print_start_time | duration_min | student_id | course_code | printer_id |
| ------ | ---------------- | ------------ | ---------- | ----------- | ---------- |
| 71     | 8/13/2026 16:00  | 479          | 100021     | ENG202      | P0007      |
| 63     | 8/12/2026 15:15  | 478          | 100010     | DES101      | P0003      |
| 75     | 8/14/2026 17:00  | 477          | 100020     | DES101      | P0004      |
| 252    | 9/22/2026 11:45  | 474          | 100008     | DES101      | P0003      |
| 127    | 8/25/2026 9:00   | 472          | 100022     | DES101      | P0007      |
| 279    | 9/27/2026 18:15  | 468          | 100014     | DES101      | P0006      |
| 118    | 8/24/2026 7:15   | 464          | 100000     | DES101      | P0002      |
| 245    | 9/20/2026 12:15  | 464          | 100010     | DES101      | P0002      |
| 246    | 9/21/2026 7:30   | 463          | 100025     | ENG202      | P0002      |
| 195    | 9/10/2026 15:45  | 461          | 100013     | ENG202      | P0003      |
___

2.
select p."printer_model"
from "printjobs" pj
join "printers" p on p."printer_id" = pj."printer_id"
where p."printer_model" LIKE '%bracket%'
group by printer_model

### Success. No rows returned
***

3.
select p."printer_model"
from "printjobs" pj
join "printers" p on p."printer_id" = pj."printer_id"
where p."printer_type" = 'SLS' 
group by p.printer_id

| printer_model |
| ------------- |
| Form 3        |
| Fuse 1+       |
| Photon Mono X |
___

4.
select s."student_id", s."first_name", s."last_name"
from "students" s 
join "printjobs" pj on s."student_id" = pj.student_id
join "courses" c on c."course_code" = pj."course_code"
where c."course_name" ILIKE '%Design%'
group by s."student_id";

| student_id | first_name | last_name |
| ---------- | ---------- | --------- |
| 100000     | Olivia     | Smith     |
| 100002     | Emma       | Williams  |
| 100004     | Ava        | Wilson    |
| 100006     | Sophia     | Nguyen    |
| 100008     | Isabella   | Chen      |
| 100010     | Mia        | Hall      |
| 100012     | Charlotte  | Baker     |
| 100014     | Amelia     | Adams     |
| 100016     | Harper     | Carter    |
| 100018     | Evelyn     | Roberts   |
| 100020     | Grace      | Phillips  |
| 100022     | Chloe      | Parker    |
| 100024     | Zoe        | Edwards   |
| 100026     | Ella       | Stewart   |
| 100028     | Lily       | Rogers    |
***

## Joins (inner joins only):
1.
select pj."job_id", s."first_name" || ' ' || s."last_name" AS "full name"
from "printjobs" pj
join "students" s on pj."student_id" = s."student_id";

| job_id | full name       |
| ------ | --------------- |
| 1      | Charlotte Baker |
| 2      | Zoe Edwards     |
| 3      | Mia Hall        |
| 4      | Olivia Smith    |
| 5      | Mason Kelly     |
| 6      | Amelia Adams    |
| 7      | Lily Rogers     |
| 8      | Samuel Morris   |
| 9      | Henry Scott     |
| 10     | Noah Brown      |
| 11     | Liam Jones      |
| 12     | Chloe Parker    |
| 13     | Charlotte Baker |
| 14     | Mason Kelly     |
| 15     | Grace Phillips  |
| 16     | Chloe Parker    |
| 17     | William Turner  |
| 18     | Noah Brown      |
| 19     | Chloe Parker    |
| 20     | Oscar Mitchell  |
| 21     | Chloe Parker    |
| 22     | Chloe Parker    |
| 23     | Jack Green      |
| 24     | Jack Green      |
| 25     | Sophia Nguyen   |
| 26     | Amelia Adams    |
| 27     | Oscar Mitchell  |
| 28     | Mia Hall        |
| 29     | Thomas Collins  |
| 30     | Ava Wilson      |
| 31     | Grace Phillips  |
| 32     | Mia Hall        |
| 33     | Sophia Nguyen   |
| 34     | Mason Kelly     |
| 35     | Benjamin Evans  |
| 36     | Amelia Adams    |
| 37     | Ella Stewart    |
| 38     | James Campbell  |
| 39     | Amelia Adams    |
| 40     | Evelyn Roberts  |
| 41     | Daniel Reed     |
| 42     | Sophia Nguyen   |
| 43     | Isabella Chen   |
| 44     | James Campbell  |
| 45     | Charlotte Baker |
| 46     | Leo Nelson      |
| 47     | Isabella Chen   |
| 48     | Chloe Parker    |
| 49     | Mia Hall        |
| 50     | Lily Rogers     |
| 51     | Grace Phillips  |
| 52     | Amelia Adams    |
| 53     | Thomas Collins  |
| 54     | Amelia Adams    |
| 55     | Isabella Chen   |
| 56     | Chloe Parker    |
| 57     | Ella Stewart    |
| 58     | Noah Brown      |
| 59     | Thomas Collins  |
| 60     | Chloe Parker    |
| 61     | Ella Stewart    |
| 62     | Benjamin Evans  |
| 63     | Mia Hall        |
| 64     | Ava Wilson      |
| 65     | Mason Kelly     |
| 66     | Grace Phillips  |
| 67     | Zoe Edwards     |
| 68     | Ava Wilson      |
| 69     | Ella Stewart    |
| 70     | Charlotte Baker |
| 71     | James Campbell  |
| 72     | Henry Scott     |
| 73     | Zoe Edwards     |
| 74     | Evelyn Roberts  |
| 75     | Grace Phillips  |
| 76     | Oscar Mitchell  |
| 77     | Ava Wilson      |
| 78     | Oscar Mitchell  |
| 79     | Liam Jones      |
| 80     | Benjamin Evans  |
| 81     | Ava Wilson      |
| 82     | Mason Kelly     |
| 83     | Leo Nelson      |
| 84     | Zoe Edwards     |
| 85     | Mia Hall        |
| 86     | Ella Stewart    |
| 87     | Amelia Adams    |
| 88     | Daniel Reed     |
| 89     | Zoe Edwards     |
| 90     | Samuel Morris   |
| 91     | Noah Brown      |
| 92     | Grace Phillips  |
| 93     | Olivia Smith    |
| 94     | Ava Wilson      |
| 95     | Jack Green      |
| 96     | Sophia Nguyen   |
| 97     | Leo Nelson      |
| 98     | Zoe Edwards     |
| 99     | Noah Brown      |
| 100    | Liam Jones      |
___

2. 
