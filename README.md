Download Link: https://assignmentchef.com/product/solved-relationaldatabase-assignment-2b
<br>
I have provided a sql script premiere_products.sql. Download it, run it and you have the required database and tables to work with for this assignment.  Put your name(s) and date in comments at the head. I will only mark your script if I can identify it by your name(s) in comments.

ADD the solutions of the queries below in this file. The queries should be answered in sequence and numbered correctly in comments.

<strong>Please write non-redundant code. You will lose marks for redundant/useless code, such as joining tables not required, grouping by where not required, displaying columns not asked for, using DISTINCT if not required etc. Please provide grammatically correct and meaningful relevant alias names for required fields in all select statements. Non-numeric literals must appear in quotes and numeric data without quotes and date with proper CAST. </strong>

<strong>All requirements carry marks and failure in following them will result in losing marks.</strong>

You need to follow the instructions below COMPLETELY and CORRECTLY. PLEASE ANSWER ALL QUERIES FROM THE INFORMATION GIVEN IN THE QUESTION – NO PEEKING IN THE TABLE DATA AND USING EXTRA INFORMATION FROM THERE.




<ol>

 <li>Use ONLY an OUTER JOIN to display the order number and order date for those orders that have exactly two different parts on the order. Sort the result in descending order number. For example, order number 21617 has two parts BV06 and CD52 on order.</li>

 <li>Use ONLY an OUTER JOIN to list the order number, part number, part description, price, quoted price and the price discount(= price – quoted_price) for those parts that are on order and the price discount &gt; 0. Order the result by part number. For example, part number AT94 with order number 21608 was given a discount of 3 dollars.</li>

</ol>




<ol start="3">

 <li>Use ONLY an INNER JOIN to list the rep number and full address (concatenate the street, city, state and zip <strong>each separated by a comma</strong>) of the rep, with the name of the customer he/she represents, if the rep number’s street contains Jackson. YOU NEED TO USE STRING FUNCTION(S) to check if the street contains Jackson and LIKE is not a function fyi. Sort the output by rep number. For example, rep 25 lives on street 124 Jackson.</li>

</ol>




<ol start="4">

 <li>Use ONLY an INNER JOIN to display the customer number and his/her order total, only for all his/her orders, if the order total &gt;= 1000. Sort the output by customer number. The total of any order is (quantity_ordered* quoted_price). For example, the order total for customer 408, who has two orders, is 4*329.95 + 1*399.99 = 1719.79</li>

</ol>




<ol start="5">

 <li>Use ONLY a JOIN to display the rep number and full name (concatenate the first and last name, <strong>separated by a blank</strong>) of the rep(s) who does not represent any customer currently. For example, rep number 99 (Anju Chawla) does not represent any customer.</li>

</ol>




<ol start="6">

 <li>Using a CORRELATED SUBQUERY ONLY (with exists/not exists), find the rep number and rep name (first name and last name concatenated) of each rep who represents a customer living in the zip 33321. Order the result by rep number. For example, rep number 25, Greg Smith has a customer living in that zip.</li>

</ol>




<ol start="7">

 <li>Using a CORRELATED SUBQUERY ONLY (with exists/not exists), find the customer number and name of each customer whose rep does not live in city Grove. Order the result by customer number. For example, the rep of customer number 282 (Brookings Direct) does not live in Grove city.</li>

</ol>




<ol start="8">

 <li>Use ONLY a subquery to find the number and name of each customer that currently has an order on file for a Washer (description of the part). No other information is available so code the solution only based on information given. For example, customer number 356 (Ferguson’s) has an order for Washer.</li>

</ol>







<ol start="9">

 <li>Use ONLY a subquery and the ANY(not ALL) keyword (NO INBUILT FUNCTION ALLOWED) to list the part number, part description, unit price and class for each part that has a unit price greater than the unit price of every part in the Appliances class, AP. Order the results by part number. For example, price of part number BV06 (Home Gym) is greater than the price of all parts in the AP class.</li>

</ol>


