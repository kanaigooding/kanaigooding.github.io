---
layout: project
type: project
image: images/cplusplus.png
title: Record Database in C++
permalink: projects/recorddatabasecplusplus
# All dates must be YYYY-MM-DD format!
date: 2021-05-14
labels:
  - C++
  - VIM
  - UNIX
summary: A database designed to store and sort user information written using class functionality of C++.
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
