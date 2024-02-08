# Lab Report 3 - Bugs and Commands 
## Part 1 - Bugs 
Choose one of the bugs from week 4's lab.

Provide:

- A failure-inducing input for the buggy program, as a JUnit test and any associated code (write it as a code block in Markdown)
- An input that doesn't induce a failure, as a JUnit test and any associated code (write it as a code block in Markdown)
- The symptom, as the output of running the tests (provide it as a screenshot of running JUnit with at least the two inputs above)
- The bug, as the before-and-after code change required to fix it (as two code blocks in Markdown)
Briefly describe why the fix addresses the issue.


## Part 2 - Researching Commands 
For this portion of the report I decided to research the command `find`. This command helps find things recursively in the file system by different characteristics like name, type, size and others. 

### Option 1: `-iname`
This command is similar to the `-name` option in that it helps us search commands by name but here `-iname` is case insensitive. 

```
$ find technical/911report -iname "CHAPTER*"
technical/911report/chapter-13.4.txt
technical/911report/chapter-13.5.txt
technical/911report/chapter-13.1.txt
technical/911report/chapter-13.2.txt
technical/911report/chapter-13.3.txt
technical/911report/chapter-3.txt
technical/911report/chapter-2.txt
technical/911report/chapter-1.txt
technical/911report/chapter-5.txt
technical/911report/chapter-6.txt
technical/911report/chapter-7.txt
technical/911report/chapter-9.txt
technical/911report/chapter-8.txt
technical/911report/chapter-12.txt
technical/911report/chapter-10.txt
technical/911report/chapter-11.txt
```
In the example above, the `find` command looked through the specified directory (technical/911report) and found all the files and directroies that start with the word "chapter", no matter the capitalization. 


```
$ find technical/government -iname "*con*" 
technical/government/About_LSC/Special_report_to_congress.txt
technical/government/About_LSC/CONFIG_STANDARDS.txt
technical/government/About_LSC/conference_highlights.txt
technical/government/Gen_Account_Office/InternalControl_ai00021p.txt
technical/government/Post_Rate_Comm/ReportToCongress2002WEB.txt
technical/government/Media/Weak_economy.txt
```
The example above surrounding "con" with stars will produce an input of all the paths containing the substring "con", no matter the capitalization. Also, as you can see, the output produced is not contained within only technical/govenment directory. The find command search through all the sub-directories of government/ like About_LSC and Media. 

### Option 2: `-type`

### Option 3:

### Option 4: 


#### Sources:
I used a google search "find command options" to start my research and then used the below websites that have resulted from the search. 
[]([http://a.com](https://www.redhat.com/sysadmin/linux-find-command))
[](https://tecadmin.net/linux-find-command-with-examples/)

For example, we saw the -name option for find in class. For each of those options, give 2 examples of using it on files and directories from ./technical. Show each example as a code block that shows the command and its output, and write a sentence or two about what it’s doing and why it’s useful.

That makes 8 total examples, all focused on a single command. There should be two examples each for four different command-line options. Many commands like these have pretty sophisticated behavior possible – it can take years to be exposed to and learn all of the possible tricks and inner workings.

Along with each option/mode you show, cite your source for how you found out about it as a URL or a description of where you found it. See the syllabus on Academic Integrity and how to cite sources like ChatGPT for this class.
