Download Link: https://assignmentchef.com/product/solved-cs6314-practice-work-5
<br>
Every 10 years, the Social Security Administration provides data about the 1000 most popular boy and girl names for children born in the US for each gender at

<a href="https://www.ssa.gov/OACT/babynames/">https://www.ssa.gov/OACT/babynames/</a>

<a href="https://www.ssa.gov/OACT/babynames/top5names.html">https://www.ssa.gov/OACT/babynames/top5names.html</a>

Your task for this assignment is to display the baby names and their popularity rankings for a given year and gender. You will implement the project by using PHP and MySQL.

There will be one single php page: babynames.php. When the page is loaded for the first time, it will not display any results.  It will have two drop down list, one for year and one for gender.  The default option for year is “All years” and other options are years between 2005 and 2015 (including both). For gender default is “Both” and other options are ”male” and ”female”. Provide a submit button to show the results for selected year and gender.

Once the form is submitted, you will connect to the database and fetch the top-five popular names for the selected year and gender.<sup>*</sup> Results will be displayed in a table. Along with each baby name, you will also list the popularity ranking, gender and the year. Order the names based on year, gender and ranking, respectively.

For database part, you will create a table with following schema:

Database name: SSA

BabyNames (name, <u>year</u>, <u>ranking</u>, <u>gender</u>)

name: varchar(20)

year: int

ranking: small int

gender: char(1)




Use attached sql file to insert records into your table. In phpMyAdmin, goto SQL tab and copy and paste “INSERT INTO” statements into the sql window, and execute them.

<strong>Important reminder:  </strong>Make sure your database name, table name and attribute names match with given names. If your database connection parameters are different from the default (host: localhost, username: root, password: root), ensure to change them as default while submitting your work. Otherwise you will lose points for not complying with the standards of the assignment.

Send multiple screenshots of your application (with different options) along with the source code.  Zip screenshots and source code into yournetid-PW5.zip.

* In database, for any given year and gender we only have top-five names so you don’t need to limit results to top 5.