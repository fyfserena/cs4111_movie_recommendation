## We are building a movie searching and recommendation website!

All the things are in progress! 

**Gist:** The user will be able to get a list of movies depending on the attributes (eg, genre, actors, and directors) or get the attributes of a particular movie. We scrape and parse data from websites like IMDB and use OMDB API to build our database. 

**E-R Diagram:**
![image](https://user-images.githubusercontent.com/46977839/110391869-1858e380-8036-11eb-9dc0-790c832c24eb.png)
(recommend a nice tool to dram ER diagram https://lucid.app/lucidchart/invitations/accept/b2a103c6-783b-4a3a-ba33-377722e40fe3)

* In the *DataScrapeAndClean.ipynb* file we create some tools to scrape, parse, clean data from different websites. 

  * The library we used in this part: 

    ​	**requests, re, json, BeautifulSoup, pandas** 

  

* We use **psycopg2** to connect to our database at postgreSQL. Created methods to insert, update, select data interacting with database.
