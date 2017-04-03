-------------------------------------------------------
INTRODUCTION
-------------------------------------------------------
Class: CS 421 - Theory of Computing
Assignment: Programming #1
Language: Java
Executable file: castillo_prog1.jar
Test file: messagefile.txt

-------------------------------------------------------
DESCRIPTION
-------------------------------------------------------
Develop a program that parses a file of email blocks
and determine which email is a spam based on a defined
finite automata. The following are accepted strings:
1) "free access"
2) "free software"
3) "free vacation"
4) "free trials"
5) "win"
6) "winner"
7) "winners"
8) "winnings"

-------------------------------------------------------
RUNNING EXECUTABLE FILE ONLY
-------------------------------------------------------
Refer to Step 4 and/or Step 5 
in the "COMPILING & RUNNING" section below.

-------------------------------------------------------
COMPILING & RUNNING
-------------------------------------------------------
Step 1: Put the following files into the same directory:
1) all *.java files specified below:
 a) EmailInfo.java
 b) EmailTracker.java
 c) Program.java (Main program)
 d) SpamParser.java
 e) States.java
2) messagefile.txt (or any other file to parse)

Step 2: Compile java files into class files
Example-> javac *.java

Step 3: Generate .jar file
Example-> jar cvfe castillo_prog1.jar Program *.class

Step 4: Run jar
Example-> java -jar castillo_prog1.jar

Step 5 (optional): Run jar with specified file
Example-> java -jar castillo_prog1.jar fileToParse.txt

Note: fileToParse.txt can be any other file and must reside 
in the same directory as the jar file.