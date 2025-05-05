# cs515-assignment-8-solved
**TO GET THIS SOLUTION VISIT:** [CS515 Assignment 8 Solved](https://www.ankitcodinghub.com/product/cs515-assignment-8-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100705&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS515 Assignment 8 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment, you need to create some Shell Scripts in the linux environment. Using shell script one can write a series of commands in a plain text file. It is just like a batch file in MS-DOS but is more powerful than the MS-DOS batch file. Shell scripts are useful to automate some periodic maintenance activities, helps in creating new commands also it helps the system administrator to avoid writing the same set of commands again and again.

To create a shell script, the basic steps are below-

<ul>
<li>Use any editor like vi to write shell script.</li>
<li>After writing the shell script, set execute permission for your script using chmod command. Example:
<pre>     $ chmod +x your-script-name
     $ chmod 755 your-script-name
</pre>
</li>
<li>To execute the shell script, following command can be used $ ./your-script-name
Let’s consider the shell script uinfo.sh

<pre>#!/bib/bash
# a simple shell script to show some basic information
clear
echo "Hello $USER"
echo "Today is "
date
echo "You are working in the directory"
pwd
</pre>
After saving the shell script, use the following command to change it to executable

<pre>$ chmod +x uinfo.sh
</pre>
To execute the shell script, type the following

$ ./uinfo.sh

A sample output of the script is as follows-

<pre>Hello seed
Today is
Thur Mar 24 22 08:17:19 IST 2022
You are working in the directory
/home/seed/CS515
</pre>
There are many good resources on shell script. Some of them are-

<pre>https://www.tutorialspoint.com/unix/shell_scripting.htm
www.shellscript.sh
</pre>
</li>
</ul>
1 Tasks to be carried out

Create and initialize a simple text database. For this purpose, you need to create the following scripts.

<ul>
<li>Script1: createTable.sh will be used to create a CPI table (a text file). The script should accept a table name and some field names. Example – CPI.tab may represent a table for CPI records. It will contain, say three fields – RollNo, Name and CPI.</li>
<li>Script2: insertRecord.sh will be used to insert records into the table. You need to provide a valid table name as one of the arguments. You can either insert one record at a time or you can insert multiple records using a single script2 invocation. You can use space as field separator.</li>
<li>Script3: updateRecord.sh will be used to update any field of the table. Use appropriate arguments for table name, field name, record number in the table and the new value using which the record will be updated.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2 General Guidelines

In each script, put some general comments like name of the developer, date of creation and the general purpose of the script. Put appropriate comment before each block of commands in the script. Exit with a status of zero when the script is able to correctly accomplish its task. Print an appropriate error message and exit with a nonzero status when the script is not able to accomplish its task.

3 Sample session

<pre>$ ./createTable.sh CPI.tab RollNo Name CPI
NEW TABLE ’CPI.tab’ WITH FIELDS ‘RollNo’, ‘Name’, ‘CPI’ CREATED
</pre>
<pre>$ ./insertRecord.sh CPI.tab -r "2021CS01" -n "Ravi" -c 7.9
RECORD ADDED TO ’CPI.tab’ table with ’RollNo’ 2021CS01, ’Name’ Ravi and ’CPI’ 7.9
</pre>
<pre>$ ./insertRecord.sh CPI.tab 3
Record 1
ENTER VALUES FOR RollNo: "2021CS02"
ENTER VALUES FOR Name: "Kiran"
ENTER VALUES FOR CPI: 8.0
Record 2
ENTER VALUES FOR RollNo: "2021CS03"
ENTER VALUES FOR Name: "Pranay"
ENTER VALUES FOR CPI: 8.4
Record 3
ENTER VALUES FOR RollNo: "2021CS04"
ENTER VALUES FOR Name: "Ali"
ENTER VALUES FOR CPI: 8.1
</pre>
<pre>3 RECORDS ADDED TO ’CPI.tab’ relation
</pre>
<pre>$ cat CPI.tab
RollNo Name CPI
2021CS01 Ravi 7.9
2021CS02 Kiran 8.0
2021CS03 Pranay 8.4
2021CS04 Ali 8.1
</pre>
<pre>$ ./updateRecord.sh CPI.tab -r "2021CS04" CPI 8.7
RECORD WITH ROLLNO 2021CS04 IS UPDATED in ’CPI.tab’ table
$ cat CPI.tab
RollNo Name CPI
2021CS01 Ravi 7.9
2021CS02 Kiran 8.0
2021CS03 Pranay 8.4
2021CS04 Ali 8.7
</pre>
</div>
</div>
</div>
