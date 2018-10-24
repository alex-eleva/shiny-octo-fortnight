# X-Team 51 Task Manager

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

A problem that our team would like to solve is the problem of managing/scheduling/prioritizing various asks effectively, in order to be efficient in our day to day lives. 

Our program aims to solve that problem by allowing users to schedule tasks, and prioritize them based on different criteria (type of event, date, importance, etc). Users will be able to create an account, which they can use to login and create their own tasks and add it to a to-do list that they can update. They will be able to mark their progress by checking off items and deleting them from the list. Furthermore, multiple lists will be able to be created to group tasks that are of the same type.

We plan to test our program by testing different classes and their functionality. We are most likely going to use JUnit to achieve this. 

**1. Name: Task Manager**

**2. Output: Describe the output your program will produce.  Include and example format of the output produced.**

A GUI "to-do list" arranged in the order that the user chooses to prioritize the events in.

**3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.**

The user will input the information needed in GUI pop up.

**4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.**

We plan on using a simple graphic user interface so different users can sign into their account and see their personal list.
The GUI will display ouput based on the user's input.

**5. Types List: Break your solution idea down into units that you think can be implemented with a single class.**

 * Task Class
 The event class will be used to create event objects. Events will have certain properties, including name, description, type, priority, and date.
 
 * User Class
 The user class will store information of different users that use the program, storing their username and password, as well as potentially their profile information.
 
 * List Class
 Keeps track of verious task lists. 
 



## Edit and Submit this file and any figures referenced by this document.

