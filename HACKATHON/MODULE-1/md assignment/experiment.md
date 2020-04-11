#**Experiment**#<br>
##This is an experiment for Introduction to PHP
This introduction has following parts of PHP<br>
Introduction<br>
If statement<br>
While-loop<br>
Do While loop<br>
Array<br>
Array Associative<br>
Functions<br>
Recursive Functions<br>
Data Function<br>
MySql Database<br>
Session Handling<br>
Cookie Handling##<br>
##**Aim**## :
<li>Demonstrate working of PHP code</li>
<li>Create basic PHP script using peoper syntax</li>
##**Procedure : **##
###1]Demonstration###
<li>Click the execute PHP button and observe</li>
<ol>a. step by step execution of PHP code.</ol>
<ol>b.changes in HTML code and HTML page.</ol>
<li>Observe the location of the yellow band. It highlights the line being executed.</li>
<li>Observe the output shown on the right hand side.</li>
<li>Observe the html code generated during the execution at the server side, displayed below the PHP code.</li>
###2]Simulator###
Write the PHP script for the tasks mentioned in the experiment and click "Execute" button to verify the output.
##Theory##
###1.1 Introduction###<br>
PHP is widely used as an open source scripting language. PHP is an acronym for Hypertext Preprocessor. PHP scripts are executed on server and the HTML result is sent back to the client (Browser).PHP can generate dynamic page content. It can work with files on the server and can be used to collect form data. PHP can send and receive cookies. It can also work with database and can be easily embedded in HTML.PHP is widely used for Web Development.<br><br>
PHP script generally contains HTML tags and PHP script. Every PHP script is stored with .php extension. PHP script can run on any platform (Windows, Linux,etc) and is compatible with most of the web servers (Apache,IIS,etc.). PHP has a support for wide range of databases with which one can work.<br><br>
To start using PHP, we need a web server (host) with PHP and MySQL support along with PHP and MySQL installed on your PC or Laptop.<br><br>
Any browser can be used to access the file with php code.One can access it with web server's URL and the file name at the end.(e.g. If the name of the file is first.php then to access this file locally one can use http://localhost/first.php as URL.)<br><br>
###1.2 Basic Syntax###
PHP script can be placed anywhere in the document. PHP script starts with <?php and ends with?>.The script written between these two tags is parsed on the server and the plain HTML result is returned back. All php statements must end with **semicolon ( ; )**<br><br>
< **?php**<br>
code;<br>
?><br>
To run the script one needs a server enabled with PHP and a browser. PHP is loosely typed language.<br>
echo or print is used to print the output.<br>
E.g.following script will print "Welcome to PHP"<br><br>
< ?php<br>
echo " Welcome to PHP " ;<br>
?><br><br>
In PHP every variable starts with $ sign . The data types supported by PHP are String, Integer, Float Boolean, Array, Object etc.<br>
eg.<br>
< ?php<br>
$number_1=10;<br>
$number_2=35.5;<br>
$str ="HELLO";<br>
echo $number_1;<br>
echo $number_2;<br>
echo $str;<br>
?><br><br>
Here in PHP you don't have to specify data types as in other languages like C, C++,java etc. PHP converts the variable to the proper data type depending upon the value provided. i.e. in the example given above **number_1** will be integer and **number_2** will be float .Variable **str** will be of type String.<br><br>

experiment.md
Displaying experiment.md.