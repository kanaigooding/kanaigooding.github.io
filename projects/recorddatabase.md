---
layout: project
type: project
image: images/c.png
title: Record Database in C
permalink: projects/recorddatabase
# All dates must be YYYY-MM-DD format!
date: 2021-05-14
labels:
  - C
  - UNIX
  - VIM
summary: A record database developed in C for ICS 212: Programming Structure
---

I developed a Record Database in C.  The database is based on a self-implemented singly linked list designed to store and sort information such as name, address, and account number.  

The user interface was designed to take user input, requiring character parsing to ensure quality of input.  

```c
  newNode = malloc( sizeof( struct record ) );

     newNode->accountno = uaccountno;
     strcpy( newNode->name, uname );
     strcpy( newNode->address, uaddress);
     newNode->next = NULL;

```
