---
layout: essay
type: essay
title: "Final Project Idea"
# All dates must be YYYY-MM-DD format!
date: 2022-11-01
published: true
labels:
- Software Engineering
- Meteor
---

By Galen Chang

# Food Truck Review

## Overview
<p><i><b>Problem:</b></i> Food truck prices are often more expensive for less food compared to other dining options near UH.  With the limited time students have to grab food between classes and their limited budget, many students go for the well known and trusted food options instead of risking it on the food trucks.  The lineup is also constantly changing, and theres no centralized place to quickly lookup reviews.</p>
<p><i><b>Solution:</b></i> Create an food truck review app where users can quickly find and post reviews for the food trucks themselves, as well as the dishes they offer.</p>

## Approach
Users do not need to log in to the app to see food truck info and reviews.

If users choose to make an account, they will be able to post reviews for the food truck itself or individual items.  Users will also be able to see their reviews and edit/delete them.

Admins can do all of the above, as well as reset passwords, ban users, remove/edit reviews.


## Mockup Page Ideas
<ul>
    <li>Navbar</li>
    <ul>
        <li>links to Home, Food Trucks, and Login/Sign up</li>
        <li>When user logs in, Add Review and Edit Review links available</li>
        <li>When admin logs in, Site Administration link is available</li>
    </ul>
</ul>
<ul>
    <li>Home/Landing page</li>
    <ul><li>Cards of the food trucks with brief description of foods offered</li></ul>
</ul>
<ul>
    <li>Food Trucks</li>
    <ul>
        <li>More detailed information about the trucks</li>
        <li>Menu</li>
        <li>When they are usually at UH</li>
        <li>Link to reviews</li>
    </ul>
</ul>
<ul><li>Login/Sign up</li></ul>
<ul>
    <li>Add Review</li>
    <ul><li>Add review to a food truck and/or a specific dish</li></ul>
</ul>
<ul>
    <li>Edit Review</li>
    <ul><li>Displays all the users reviews and lets them edit/remove them</li></ul>
</ul>
<ul>
    <li>Site Administration</li>
    <ul><li>User management (password reset, ban users)</li></ul>
    <ul><li>Remove/edit reviews</li></ul>
</ul>

## Use Case Ideas
<li>
    Visitor can browse the full site, but can't post reviews.
</li>
<li>
    If user decides to make an account, when logging in, takes them right back to the home page, which has cards that have a picture of the truck and brief description of the foods they offer.  Users can also add, edit, and remove their reviews.
</li>
<li>
    Visitors/users can click the cards, which takes them to the Food Trucks page and to the food truck's section, which has much more info like a menu and a link to reviews for the truck itself and for individual dishes.
</li>
<li>
    Admins have all of the user functionality, as well as the ability to conduct user management (password reset) and edit/delete inappropriate reviews.
</li>

## Beyond the Basics
<li>
    Image upload
</li>
<li>
    Contact system between users and admins (suggestions, new food truck, account modification requests)
</li>
<li>
    Review sorting system (by date, number of reviews, highest to lowest reviews, etc.)
</li>