# cmpt135-assignment-1--basic-c-features-solved
**TO GET THIS SOLUTION VISIT:** [CMPT135 Assignment 1- Basic C++ Features Solved](https://www.ankitcodinghub.com/product/cmpt135-assignment-1-basic-c-features-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120365&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT135 Assignment 1- Basic C++ Features Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
Lets get re-acquainted with basic C++ programming. We’ll do that by implementing some useful command-line utilities.

Getting Started

Question 1

Compile the file line_check.cpp using the makefile like this:

“`

make line_check g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g line_check.cpp -o line_check “`

When you run it on sample_lines.txt you should see this:

â¯ ./line_check &lt; sample_lines.txt Line 4 is too long. Line 6 is too long.

Modify line_check.cpp so that, in addition to printing which lines are too long, it prints how long those lines are:

â¯ ./line_check_a1 &lt; sample_lines.txt Line 4 is too long: 101 characters Line 6 is too long: 110 characters

Put your program for this question in line_check_a1.cpp, and make sure it compiles with the makefile.

Question 2

Modify your program from Question 1 to allow a maximum line length to be passed as a command-line parameter: “` â¯ ./line_check_a1 100 &lt; sample_lines.txt Line 4 is too long: 101 characters Line 6 is too long: 110 characters â¯ ./line_check_a1 200 &lt; sample_lines.txt No lines are too long. “`

The parameter is optional. If no parameter is given, then use a line length of 100:

â¯ ./line_check_a1 &lt; sample_lines.txt Line 4 is too long: 101 characters Line 6 is too long: 110 characters

If more than one parameter is passed, then print an error message and exit:

â¯ ./line_check_a2 100 200 &lt; sample_lines.txt Too many arguments. Usage: ./line_check_a2 [max_line_length]

Similarly, if the passed-in parameter is not an integer that’s 0 or bigger, then print an error message and exit:

â¯ ./line_check_a2 -100 &lt; sample_lines.txt Invalid argument: -100 Usage: ./line_check_a2 [max_line_length]

Put your program for this question in line_check_a2.cpp, and make sure it compiles with the makefile.

Question 3

Linux has a built-in program called sort that sorts the lines of a text file. For example:

“` â¯ cat names.txt # cat prints the contents of a file Rick Morty Summer Uncle Slow Evil Morty Jerry Beth â¯ sort names.txt Beth Evil Morty Jerry Morty Rick Summer Uncle Slow “`

Your task is to implement a program named mysort that sorts lines of text of a given file in alphabetical order. When mysort is called without any options, it should print the same thing as built-in sort:

â¯ ./mysort names.txt Beth Evil Morty Jerry Morty Rick Summer Uncle Slow

Important – Unlike the line checking programs above, mysort does not use the &lt; re-direction operator when reading a file name. The file name is instead passed to the program as a command-line parameter. – mysort does not modify the passed-in file; it always prints its output to cout.

./mysort also has two command-line options:

-r: reverse the order of the sort, i.e. the lines are printed in reverse alphabetical order

s: print lines in order starting with the shortest and going to the longest; lines of the same length are in alphabetical order

The general syntax of mysort is:

./mysort filename [-r|-s]

This means that you must pass exactly one file to ./mysort, and then, optionally, you can put either (but not both!) the -r or -s option after the filename. For example:

“` â¯ ./mysort names.txt -r Uncle Slow Summer Rick Morty Jerry Evil Morty Beth â¯ ./mysort names.txt -s Beth Rick Jerry Morty Summer Evil Morty Uncle Slow “`

-r and -s are the only options allowed, and at most one of them can be given for a call to mysort. If you don’t call mysort with exactly one file and at most one of -r or -s, then print an error message (at least as descriptive as in the examples) and return. For example:

“` â¯ ./mysort names.txt -sr Error: unknown option “-sr” Usage: ./mysort input_file.txt [-r|-s] -r: sort in reverse order -s: sort in increasing order of string length

â¯ ./mysort_sol names.txt -s -s Error: invalid number of arguments Usage: ./mysort_sol input_file.txt [-r|-s] -r: sort in reverse order -s: sort in increasing order of string length

â¯ ./mysort Error: invalid number of arguments Usage: ./mysort input_file.txt [-r|-s] -r: sort in reverse order -s: sort in increasing order of string length

â¯ ./mysort_sol blurb Error: unable to open file “blurb” Usage: ./mysort input_file.txt [-r|-s] -r: sort in reverse order -s: sort in increasing order of string length “`

For this assignment, to test if a file has been successfully opened it is enough to check whether input_file.fail() returns true or false (where input_file is a C++ ifstream object).

Put your program for this question in mysort.cpp, and make sure it compiles with the makefile.

Hints: – If s and t are C++ string variables, then s &lt; t is true just when s comes before t alphabetically. – If you first sort the lines alphabetically, then you can use std::stable_sort to sort the lines by length while keeping lines of the same length in alphabetical order. – The diff command tests if two files are the same. For example, the command diff out.txt sorted_data.txt prints all the differences of the files out.txt and sorted_data.txt (and prints nothing if they are identical). This can be handy for testing the output of your program.

Submitting Your Work

Please put all your .cpp files for the questions above into a folder named a1, and then compress this to a zip file named a1.zip.

Do not submit any unnecessary files or folders.

How Your Code Will be Compiled by the Marker

The marker will compile and run your code on Ubuntu Linux using the given makefile:

“`console

make line_check_a1 g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g line_check_a1.cpp -o line_check_a1

./line_check_a1 … “`

If you’ve chosen to compile your program using a different method, then before you submit your programs please make sure to test that they compile with this makefile.

Marking Scheme

Question 1

Efficiency, 1 mark

Question 2

Efficiency, 1 mark

Question 3

General Marking Scheme

Completeness

Are all the required features fully implemented? Are any missing? Extra features are usually okay as long as they do not interfere with the required features.

Correctness

Are their any flaws in the program? Does everything work as specified?

Efficiency

Does the program run efficiently, and avoid doing unnecessary work and using unnecessary memory? Have the appropriate data structures and algorithms been used?

Usability

Is the program easy to use for its intended users? Is the output (including error messages!) easy to read (e.g. good spelling, good grammar, nice formatting)? This also includes things like using the requested file and class names, submitting a program that compiles using a given makefile, etc.

Source Code Readability

While readability is somewhat subjective, here are some guidelines:

All names of variables, functions, structs, classes, etc. are sensible, self-descriptive, and consistent.

Indentation and spacing is perfectly consistent and matches the structure of the program. All blank lines, indents, and extra spaces have a reason.

All lines are 100 characters in length, or less.

Comments are used when appropriate, e.g. to describe code that is tricky or very important. There are no unnecessary comments, and no commented-out code.

Overall, the source code is easy to read and understand.

Other Deductions

valgrind ./some_prog

// … lots of output … “`

A program is considered to have no memory leaks if:

In the LEAK SUMMARY, definitely lost, indirectly lost, and possibly lost are all 0. ERROR SUMMARY reports 0 errors.

If valgrind reports any errors for a run of your program, your assignment will get a deduction as described below.

A score of 0 if one or more of the following are true:

You don’t include the “Statement of Originality”, or it is modified in any way.
