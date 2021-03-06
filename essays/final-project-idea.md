---
layout: essay
type: essay
title: PANDA Coding Website
date: 2021-03-30
labels:
  - Software Engineering
  - Meteor
  - Semantic UI
  - React
---

Group Members: Jess Ocampo, Kana'i Gooding, Kiran Datwani, Makana Lacson-Garrett

## The problem
The Programing and Algorithms (PANDA) SIG of ACM Manoa presents algorithm mock interview problems to its members.  Currently, it does not have an effective method of collecting and storing submissions.  Without a unified database of problems and solutions work is often repeated by the club officers and students will have to use difficult methods of submission such as Google Docs.  Google Docs is missing key features such as consistent indentation, language-based color (for variables, etc), and the ability to compile and test submissions.  

PANDA has been interested in a program such as this for two semesters now.  Its requirements have been brainstormed by current and previous PANDA officers and are listed below.

## The Solution
A comprehensive website that can be used to store problems and solutions submitted by students.  The website should feature professional-looking themes, run at reasonable speeds, and operate without crashes or failures up to a professional standard.  

There should also be a Problems page with a brief overview of the problem, and a tag for its difficulty.  This should list all published problems and should be sortable and searchable to some extent.  For inspiration visit https://leetcode.com/problemset/all/.  

Admins of the website should be able to add new problems, they should be able to write the description, assign a difficulty tag, assign the number of points awarded for solving the problem, several test cases, and provide solutions in Java and Python.  Preferably the problem description can be written in markdown, so the admins can create a detailed description of the problem using markdown features.  

Users should be able to answer questions (requiring a sign-in).  By selecting a problem from the problems page, they should be taken to a page to answer the problem where they can record a solution via a textbox.  The text box should include the necessary features to submit Java or Python Code.  The solution should note the language the submission was in.  For inspiration see https://leetcode.com/problems/symmetric-tree/.  If possible, (if this is reasonable for a student to develop), code can be run in the browser and tested against the solutions submitted by the admin for the before-mentioned test cases.  

Admins should be able to view each problem and see all submitted solutions.  Admins should be able to remove any undesired solution from the database from this page.

## Mockup page ideas
- Problem(s) page (For inspiration visit https://leetcode.com/problemset/all/)
- User profile page (simple options to change name, email and password)
- User solution submit page (For inspiration see https://leetcode.com/problems/symmetric-tree/)
- New Problem Page (admin only)
- Leaderboard (users with most correct solutions)

## Use case ideas
- User goes to landing page (aka. Problem(s) page), uses log-in page, and uses the user profile page and user home page
- Admin goes to landing page, uses log-in page, and sees the new Problem page
- Admin is able to see all problem solutions and submit problems
- User is able to see problems and submit solutions
- All have access to past problems and solutions

## Beyond the basics
- Textbox/format property (depending on programming langauge)
- Compling code in browser
- Test code against submitted code by the admin
