# X-Team 004 Schedule Generator Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

The problem our team would like to solve is to create a program that allows the user to discover what classes they need to take over the course of their remaining years at UW Madison depending on their major. Our scheduler will generate a four year plan for students based on what classes they have already taken and avoiding classes that would be difficult to take at the same time.

## Questions to answer for Exercise #2

1. Name: Schedule Generator



2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Output would be in an excel file or google sheets file that contain a recommended schedule with lectures already choosen out for you. The program will automatically choose non-confliting lectures and will make sure your classes keep you on track towards your major. The classes choosen will be preferred towards your prefernces, early morning or late at night, how far can your classes be depending on your transportation, etc.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

You will have to input your college, your current year in college, your major and what classes you have already taken. You will also be asked some optional preference question like would you rather have morning classes or evening classes, would you rather have a busy day then a relaxed day or two half-busy days. How long do you want your lunch and what kind of transporation do you have. You can answer these questions through the programs UI. AP Credits and what classes can be skipped with the credit.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

Users will interact with text boxes and lists for inputing the class names, number of credits desired per semester, current year in college and other inputs. Buttons will allow the user to submit this information. Since the output is in excel format, it can be easily modified without many specific GUI elements.  

5. Types List: 

Our program would make use of a custom data structure in which we would have a priority queue that would give the highest priority to classes that you need for your major to graduate and other classes are given lower priority. The highest priority is given to prerequisite classes that must be taken in order for you to take other major required classes later on. The priority queue would interact with the input given taking into consideration classes you have already taken.
Another data structure that we would need to implement is an array list that consists of all of the classes the user has already taken and is currently taking.


Name each interface or class and briefly describe its function or purpose.

Our program would consist of 4 classes.
1. This class would keep track of classes that the user is taking and has taken.
2. Another class would keep track of classes that the user still needs to take depending on their major.
3. We need a class that handles classes that shouldn't be taken at the same time and prerequisites.
4. Finally we need a class for the GUI and a main method.
5. We will also include a test class to test the implementation of our priority queue and arrayList.


## Edit and Submit this file and any figures referenced by this document.

