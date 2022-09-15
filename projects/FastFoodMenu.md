---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "FastFoodMenu.js"
date: 2022
published: true
labels:
- Javascript
- JSFiddle
  summary: "Lets the user order from a generic fast food menu and output a warning if daily fat, sodium, or calories limit is exceeded."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

FastFoodMenu.js is a very simple Javascript program that has a hardcoded, generic fast food menu that the user can order off of by simply changing a few lines of code at the bottom as seen here:  

```cpp
const myMenu = new fastFoodMenu(fastFoodItems);
myMenu.add("<item 1>");
myMenu.add("<item 2>");
myMenu.add("<item 3>");
myMenu.add("<item 4>");
```

This project was done as a "Workout of the Day" in groups of two in ICS 314 (Software Engineering 1) at the University of Hawaii at Manoa.  [You can read the full details of the assignment here](https://courses.ics.hawaii.edu/ics314f22/morea/javascript-2/inclass-bk-menu.html).

The goal of the program is to create a generic fast food menu and let the user add food items to their order while keeping track of the order's total fat, sodium, and calorie count.  If any of these amount exceeds the recommended daily intake, then the program would output a warning.  This was done by making the menu a series of objects within objects.  Each food item is an object that contains keys fat, sodium, and calories, along with their respective values.  When the user adds an item to their order, it adds the fat, sodium, and calories of the food item to the current order total.   
Micromouse is an event where small robot “mice” solve a 16 x 16 maze.  Events are held worldwide.  The maze is made up of a 16 by 16 gird of cells, each 180 mm square with walls 50 mm high.  The mice are completely autonomous robots that must find their way from a predetermined starting position to the central area of the maze unaided.  The mouse will need to keep track of where it is, discover walls as it explores, map out the maze and detect when it has reached the center.  having reached the center, the mouse will typically perform additional searches of the maze until it has found the most optimal route from the start to the center.  Once the most optimal route has been determined, the mouse will run that route in the shortest possible time.



Some things that can be improved are 

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
