# Relational-Databases-Build-a-Student-Database-Part-2-Project
## Relational Databases Independent Learning
I independently completed [my sixth project](https://www.freecodecamp.org/learn/relational-database/learn-sql-by-building-a-student-database-part-2/build-a-student-database-part-2) in freeCodeCamp's [Relational Databases course](https://www.freecodecamp.org/learn/relational-database/) to improve my shell scripting and SQL skills. This curriculum consisted of 14 guided projects, to be completed in a Gitpod environment. My notes outlining the names (et al) of these guided projects are [here](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project/blob/main/0%20relational-databases-course-overview.txt). This repository is for the sixth of these projects I completed as part of this.

## Adding Complex SQL Into the Project student_info.sh File
### Problem Solving
For this project, I had to produce a Bash script that used complex SQL statements to obtain information about computer science students from a database and alter said database. My notes on the full task brief for this are [here](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project/blob/main/1%20project-task-notes.txt). 
### Solution Workflow 
- To solve this problem, I first cloned the project boilerplate files in a Gitpod environment and followed 140 Bash and SQL lessons
- The [in-depth SQL notes I produced when completing this task are here](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project/blob/main/2%20relational-databases-build-a-student-database-part-2-project-guided-course-notes.txt). These notes include the Bash I used to reconstruct the [students.sql database](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project/blob/main/students.sql) used by the project. This database was constructed by the previous guided project in the course, [whose repository is here](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-1-Project)

- I split the VSCode terminal with dual PSQL and Bash prompts for this. The prior prompt was used to write SQL that extracted the correct set of information from the [students.sql database](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project/blob/main/students.sql) or altered it in the desired way

- Once the desired SQL statement was obtained in the PSQL prompt, it was then added to the project Bash program, [`student_info.sh`](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project/blob/main/student_info.sh). This was tested in the latter Bash terminal, using `./student_info.sh`

- This process was repeated for each of the SQL statements in [the project .sh file](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project/blob/main/student_info.sh). I created in-depth SQL notes for each of these iterations [which are here](https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project/blob/main/2%20relational-databases-build-a-student-database-part-2-project-guided-course-notes.txt)

## To Clone This Repository
```
git clone https://github.com/franpanteli/Relational-Databases-Build-a-Student-Database-Part-2-Project.git
```
