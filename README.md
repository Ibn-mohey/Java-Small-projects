# Java-Small-projects
projects for Java Course in the ITI AI pro Track it consist of small projects to train Java and Big final project
## content 
1. [Lab Exercise 1 - Olympic Delegation](Olympic%20Delegation)
   > Convert the class diagrams made for these following systems to java classes.
    *  An Olympic Delegation representing a country consists of Players and Coaches
    *  Each Player and Coach must be part of a Delegation
    *  Each Player and Coach has personal info: Name and Address.
    *  Players can be part of a team (Basketball, etc) or individual
    *  A player or team may or may not have a coach assigned to him/her
    *  A coach can coach multiple players in the same or different games.
    *  In the tournament a player can get a Medal (only one medal type)


![](Olympic%20Delegation/UML.png)

2. [Lab Exercise 2 - Java IP cutter](Java_IPCutter)
    > Create a non-GUI Application that accepts a well formed IP Address in the form 
of a string and cuts it into separate parts based on the dot delimiter.
    
    >Hint : split(“\\.”)
    The program, for example:
    your Input : 
    163.121.12.30
    The result is :
    163<br>
    121<br>
    12<br>
    30<br>

3. [Lab Exercise 3 - Threads](Try_Thread)
    > Working with Threads in java throw Threads and Runnable

4. [Lab Exercise 4 - InputWriter](InputWriter)
    > reading data from console until user writes stop, Write the entered data to a file

5. [Lab Exercise 5 - CSV reader (DAO) ](PyramidsAnalysis)
    > Deal with Egyptian Pyramids [CSV dataset](https://www.kaggle.com/lsind18/egyptianpyramids) <br>
    > Prepare it and print the basic data about each pyramid
    > Explore the dataset (CSV file) and understand it’s parts

    > Build a Pyramid class to define a prototype for all information you will extract from
CSV for each pyramid. <br> Build a PyramidCSVDAO class to:
      * Read pyramids.csv file. Make this in thread
      * Create List of Pyramids objects for each pyramid in the csv file
      * Do not forget to validate the values you make all needed conversion.

    > Build a Main class to use PyramidCSVDAO class and print the basic data about each
pyramid.

6. [Lab Exercise 6 -betterStringMethod](betterStringMethod)
    > Your goal is to make a method called betterString that takes two Strings and a lambda 
that says whether the first or the two is “better”. 
<br>The method should return that better String; i.e., if the function given by the lambda 
returns true, the betterString method should return the first String, otherwise 
betterString should return the second String.
<br>
String string1 = ...; 
<br>
String string2 = ...; 
<br>
String longer = StringUtils.betterString(string1, string2, (s1, s2) -> s1.length() > s2.length()); <br>
String first = StringUtils.betterString(string1, string2, (s1, s2) -> true);<br>

7. [Lab Exercise 7 - Taitanic data EDA with java ](Taitanic_data_EDA_with_java)
    > Apply xChart for the Titanic Passengers Data Set :
   * graphPassengerAges
   * graphPassengerClass
   * graphPassengersurvived
   * graphPassengersurvivedGender

8. [Lab Exercise 8 - Polutation and Country analysis in Java](Polutation%20and%20Country%20analysis%20in%20Java)
    > Develop (in a team of 2) an application that reads two files for cities and countries 
and store each in a List. <br>
Create a map that uses the country code as keys and a list of cities as the value for 
each country. <br>
For a given country code (from Console) sort the cities according to the population

    > Provide classes or methods to get the following:
<br> Get a List of countries population
<br> Get the average countries population
<br> Get the maximum countries population
<br> Highest population city of each country
<br> Highest population capital

9. [Lab Exercise 9 - Using Spark on youtube Data](SaprkOnyoutubedata)
    >  For the dataset that contains US Youtube videos :
<br> we want to know the most popular title word, so we will focus on the title.
<br> we want to know the most popular tags, so we will focus on the tags.

    > [the data set]( https://www.kaggle.com/datasnaek/youtube-new)


### Final Project 

[The Project Guide Line](SpringWithSparkProject/1.Java_Final_Exercise_description.pdf)

* This project is web service to get the following from the data set:
    * Display structure and summary of the data. 
    * Clean the data (null, duplications) 
    * Count the jobs for each company and display that in order 
  * (What are the most demanding companies for jobs?)  in a pie chart
  * Find out What are it the most popular job titles?  in bar chart
  * Find out the most popular areas in bar chart 
  * Print skills one by one and how many each repeated and 
  * order the output to find out the most important skills required? 
  * Factorize the YearsExp feature and convert it to numbers in new col. 
   * Apply K-means for job title and companies
### Demo

[Small Video Demo](https://github.com/Ibn-mohey/Java-Small-projects/blob/main/SpringWithSparkProject/Project%20Demo.mkv)
