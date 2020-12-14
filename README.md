# Code Challenge: 


## The Lonliest Character


![](https://raw.githubusercontent.com/twhipple/Code_Challenge_Loneliest_Character/main/Images/lee-scott-_VTgctRg0tA-unsplash.jpg)

*Those who look lonely aren't necessarily the most lonely. Source: Lee Scott, Upsplash.com*


## Coding Challenge Consecutive Repetition

This Repo is about another coding challenge that relates to a finding the lonliest character - meaning the character with the most white splace on either side. I was fairly quickly able to figure out how to get all the white space AFTER each letter, plus keep track of them using a dictionary. But figuring out how to add the white space from the character BEFORE (which is also the white space BEFORE the letter) was much more challenging.

Complete the function which accepts a string and return an array of character(s) that have the most spaces to their right and left.

Notes:

* the string can have leading/trailing spaces - you should not count them
* the strings contain only unique characters from a to z
* the order of characters in the returned array doesn"t matter

![](https://raw.githubusercontent.com/twhipple/Code_Challenge_Loneliest_Character/main/Images/ricardo-gomez-angel-KmKZV8pso-s-unsplash.jpg)

*Looking for the loneliest character I found this lonely seat! Source: Ricardo Gomez Angel, Upsplash.com*


## Examples:

* "a b  c"                        -->  ["b"]
* "a bcs           d k"           -->  ["d"]
* "    a b  sc     p     t   k"   -->  ["p"]
* "a  b  c  de"                   -->  ["b", "c"]
* "     a  b  c de        "       -->  ["b"]
* "abc"                           -->  ["a", "b", "c"]


## Additionally

This seeemed like a pretty straight forward solution to me. There was something about the output that was troubling me - and ultimately took me down many a wrong path. Ultimately, I just needed to set ups some variables and iterate through the string in order to solve it. The last two examples also took some additional work, but not near as much as getting started!

This kata was written by: aplefull

Thank you to Codewars for helping me practice my Python skills.


