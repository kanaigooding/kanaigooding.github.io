---
layout: essay
type: essay
title: Helping the next engineer.  
# All dates must be YYYY-MM-DD format!
date: 2021-02-11
labels:
  - Coding Standards
  - Learning
---


### Code Style can't be ignored
Since the first time I was introduced to software development, I immediately recognized that coding style and formatting plays a key part in what we do as engineers.  Code style can change from language to language or from organization to organization, but no matter what the importance of code style remains.  I realized that having a consistent and clear coding style leads to clear, legible code.  This helps immensely in developing your code, as reading back on your old code because infinitely is easier.  But, even more importantly, it can help the next engineer who needs to update or modify your code.  Without this, code would be much more challenging to update and for projects such as Source (released 2004), an update in 2021 would be impossible without it.  

### I hated Intellij
When learning to get ESLint up and running in Intellij, I had issues with how challenging it is to initially get started in a project.  I felt that there were too many steps to get it set up, too many formatting files, and too many settings to adjust each time one created a project.  To me, code style is something that should be set up once and simply works from thereon.  However, upon more reflection I realized in the real world projects are MUCH larger, and one will not have to set up new projects so often.  I also realized that code styles may not be the same for each project, especially some that were initially developed 10+ years ago.  

### Settling in 
Once I considered that, and let myself sit with the green check mark and ESLint, I found myself fitting nicely into a temp of matching the code style naturally.  "The green checkmark" simply lets me know that I am doing my work correctly as I always strive to produce neat, clean, and legible code whenever I develop.  I always keep in mind the next person reading my code may not be me, and I need to make sure that they can understand it as well.  And as always, clean code is beautiful code...

```JavaScript
function sumFor(list) {
  let sum = 0;
  for (const num of list) {
    sum += num;
  }
  return sum;
}
````
