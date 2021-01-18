# SQL and noSQL Queries


In this repository you'll find SQL and noSQL queries. The SQL queries comes from two different websites: [HackerRank](https://www.hackerrank.com/dashboard) and a SQL free course (which I recommend) from [Udacity](https://classroom.udacity.com/) in this course were used SQLite as the database and in HackerRank I choose mySQL. Although they focus on teaching SQL, there are some difference between them: **Udacity** focus on teaching you SQL from the first "Select * from" to even advanced queries such as Window Functions and I 've collect some of my answers for the exercises. **HackerRank**, on the other hand, focus on test your SQL Skills(and why not teaching too, right?) by proposing different types of questions, and I also collect some answers of mine. Interesting fact is that some companies use HackerRank questions as a skill test for their technical interviews.

The noSQL queries comes from MongoDB(which is a document oriented database) and I have collect some answers to their challenges too. Unfornately, I did not save answers from the basics course, and all that I have here are the answers to their aggregate queries course. In fact, you'll find few answers in the MongoDB folder mainly because I had to focus my study in others technologies(big data tools). The reason why I choose MongoDB is because it is one of the most used noSQL Databases in the world, by clicking [here](https://db-engines.com/en/ranking) you can check the ranking, and by the time I wrote this MongoDB is at #5, losing only to relational databases. If you want to do know about the course I made click [here](https://university.mongodb.com/) they're all free(etlist when I wrote this) and they also have a carrer path, which I strongly recommend you to follow.

## Differences between SQL and noSQL databases

Since I came with this SQL-noSQL concept in this ReadME, I realize that would be nice to give a little context about what they are. Please keep in mind that this is only a shallow explanation, which has the goal to clarify the concepts. At the end of this text I'll put some links if you'd like to go deeply(which I also strongly recommend you to do).

### SQL Databases

SQL attends to **S**tructured **Q**uery **L**anguage and was developed in the 70's(I know too old, right?) by IBM researchers and even though 50 years have passed, it still remain as a very important programming language to learn. This language focus on bring results from a database, if you want to know some information that relies on your company database per say. This databases stores informations in tables, which means that every information within it, has a column and a row associated to it. What you do with SQL(some read it as SEQUEL) it's to write a query that selects a column from a specific database and you add some clauses to specify what you want. Therefore, if you want to add an information to your database you have to explicit the name of the column and the table that it belongs(bear that in mind, this is one of the biggest differences between SQL and noSQL). Think in an excel file, if you have a table with information of two columns: apple and oranges. You want to add information about bananas, in which column do you put this information? You add a new column called bananas and add the information that you want. Is the same with SQL.

### noSQL Databases

noSQL attends to **n**ot **o**nlySQL and it was developed by the end of this century(I'm not so sure) and has grown in importance in the late years mainly because big companies such as Amazon, Facebook starts using it and also by the rise of Big Data. These databases have the same objective as SQL Databases, they want to store information about something, the difference is how the do this. As I say above, SQL stores information as a table of content, noSQL databases, on the other hand, can store information in three different ways:

  * Document oriented: These are databases that look like documents such as JSON and XML files. Example: MongoDB
  * Key-value oriented: Databases that stores information with a key and its value(where should be the content of the row). Example: Redis
  * Graph oriented: Databases that stores information as a graph. Example: neo4j
 
Since they are not only SQL they have a benefit over SQL. Remember when I said that if you want information about something that it's not on your SQL table you have to add this column? It turns out that adding this column may cause some troubles to your table, and it's something that it's not wanted by the DBA(database administrators). When we're talking about noSQL databases adding a new column it's something easy to do, basically you just add the information as if the column always had been there.

