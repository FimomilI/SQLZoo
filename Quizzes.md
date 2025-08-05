<!-- omit in toc -->
# Tutorials: Learn SQL step by step

This file contains the solutions to the quiz's questions posed by <https://sqlzoo.net/wiki/Tutorial_Quizzes>.



<!-- omit in toc -->
## Table of Contents

- [1. SELECT Quiz (last edited 01/08/2025)](#1-select-quiz-last-edited-01082025)
- [2. BBC Quiz](#2-bbc-quiz)
- [3. Nobel Quiz](#3-nobel-quiz)
- [4. Nested SELECT Quiz](#4-nested-select-quiz)
- [5. SUM and COUNT Quiz (last edited 22/07/2025)](#5-sum-and-count-quiz-last-edited-22072025)
- [6. JOIN Quiz (last edited 27/07/2025)](#6-join-quiz-last-edited-27072025)
- [7. JOIN Quiz 2 (last edited 29/07/2025)](#7-join-quiz-2-last-edited-29072025)
- [8. Using Null Quiz (last edited 30/07/2025)](#8-using-null-quiz-last-edited-30072025)
- [9. Self JOIN Quiz (last edited 05/08/2025)](#9-self-join-quiz-last-edited-05082025)



## 1. SELECT Quiz (last edited 01/08/2025)

Webpage <https://sqlzoo.net/wiki/SELECT_Quiz>.


<!-- omit in toc -->
### 1. Select the code which produces this table

![Q1q1](assets/quiz_answers/Quiz1.question1.png)

---


<!-- omit in toc -->
### 2. Pick the result you would obtain from this code

```SQL
SELECT name, population
FROM world
WHERE name LIKE "Al%"
```

![Q1q2](assets/quiz_answers/Quiz1.question2.png)

---


<!-- omit in toc -->
### 3. Select the code which shows the countries that end in A or L

![Q1q3](assets/quiz_answers/Quiz1.question3.png)

---


<!-- omit in toc -->
### 4. Pick the result from the query

```SQL
SELECT name,length(name)
FROM world
WHERE length(name)=5 and region='Europe'
```

![Q1q4](assets/quiz_answers/Quiz1.question4.png)

---


<!-- omit in toc -->
### 5. Here are the first few rows of the world table

![Q1q5table](assets/quiz_answers/Quiz1.question5.table.png)

```SQL
SELECT name, area*2 FROM world WHERE population = 64000
```

![Q1q5](assets/quiz_answers/Quiz1.question5.png)

---


<!-- omit in toc -->
### 6. Select the code that would show the countries with an area larger than 50000 and a population smaller than 10000000

![Q1q6](assets/quiz_answers/Quiz1.question6.png)

---


<!-- omit in toc -->
### 7. Select the code that shows the population density of China, Australia, Nigeria and France

![Q1q7](assets/quiz_answers/Quiz1.question7.png)


<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>

---




## 2. BBC Quiz

Webpage: <https://sqlzoo.net/wiki/BBC_QUIZ>.


<!-- omit in toc -->
### 1.



---


<!-- omit in toc -->
### 2.



---


<!-- omit in toc -->
### 3.



---


<!-- omit in toc -->
### 4.



---


<!-- omit in toc -->
### 5.



---


<!-- omit in toc -->
### 6.



---


<!-- omit in toc -->
### 7.




<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>

---




## 3. Nobel Quiz

Webpage: <https://sqlzoo.net/wiki/Nobel_Quiz>.


<!-- omit in toc -->
### 1.



---


<!-- omit in toc -->
### 2.



---


<!-- omit in toc -->
### 3.



---


<!-- omit in toc -->
### 4.



---


<!-- omit in toc -->
### 5.



---


<!-- omit in toc -->
### 6.



---


<!-- omit in toc -->
### 7.




<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>

---




## 4. Nested SELECT Quiz

Webpage: <https://sqlzoo.net/wiki/Nested_SELECT_Quiz>.


<!-- omit in toc -->
### 1.



---


<!-- omit in toc -->
### 2.



---


<!-- omit in toc -->
### 3.



---


<!-- omit in toc -->
### 4.



---


<!-- omit in toc -->
### 5.



---


<!-- omit in toc -->
### 6.



---


<!-- omit in toc -->
### 7.




<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>

---




## 5. SUM and COUNT Quiz (last edited 22/07/2025)

Webpage: <https://sqlzoo.net/wiki/SUM_and_COUNT_Quiz>.


<!-- omit in toc -->
### 1. Select the statement that shows the sum of population of all countries in 'Europe'

![Q5q1](assets/quiz_answers/Quiz5.question1.png)

---


<!-- omit in toc -->
### 2. Select the statement that shows the number of countries with population smaller than 150000

![Q5q2](assets/quiz_answers/Quiz5.question2.png)

---


<!-- omit in toc -->
### 3. Select the list of core SQL aggregate functions

![Q5q3](assets/quiz_answers/Quiz5.Question3.png)

---


<!-- omit in toc -->
### 4. Select the result that would be obtained from the following code

```SQL
 SELECT region, SUM(area)
   FROM bbc
  WHERE SUM(area) > 15000000
  GROUP BY region
```

![Q5q4](assets/quiz_answers/Quiz5.question4.png)

---


<!-- omit in toc -->
### 5. Select the statement that shows the average population of 'Poland', 'Germany' and 'Denmark'

![Q5q5](assets/quiz_answers/Quiz5.question5.png)

---


<!-- omit in toc -->
### 6. Select the statement that shows the medium population density of each region

![Q5q6](assets/quiz_answers/Quiz5.question6.png)

---


<!-- omit in toc -->
### 7. Select the statement that shows the name and population density of the country with the largest population

![Q5q7](assets/quiz_answers/Quiz5.question7.png)

---


<!-- omit in toc -->
### 8. Pick the result that would be obtained from the following code

```SQL
 SELECT region, SUM(area)
   FROM bbc 
  GROUP BY region
 HAVING SUM(area) <= 20000000
```

![Q5q8](assets/quiz_answers/Quiz5.question8.png)


<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>

---




## 6. JOIN Quiz (last edited 27/07/2025)

Webpage: <https://sqlzoo.net/wiki/JOIN_Quiz>.


<!-- omit in toc -->
### 1. You want to find the stadium where player 'Dimitris Salpingidis' scored. Select the JOIN condition to use

![Q6q1](assets/quiz_answers/Quiz6.Question1.png)

---


<!-- omit in toc -->
### 2. You JOIN the tables _goal_ and _eteam_ in an SQL statement. Indicate the list of column names that may be used in the SELECT line

![Q6q2](assets/quiz_answers/Quiz6.question2.png)

---


<!-- omit in toc -->
### 3. Select the code which shows players, their team and the amount of goals they scored against Greece(GRE)

![Q6q3](assets/quiz_answers/Quiz6.question3.png)

---


<!-- omit in toc -->
### 4. Select the result that would be obtained from this code

```SQL
SELECT DISTINCT teamid, mdate
  FROM goal JOIN game on (matchid=id)
 WHERE mdate = '9 June 2012'
```

![Q6q4](assets/quiz_answers/Quiz6.question4.png)

---


<!-- omit in toc -->
### 5. Select the code which would show the player and their team for those who have scored against Poland(POL) in National Stadium, Warsaw

![Q6q5](assets/quiz_answers/Quiz6.question5.png)

---


<!-- omit in toc -->
### 6. Select the code which shows the player, their team and the time they scored, for players who have played in Stadion Miejski (Wroclaw) but not against Italy(ITA)

![Q6q6](assets/quiz_answers/Quiz6.question6.png)

---


<!-- omit in toc -->
### 7. Select the result that would be obtained from this code

```SQL
SELECT teamname, COUNT(*)
  FROM eteam JOIN goal ON teamid = id
 GROUP BY teamname
HAVING COUNT(*) < 3
```

![Q6q7](assets/quiz_answers/Quiz6.question7.png)


<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>

---




## 7. JOIN Quiz 2 (last edited 29/07/2025)

Webpage: <https://sqlzoo.net/wiki/JOIN_Quiz_2>.


<!-- omit in toc -->
### 1. Select the statement which lists the unfortunate directors of the movies which have caused financial loses (gross < budget)

![Q7q1](assets/quiz_answers/Quiz7.question1.png)

---


<!-- omit in toc -->
### 2. Select the correct example of JOINing three tables

![Q7q2](assets/quiz_answers/Quiz7.question2.png)

---


<!-- omit in toc -->
### 3. Select the statement that shows the list of actors called 'John' by order of number of movies in which they acted

![Q7q3](assets/quiz_answers/Quiz7.question3.png)

---


<!-- omit in toc -->
### 4. Select the result that would be obtained from the following code

```SQL
SELECT title
  FROM movie JOIN casting ON (movieid = movie.id)
             JOIN actor   ON (actorid = actor.id)
 WHERE name = 'Paul Hogan'
   AND ord = 1
```

![Q7q4](assets/quiz_answers/Quiz7.question4.png)

---


<!-- omit in toc -->
### 5. Select the statement that lists all the actors that starred in movies directed by Ridley Scott who has id 351

![Q7q5](assets/quiz_answers/Quiz7.question5.png)

---


<!-- omit in toc -->
### 6. There are two sensible ways to connect movie and actor. They are

![Q7q6](assets/quiz_answers/Quiz7.question6.png)

---


<!-- omit in toc -->
### 7. Select the result that would be obtained from the following code

```SQL
SELECT title, yr
  FROM movie, casting, actor
 WHERE name = 'Robert De Niro'
   AND movieid = movie.id
   AND actorid = actor.id
   AND ord = 3
```

![Q7q7](assets/quiz_answers/Quiz7.question7.png)


<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>

---




## 8. Using Null Quiz (last edited 30/07/2025)

Webpage: <https://sqlzoo.net/wiki/Using_Null_Quiz>.


<!-- omit in toc -->
### 1. Select the code which uses an outer join correctly

![Q8.q1](assets/quiz_answers/Quiz8.question1.png)

---


<!-- omit in toc -->
### 2. Select the correct statement that shows the name of department which employs Cutflower -

![Q8.q2](assets/quiz_answers/Quiz8.question2.png)

---


<!-- omit in toc -->
### 3. Select out of following the code which uses a JOIN to show a list of all the departments and number of employed teachers

![Q8.q3](assets/quiz_answers/Quiz8.question3.png)

---


<!-- omit in toc -->
### 4. Using `SELECT name, dept, COALESCE(dept, 0) AS result FROM teacher` on `teacher` table will

![Q8.q4](assets/quiz_answers/Quiz8.question4.png)

---


<!-- omit in toc -->
### 5. Query

```SQL
SELECT name,
       CASE WHEN phone = 2752 THEN 'two'
            WHEN phone = 2753 THEN 'three'
            WHEN phone = 2754 THEN 'four'
            END AS digit
  FROM teacher
```

shows following 'digit'

![Q8.q5](assets/quiz_answers/Quiz8.question5.png)

---


<!-- omit in toc -->
### 6. Select the result that would be obtained from the following code

```SQL
SELECT name,
     CASE
       WHEN dept
       IN (1)
       THEN 'Computing'
       ELSE 'Other'
     END
 FROM teacher
```

![Q8.q6](assets/quiz_answers/Quiz8.question6.png)


<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>

---




## 9. Self JOIN Quiz (last edited 05/08/2025)

Webpage: <https://sqlzoo.net/wiki/Self_join_Quiz>.


<!-- omit in toc -->
### 1. Select the code that would show it is possible to get from Craiglockhart to Haymarket

![alt text](assets/quiz_answers/Quiz9.question1.png)

---


<!-- omit in toc -->
### 2. Select the code that shows the stops that are on route.num '2A' which can be reached with one bus from Haymarket

![alt text](assets/quiz_answers/Quiz9.question2.png)

---


<!-- omit in toc -->
### 3. Select the code that shows the services available from Tollcross

![alt text](assets/quiz_answers/Quiz9.question3.png)


<div align="right">

  [![header](https://img.shields.io/badge/back_to-TOC-grey?style=flat-square)](#table-of-contents)
</div>
