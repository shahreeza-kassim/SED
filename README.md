
---

# Student Engagement Dataset

The dataset will be made publicly available once the submitted paper is accepted. 

## Overview

This dataset contains information on student engagement. There are four .csv files that come with this dataset which are


1. **Student_grade_aggregated.csv**
2. **Student_grade_detailed.csv**
3. **Student_activity_summary.csv**
4. **Student_log.csv**

The first two files are grade related data. ```Student_activity_summary.csv``` data is merged and aggregated from ```Student_log.csv``` and ```Student_grade_aggregated.csv```.
Except for ```Student_log.csv``` each row on the remaining dataset represents a unique student and each column representing a different feature related to their engagement. 
The dataset consists of approximately 16,000 students across 2,000 courses from 21 different categories or faculties.

## Student_grade_aggregated
The dataset contains the aggregated student grade information and consists of 16,909 rows and 3 columns. Each column corresponds to
1.	**userid**- The unique identifier for each student.
2.	**number_of_courses**-The total number of courses completed by each student.
3.	**total_marks**-The sum of marks for all courses completed by each student.

## Student_grade_detailed
The dataset contains student’s grades information and consists of 90,089 rows and 5 columns. Each column corresponds to
1.	**userid**- The unique identifier for each student.
2.	**courseid** (2407 unique courses)-The unique identifier for each course.
3.	**formatted agreed mark**-The mark for each userid in the scale of 0-100 for each courseid.
4.	**actual grade**-The grade category for each userid, for each courseid. 
5.	**faculty**-The faculty which a course belongs to

## Student_log
This dataset contains student’s activity or engagement information. It consists of 12,139,424 rows and 6 columns and it is the largest file.  Each column corresponds to
1.	**userid**- The unique identifier for each student.
2.	**component** (36 unique components)-Moodle’s user interface components.
3.	**action** (37 unique actions)- The actions taken by a user on a target.
4.	**target** (74 unique targets)-The target component of an action by a student.
5.	**courseid** (2826 unique courses)-The course id resources accessed by a user. 
6.	**timecreated**-The time when a user accessed a particular resource.

## Student_activity_summary
It consists of 16,909 rows and 20 columns. Each column corresponds to
1.	**userid**- The unique identifier for each student.
2.	**no_of_courses**- The total number of courses taken by each student.
3.	**average_marks**- The marks are normalised by the number of courses taken by each student.
4.	**total_login**- The total number of LMS logins by each student. 
5.	**weekend_login**- The number of LMS logins during the weekend by each student. 
6.	**weekday_login**- The total number of LMS logins during the weekday by each student.
7.	**midnight _login**- The total number of LMS logins from 12am to 4am by each student.
8.	**early_morning_login**- the total number of LMS logins from 4am to 8am by each student.
9.	**late_morning_login**- The total number of LMS logins from 8am-12pm for each student.
10.	**afternoon_login**- The total number of LMS logins from 12pm-4pm for each student.
11.	**evening_login**- The total number of LMS logins from 4pm-8pm for each student.
12.	**night_login**- The total number of LMS logins from 8pm-12am for each student.
13.	**no_of _viewed_courses**- The total number of views across all courses taken by each student.
14.	**no_of_attendance_taken**- The total number of attendances taken in LMS by each student.
15.	**no_of_all_files_downloaded**- The total number of files downloaded from LMS by each student.
16.	**no_of_assignments**- The total number of assignments submitted by each student across all courses.
17.	**no_of_forum_created**- The total number of forums participated by each student. This includes starting a topic or continuing/replying to a topic/thread.
18.	**no_of_quizzes**-The total number of quizzes across all courses each student has.
19.	**no_of_quizzes_completed**- The total number of quizzes completed by each student across all courses.
20.	**no_of_quizzes_attempt**- The total number of quizzes attempted by each student across all courses.




## Usage

This dataset can be used for the following purposes:
- Analyzing patterns in student engagement.
- Predicting academic outcomes based on engagement levels.
- Identifying factors that contribute to higher or lower student engagement.


## Contact

For any questions or inquiries, please contact ``` shahreeza at um.edu.my ``` .

## License and Copyright

This project is open source under the BSD-3 license.

© 2024 Universiti Malaya.

---

