
Bowling Scorecard 
=================

![Game Screenshot](http://imgur.com/jxTjpmA)

The Bowling Scorecard App counts and sums the scores of a bowling game for one player. It is my first app written in Javascript (jQuery) with unit tests in Jasmine.

A bowling game consists of 10 frames in which the player tries to knock down the 10 pins. In every frame the player can roll one or two times. The actual number depends on strikes and spares. The score of a frame is the number of knocked down pins plus bonuses for strikes and spares. After every frame the 10 pins are reset.

What follows is an example of a scorecard.

![Ten Pin Score Example](images/example_ten_pin_scoring.png)

Approach 
--------

This app was built using TDD and adheres to OOP principles. I got stuck on
implementing the quite complex logic of the tenth frame, only to discover that I
had not really understood bowling up till then. After really coming to grips
with the endgame rules, I was able to write appropriate tests and complete the
project.

How to install:
---------------

* Clone the repo
* Open index.html and play
