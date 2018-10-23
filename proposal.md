# Friendopedia
# X-Team 79 Project Proposal

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

We are trying to develop a data structure that helps people make friends. Each node will represent a person and each person can have many friends. We want to connect people in the graph with people they have in common or potentially traits they have in common.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

   Friendopedia

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Our program will output a list of possible friends. 

*Recommended friends in your area:*

```
Name:                Bob 
Age:                 20
Friends in common:   Charlie
Interests in common: Frisbee
```

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
The input data for our program would be an individuals name, their age, their interests, and their closest friends.
```
Name:               Bob
Want to Friend:     Jim
```
4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
   **Text Menu with options:**
   1. "Add Friend"
   2. "Find Friend"
   3. "Remove Friend"
   4. "Edit Profile"


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.



Name each interface or class and briefly describe its function or purpose.

Our program would have a Friends class and a Person class. The Friends class would create a graph to hold all of the people signed up to Friendopedia. The Person class would create a person with unique information about the person it represents.


## Edit and Submit this file and any figures referenced by this document.

