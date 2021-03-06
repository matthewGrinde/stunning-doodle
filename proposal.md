# X-Team 44 Project Proposal

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

Book stores are confusing for new students and can seem like mazes. They are large and filled with a large number of different books for an equally large number of classes. This program will store the location of the books in the store along with other pertinent information about the text book using a hash table. The user can search for a certain book using the program and recieve the location and info about the requested book. People working at the bookstore will be able to update the information shown to the users through admin privilages. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Student Textbook Helper

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The output will be the aisle the book is in, how many are left, and the name of the book that is on file.

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The input will include the ISBN number for each book, the name of the book, how many of each book are on the shelf (by updating every time a book is added or checked out), and the aisle number and shelf number of the book.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

We will use a simple graphic user interface and text menus to show books available in the aisles and display the details for each book. This should make it easier to search and view information in the program.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

For this programs we will need four key files. This will include a main, hashtable, node class, and the graphical interface (we do not know how to do that yet). We will also need and ADTInterface. 

Name each interface or class and briefly describe its function or purpose.

* Main- This class communicates with the user whether that be a student or someone with admin privilages trying to make changes to data.
* Node- This class outlines all the information that someone may need about specific books such as book title, ISBN, number aviliable, used vs. new, ect.
* Hashtable-  This is the main data structure used for this app. Things added to the hashtable will be able to be edited.
* Graphical interface- We do not know how to implement this yet but we will need to have some type of graphical interface that will be used along with the main to communicate with the user.

## Edit and Submit this file and any figures referenced by this document.

