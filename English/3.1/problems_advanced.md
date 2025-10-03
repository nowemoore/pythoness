# Advanced Problems

## ⭐ Task 01
Create a `Projectile` class with initial velocity and angle. Implement methods `get_position(time)` that returns a tuple of `x` and `y` coordinates at time `t`. Them implement the `get_max_height()`, `get_range()`, and `time_to_ground()` methods. Use physics equations to make this work.

## ⭐ Task 02
Create `Card` and `Deck` classes. `Card` has suit, rank, and value. `Deck` has 52 cards. Implement Deck methods `shuffle()`, `deal(n)`, `draw()`, `cards_remaining()`, `has_card()` and `sort_by_value()`. Create a simple game: deal 5 cards to 3 players, determine who has the highest total value.

## ⭐ Task 03
Create a program that simulates a simple traffic light system. The light cycles through green (30 seconds), yellow (5 seconds), and red (25 seconds). Given a time in seconds since the light turned green, determine what color the light currently shows. Use if/elif/else statements and handle multiple complete cycles. (Use Python's [time](https://docs.python.org/3/library/time.html) library to keep track of time.)

## ⭐ Task 04
Create a `Maze` class that can be initialised using a single integer argument `n` and subsequently generates an n*n grid of squares that can be either blocked or free. Then create a function `find_path` that takes in two tuples of x and y coordinates for the start and end point and returns a list of coordinates of squares that form the *shortest* path between the start and end point. (Hint: Add any helper methods such as `move_left`.)

## ⭐ Task 05
Create a virus spread simulation  with a `Person` class having states: healthy, infected, recovered, or vaccinated. If a healthy, vaccinated, and recovered person meets an infected person, they will get infected with a 70%, 20%, and 10% probability respectively. In a population of 100, start with a constant number of infected people and a set number of randomly generated one-on-one meetings every day. Compare virus spread with 0%, 30%, and 60% vaccination rates.
