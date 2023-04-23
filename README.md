Download Link: https://assignmentchef.com/product/solved-assignment-1-functional-overload
<br>
<h1>1. <strong>Objective</strong></h1>




The aim of this assignment is to have you practice on how to define functions, as well as beginning the development of critical thinking skills that will be essential for the remainder of the course. You are required to write <strong><em>twelve </em></strong>functions as specified below. However, it will be up to you on how to implement the required function and make sure that it works as intended. Do note that names of the function <strong><em>MUST</em></strong> be spelled as they are shown, along with any given parameter as well.







<ol start="2">

 <li><strong>Required Functions</strong></li>

</ol>







<h1>return_five()</h1>




<strong>Description</strong>: Will return the integer <strong>5</strong>.




<strong>Output</strong>: This function should not print anything to the screen.




<strong>Return Value</strong>: Return <strong>5</strong>.







<h1>return_pi()</h1>

<em> </em>

<em>            </em><strong>Description: </strong>Will return the floating-point number <strong>3.14</strong>.




<strong>Output</strong>: This function should not print anything to the screen.




<strong>Return Value</strong>: Return <strong>3.14</strong>.







<h1>return_hello()</h1>




<em>            </em><strong>Description: </strong>Will return the string “Hello”, excluding the quotation  marks.

<strong>Output</strong>: This function should not print anything to the screen.




<strong>Return Value</strong>: Return “Hello”.







<h1>return_True()</h1>




<em>            </em><strong>Description: </strong>Will return the Boolean value <strong>True</strong>.




<strong>Output</strong>: This function should not print anything to the screen.




<strong>Return Value</strong>: Return <strong>True</strong>.







<h1>determine_data_type(data)</h1>




<em>            </em><strong>Description: </strong>For a passed parameter <em>data</em>, the function will determine its  data type and print the result. So, for example, if <em>data = 5, </em>then the function should print “Integer”.




<strong>Output</strong>: This function should print one of the following, all  dependent on the data type of the parameter <em>data</em>:




<ul>

 <li>Integer</li>

 <li>Float</li>

 <li>String</li>

 <li>Boolean</li>

</ul>




Your output must match the sample output file exactly.




<strong>Return Value</strong>: This function should not return anything.







<h1>powTen(p)</h1>

<em> </em>

<strong>Description</strong>: Given a specified power <em>p</em>, the function will compute a  power of ten. In other words, if <em>p = 2</em>, then that means <em>10<sup>2</sup> = 100</em>.




<strong>Output</strong>: This function should not print anything to the screen.




<strong>Return Value</strong>: Return the calculated power of ten.







<h1>cubed(base)</h1>




<strong>Description</strong>: Given a specified base <em>base</em>, the function will compute its  cube. In other words, if <em>base = 2</em>, then that means <em>2<sup>3</sup> = 8</em>.




<strong>Output</strong>: This function should not print anything to the screen.




<strong>Return Value</strong>: Return the calculated cube for the given base.







<h1>fahrenheit_to_celcius(f)</h1>




<em>            </em><strong>Description: </strong>Given a temperature <em>f</em> that will be in degrees Fahrenheit,  convert it to its equivalent Celsius temperature. The conversion is given  as the following: <em><u>c</u> = (f – 32) * (5.0 / 9.0) </em>




<strong>Output</strong>: The function should print the passed Fahrenheit temperature <em>f</em>  (up to two decimal places) and the calculated Celsius temperature, also  up to two decimal places. For example, if <em>f</em> = 45, the output should be

“Fahrenheit temperature: 45.00; Celsius temperature: 7.22”




<strong>Return Value</strong>: This function should not return anything.







<h1>print_median_of_three(a, b, c)</h1>




<em>            </em><strong>Description: </strong>Given three integers <em>a</em>, <em>b</em>, and <em>c</em>, determine the median of all  three. Once determined, the function will print out which integer is the  median.




<strong>Output</strong>: This function should print “The median is: X”, where X is the  value of the integer that is the median. Your output must match the  sample output file exactly.




<strong>Return Value</strong>: This function should not return anything. <em>print_military_to_standard(mil_time)</em>




<strong>Description</strong>: Military time is used with a 24-hour format. To elaborate, if  it is 11:00 PM, then in military time that will be 2300 hours, or simply  23:00. Thus, given a military time, implement a function that will convert  it to standard time and print out the time, indicating whether it is AM or  PM. The input will always be an integer whose value will be within the  range of 0 and 23, with 0 being 12:00 AM, 1 being 1:00 AM, so on and so  forth.




<strong>Output</strong>: This function should print the standard time while also indicating  whether it is AM or PM. From the example provided in the <strong>Description</strong>, if  <em>mil_time</em> <em>= 23</em>, then the function should print “11:00 PM”.




<strong>Return Value</strong>: This function should not return anything.







<h1>get_ordinal_day(month, day)</h1>




<strong>Description</strong>: Assuming a regular year, that is, a non-leap year, determine the corresponding ordinal day for a given month and day. For example, if  the entered arguments are March 15<sup>th</sup>, then the corresponding ordinal  day will be 74. Note that <em>month</em> will be an integer whose value will be  within the range of 1 and 12, and <em>day</em> will also be an integer whose value  will be within the range of 1 and 31. During testing, correct values will be  passed so there will be no need for error-checking.

<strong> </strong>

<strong>            Output</strong>: This function should not print anything to the screen.




<strong>Return Value</strong>: Return the corresponding ordinal day for the passed date.







<h1>ordinal_day_error_checking(month, day)</h1>




<strong>Description</strong>: This function will have all of the functionality of the  <em>get_ordinal_day()</em> function, but now with error-checking. Suppose that  the arguments <em>-1, 4</em> are passed. The latter argument is valid, as it falls  within the range of acceptable values for <em>day</em>, but the former argument is  invalid as it falls outside of the range of acceptable values for <em>month</em>. An  important thing to consider is that not all months have 31 days: April only  has 30 days, whereas February only has 28! Thus, in the development of

this function, make sure to consider those special cases. Whenever an  invalid argument is encountered, return a -1. Otherwise, if the arguments  are valid, return the corresponding ordinal day.




<strong>Output</strong>: This function should not print anything to the screen.




<strong>Return Value</strong>: -1 if an invalid argument is encountered, otherwise return  the corresponding ordinal day.







<h2>3. Testing</h2>

<strong> </strong>

In testing your implementations of the above functions, you are allowed to test the functions individually using your own test cases.




However, it is highly recommended that you make use of the provided functionsTester.py program to obtain immediate feedback on your implemented functions. Please note that the functionsTester.py program makes use of the functionsTesterGenOutput.py script. As such, it is suggested that a new folder is created which contains the following three files: your program which contains the implemented functions (your program MUST be named functions.py, otherwise the functionsTester.py program will NOT work), the functionsTester.py script, and the functionsTesterGenOutput.py script.




To further elaborate on what the functionsTester.py script does, it will conduct a total of <strong>32</strong> tests on your implemented functions according to the following breakdown:




<ul>

 <li>return_five() – Test Case 1</li>

 <li>return_pi() – Test Case 2</li>

 <li>return_hello() – Test Case 3</li>

 <li>return_True() – Test Case 4</li>

 <li>determine_data_type() – Test Cases 5, 6, 7, and 8</li>

 <li>powTen() – Test Cases 9 and 10</li>

 <li>cubed() – Test Cases 11 and 12</li>

 <li>fahrenheit_to_celcius() – Test Cases 13, 14, 15, and 16</li>

 <li>print_median_of_three() – Test Cases 17, 18, 19, and 20</li>

 <li>print_military_to_standard() – Test Cases 21, 22, 23, and 24</li>

 <li>get_ordinal_day() – Test Cases 25, 26, 27, and 28</li>

 <li>ordinal_day_error_checking() – Test Cases 29, 30, 31, and 32</li>

</ul>

The functionsTester.py program will attempt to import your own program (functions.py), and the functionsTesterGenOutput.py program. If the import fails, the program will notify you and terminate testing.




If the import is successful, for each of the above functions, an attempt will be made on calling the function. If the function is misspelled or not yet defined, that particular test case will crash, and you will be notified. If the function is “improperly” <a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> defined, then you will fail that test case.




If none of the above occurs, and your implemented function was “properly” <sup>2</sup> defined, then a success will occur, and you pass that test case.




Once the program completes all 32 test cases, then a summary report will be displayed, and a summary report file (under the name of results.txt) will be created. The results.txt file contains information such as the test values that were used during testing, along with the number of test cases that were passed, the number of test cases that failed, and the number of test cases that crashed. The results.txt does NOT indicate specifically which test case was a pass, a fail, or crashed; the functionsTester.py program will output that information for your convenience so that you may adjust your efforts towards the successful implementation of the functions.







<ol start="4">

 <li><strong> Requirements </strong></li>

</ol>

<strong> </strong>

Your program MUST be named as functions.py.

<strong> </strong>

<strong> </strong>

<h2>5. Help &amp; Advice</h2>

<strong> </strong>

If you feel overwhelmed by this assignment, don’t be. A good starting point is to first create skeleton definitions of the required functions that returns dummy values. From there, work on the function that you feel is the easiest to implement. Once defined, run the functionsTester.py program and see if you were able to successfully implement it. From this point, rinse and repeat.




If you need any kind of clarification to anything on this assignment, such as if you’re confused about the requirements for one of the functions, or if you encounter a bug error that you are unable to figure out on your own, please send an email to <strong><u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="f89b908b888a979f8e9794b89f95999194d69b9795">[email protected]</a></u></strong>. You may expect a response within 24 to 48 hours

<a href="#_ftnref1" name="_ftn1">[1]</a> Please keep in mind that there is no right or wrong way of implementing something in programming. <sup>2</sup> Reference the above.