---
layout: project
type: project
image: images/panda.PNG
title: UH Code Submissions
permalink: projects/uhcodesubmissions
# All dates must be YYYY-MM-DD format!
date: 2021-05-14
labels:
  - Javascript
  - Meteor
  - MongoDB
  - GitHub
summary: A platform to prepare for technical interviews with challenging problems designed for ICS 314.  
---

I developed a Record Database in C++.  The database is based on a self-implemented singly linked list designed to store and sort information such as name, address, and account number.  

The user interface was designed to take user input, requiring character parsing to ensure quality of input.  

```c++
while ( theFile.eof( ) && theFile.good( ) )
 {
     getline( theFile, temp, ';' );
     istringstream ( temp ) >> uaccountno;

     getline( theFile, temp, ';' );
     strcpy( uname, temp.c_str( ) );
```
