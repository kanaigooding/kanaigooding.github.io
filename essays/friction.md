---
layout: essay
type: essay
title: Friction     
# All dates must be YYYY-MM-DD format!
date: 2021-04-29
labels:
  - Design Patterns
  - solution
---

### Avoiding friction
Carl von Clausewitz defines friction the disparity between the ideal performance of units, organizations or systems due to the sum of the little things wearing the system down.  A strategic theorists way of rigorizing the saying "everything that can go wrong will go wrong".  And while Clausewitz may have been to the clashing of Napoleonic armies, friction has its place it any large organization or system.  The grinding and scraping of parts, the miscommunications and mistakes.  And to avoid this, modern armies are filled with strict formulas, methods, and documents for everything.  To ensure things are done to standard, all in the name of "greasing the gears" and avoiding the dreaded friction.  These formulas and methods are what Design Patterns are; formalized best practices that a programmer can use to solve common problems.  These Design Patterns grease the gears of software projects everywhere.  They can be simple or complex, but define simple rules that allow programmers to base their programs on everywhere.  

### A frictionless website
First of all, friction like its physics cousion, can never be eliminated.  However, using proper design patterns for a Meteor-React website, friction can be reduced.  Due to the nature of Javascript, and its way of handling class instantiation, design patterns such as prototype design pattern are used almost as a default.  Other design patterns that appear especially in react software, including the ICS 314 Final Project - UH Code Submissions, are Publish-Subscribe and the Observer Pattern which allow for cotinues updates based on changes in other Javascript Objects.  The meteor subscribe and publish methods, trivially, are the perfect example of the Publish-Subscribe Pattern.  This can be seen in the use of profiles and collections, and these design patterns allow for the frictionless updates to profiles and other information stored in the meteor database such as problems and solutions in our website.  How a meteor-react website handles requests is another example of a design pattern.  The Front Controller Design Pattern can be used to handle requests and authentication like in the pages described by login.jsx and regester.jsx in the UH Code Submissions source code.  This design pattern calls to pass of the authentication request to its handler, in this UH Code Submissions it is passed on by router.js.  These and many other design patterns were used in the design of our website.  Their use reduce the understanding needed for other developers and reduce optimization issues or bugs in the code itself, as the best practices have already been formalized into repeatable patterns for engineers everywhere to use.  


#### Publish-Subscribe
```JavaScript
Meteor.publish(Problems.userPublicationName, function () {
  if (this.userId) {
    return Problems.collection.find();
  }
  return this.ready();
});
````
```JavaScript
  ...
  const subscription = Meteor.subscribe(Problems.userPublicationName);
  ...
```
