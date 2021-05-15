---
layout: project
type: project
image: images/micromouse.jpg
title: Webcrawler
permalink: projects/webcrawler
# All dates must be YYYY-MM-DD format!
date: 2015-07-01
labels:
  - C
  - UNIX
  - VIM
summary: A record database developed in C for ICS 212: Programming Structure
---

I developed a Record Database in C.  The database is based on a self-implemented singly linked list designed to store and sort information such as name, address, and account number.  

The user interface was designed to take user input, requiring character parsing to ensure quality of input.  

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```
