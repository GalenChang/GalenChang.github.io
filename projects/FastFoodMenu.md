---
layout: project
type: project
image: img/FastFoodMenu/cartoon_burger.jpg
title: "FastFoodMenu.js"
date: 2022-09-15
published: true
labels:
- Javascript
- JSFiddle
summary: "Lets the user order from a generic fast food menu and output a warning if daily fat, sodium, or calories limit is exceeded."
---

<div class="text-center p-4">
  <img width="200px" src="../img/FastFoodMenu/burger.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/FastFoodMenu/fries.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/FastFoodMenu/shakes.jpg" class="img-thumbnail" >
</div>

The goal of the program is to create a generic fast food menu and let the user add food items to their order while keeping track of the order's total fat, sodium, and calorie count.  If any of these amount exceeds the recommended daily intake, then the program would output a warning.  This was done by making the menu a series of objects within objects.  The menu itself is an object, whose keys were food items and values were another object.  These objects are the fat, sodium, and calories of the food items paired with their respective values.  When the user adds an item to their order, it adds the fat, sodium, and calories of the food item to the current order total.  Simple comparisons were made with the daily recommended intake, and warnings produced if current total exceeds the daily recommended intake.

The user order is hardcoded into the program, but is easily changeable.  At the bottom of the code, there is a small section that looks like this:

```cpp
const userOrder = new fastFoodMenu(fastFoodItems);
userOrder.add("<item 1>");
userOrder.add("<item 2>");
userOrder.add("<item 3>");
userOrder.add("<item 4>");
```

By modifying the <item #>, the user can tailor their order to their needs.

We worked in groups of two.  Constant communication between my partner and I allowed us to develop the code simultaneously while allowing for discussions as to the best methods to accomplish the requirements.  After some work, we managed to get the program to work correctly, but there are several aspects that could be improved, such as being able to take user input instead of the user having to manually edit their order in the code.

This project was done as a "Workout of the Day" in ICS 314 (Software Engineering 1) at the University of Hawaii at Manoa.  [You can read the full details of the assignment here](https://courses.ics.hawaii.edu/ics314f22/morea/javascript-2/inclass-bk-menu.html).

A link to the [JSFiddle can be found here](https://jsfiddle.net/galenc12/5ksjvyLz/11/).
Alternatively, the code can be found at [this github repository](https://github.com/GalenChang/FastFoodMenu).
