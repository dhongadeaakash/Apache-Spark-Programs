# Apache-Spark-Programs
All the scripts in the program are developed using Apache Spark using Jupyter.
Refer http://spark.apache.org/docs/latest/api/python/pyspark.html for documentation <br>
The programs are based on Apache Spark using Python based on the mooc https://courses.edx.org/courses/BerkeleyX/CS100.1x/1T2015/info<br>
All the outputs of the programs are in the outputs folder
# Description of the Pograms
##Word Processing Program
The program performs a word Count on the given input text file (in this case big.txt) from http://norvig.com/big.txt . It takes a file removes the punctuation ,splits the lines into words ,performs a count function and then displays the top 15 words using sorting.
It is a python based script using PySpark API 
<br> Note Set the path of your file for big.txt as per your machine
##Web Sever Analysis Program
The This script performs analysis on the Web Server Log files which are in the Apache common log format.<br>
The fields in the format are <br>
<ul>
<li>Host</li>
<li>ClientID</li>
<li>user_id</li>
<li>date_time</li>
<li>method</li>
<li>endpoint</li>
<li>protocol</li>
<li>response_code</li>
<li>content_size</li>
</ul>
<br>
The dataset used in this program is available at (http://ita.ee.lbl.gov/html/contrib/NASA-HTTP.html) <br>
The following points are analysed in the script.<br>
1) Content Size Statistics (Average ,Minimum and Maximum)<br>
2) Response Code Analysis<br>
3) Host Frequency<br>
4) Number of Hits on Endpoints<br>
5) Error EndPoints<br>
6) Number of Unique Hosts<br>
7)  Number of Unique Hosts per Date<br>
8) Total  Number of 404 Response Codes along with top 20 404 Response Code EndPoints<br>
9) Listing 404 Response codes Per Day<br>
