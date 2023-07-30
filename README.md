# Programming-Exercise-Reading-Log-Files
Assignments from OOP Course on Java Programming: Arrays, Lists, and Structured Data, week 3. https://www.coursera.org/learn/java-programming-arrays-lists-data/supplement/cAl9o/programming-exercise-reading-log-files

PROJECT TITLE: "Programming Exercise: Reading Log Files"

PURPOSE OF PROJECT: Modify existing code to work properly. Specifically,
                    in the LogAnalyzer class I need to complete the constructor 
                    to initialize records to an empty ArrayList and complete 
                    the readFile method to create a FileResource and to iterate 
                    over all the lines in the file. For each line, create a 
                    LogEntry and store it in the records ArrayList.
                    In the Tester class you will need to complete the testLogAnalyzer 
                    method, which creates a LogAnalyzer object, calls readFile on 
                    the data file short-test_log, and then calls printAll to print 
                    all the web logs.
                    Also, make use of Object oriented principle of programming.

DATE: 30.07.2023

HOW TO START THIS PROJECT: Use BlueJ Environment to open project named "package.bluej". 
                           Find inside of this project 4 classes: 
                           LogEntry (organizes all the variables from the WebLogParser
                           and return a string with them)
                           WebLogParser (take line from WebLog and make it an object of
                           type LogEntry that holds all information about specific log)
                           LogAnalyzer (stores all log entries and print them on the screen)
                           Tester - compile, create object of type Tester 
                           and start function: 
                           "testLogAnalyzer"; 
                           It chooses automatically one file from the project folder.
                           You may choose another one web log example file, but should modify
                           filename in the code.

AUTHOR: Gusev Roman

USER INSTRUCTIONS: if your time zone is different from Durham, 
                   USA, you may want to temporarily change the time zone on your 
                   computer as the time zone setting of your computer affects the 
                   output value from the getAccessTime method.
                   you will need 6 imports: 
                   "edu.duke.FileResource" (simplified version of 
                   File function from Java);
                   "java.text.SimpleDateFormat";
                   "java.text.ParsePosition";
                   "java.util.ArrayList", 
                   "java.util.Date";
                   "java.util.Locale;";
