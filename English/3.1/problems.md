# In-Class Problems

## ⭐ Task 01
Create an class `Ball` with a function `hop_height` that takes in argument `h` for height from the ball is dropped and return the the height of the k-th hop which decresed exponentially.

## ⭐ Task 02
Create a `Dice` class with an attribute for the number of sides (default 6). Add a `roll` method that returns a random number between 1 and the number of sides. Create two dice and simulate 100 rolls, tracking some interesting statistics such as which die rolled more on average, distribution of numbers rolled overall, etc. (Be creative!)

## ⭐ Task 03
Create a "guess the number" game where the computer picks a random number between 1 and 100. A player has 7 attempts. After each guess, tell them if they're "very cold" (20+ away), "cold" (10-19 away), "warm" (5-9 away), or "hot" (1-4 away). Use while loops and break/continue appropriately. (Tip: Use Python [input()](https://www.w3schools.com/python/python_user_input.asp) to collect input from players.)

## ⭐ Task 04
Create a class `Student` with the parameters `name`, `age`, and `hours_studied`. Every student aged 10-15 would earn 50% on a test if they didn't study at all and their grade would increase by 7% with every incremental hour they spent studying. Every student aged 15-18 would earn 65% on the same test if they didn't study at all but their grade would only increment by 5% with every hour spent studying. Create a function that takes in a list of students and returns the percentage grade average of these students. Show that your function is working on tests.

## ⭐ Task 05
Create an class `Child` that can throw a ball and receive a ball. The class should have a boolean field `tired` that yields `True` if an object of this class has received and thrown a ball at least five times. A child can only throw a ball if they're not tired. Show that three `Child` objects can pass on a ball without the ball getting stuck.

## ⭐ Task 06
Create a `Tournament` class for Rock-Paper-Scissors, which enrolls 6 players with a different strategy each (e.g. always playes paper, always plays rock, plays uniformly random moves, etc.; be creative!). Implement tournament where each player plays 20 games against every other player. Show interesting statistics about the games.

## ⭐ Task 07
Design a class `ParkingLot` that has a specified number of `ParkingSlot` objects. Simulate 10 cars driving in and out of this parking lot over time, with each car staying for a randomly generated number of minutes (within a reasonable range). Each hour (0-1, 1-2, 2-3, etc.) is charged at a different rate. Demonstrate that your class works on tests. (Hint: consider what data structure would be good for holding and keeping track of all your parking slots.)

## ⭐ Task 08
Create an `Elevator` class for a 20-floor building. Track current floor, direction, and a queue of requested floors (i.e. where people called the elevator from). Implement an algorithm to efficiently serve requests (consider moving in one direction before reversing). Demonstrate that your algorithm works as intended using tests.

## ⭐ Task 09
Create a `Auction` class for a silent auction. `Bidder` objects can place bids on `Item` objects. Each item has a starting price and minimum increment. Implement auto-bidding where bidders have max budgets and automatically counter-bid up to their limit. Simulate an auction with 5 items and 8 bidders.

## ⭐ Task 10
Build a `Supermarket` class with a set number of checkout lanes. Create a `Customer` class with a randomly generated number of items (1-30), where each item takes 2 seconds to scan. Implement a queue system where customers get assigned to the shortest queue. Simulate 100 customers checking out and compare average wait times for different numbers of lanes.