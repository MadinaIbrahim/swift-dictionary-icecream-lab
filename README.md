# Dictionary Basics: Ice Cream

## Objectives

1. Practice creating and using a dictionary.
2. Write methods to interpret the information in a dictionary.

## Introduction

Some of the instructors are planning a summer ice cream party. Joe has collected some information on everyone's favorite ice cream flavors (including his own), but he needs help analyzing the list to know how much of each flavor to buy!

>Susan likes Peanut Butter and Chocolate  
Ian wants Natural Vanilla  
Haaris loves Mexican Chocolate  
Joel only likes Natural Vanilla  
Johann will eat Mexican Chocolate  
Jim never answered so he's getting Natural Vanilla  
Sophie — Cookies 'n Cream duh

## Instructions

Creat a new class called `IceCream`.

Declare and define two methods:

  1. `namesForIceCream()` which takes a `String` argument `iceCream:` and returns an `Array` object.
 
  	* Translate Joe's notes into a `Dictionary` with each name as a key with that person's preferred ice cream flavor as the associated value.
  	* Return an array of the names of everyone who likes the ice cream flavor submitted in the string argument. 
  	
2. `countsOfIceCream()` which takes a `Dictionary` argument `iceCreamByName:` and returns an `Dictionary` object.
	* Returns a dictionary of the number (value) of people who like each flavor of ice cream (key).

 **Hint:** One way is to call `namesForIceCream()` method that you just wrote to get a list of names for each ice cream flavor by calling it on.
 
3. Be sure to run your program constantly and print all asumptions. Where can you call your methods to do this?