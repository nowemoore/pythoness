# In-Class Problems

## ⭐ Task 01
Create an class `ball` with a function `hop_height` that takes in argument `h` for height from the ball is dropped and return the the height of the k-th hop which decresed exponentially.

## ⭐ Task 02
Create an class `child` that can throw a ball and receive a ball. The class should have a boolean field `tired` that yields `True` if an object of this class has received and thrown a ball at least five times. A child can only throw a ball if they're not tired. Show that three `child` objects can pass on a ball without the ball getting stuck.

## ⭐ Task 03
Create a class `student` with the parameters `name`, `age`, and `hours_studied`. Every student aged 10-15 would earn 50% on a test if they didn't study at all and their grade would increase by 7% with every incremental hour they spent studying. Every student aged 15-18 would earn 65% on the same test if they didn't study at all but their grade would only increment by 5% with every hour spent studying. Create a function that takes in a list of students and returns the percentage grade average of these students. Show that your function is working on tests.

## ⭐ Task 04
Create a `Dice` class with an attribute for the number of sides (default 6). Add a `roll` method that returns a random number between 1 and the number of sides. Create two dice and simulate 100 rolls, tracking some interesting statistics such as which die rolled more on average, distribution of numbers rolled overall, etc. (Be creative!)

## ⭐ Task 05
Design a class `ParkingLot` that has a specified number of `ParkingSlot` objects. Simulate 10 cars driving in and out of this parking lot over time, with each car staying for a randomly generated number of minutes (within a reasonable range). Each hour (0-1, 1-2, 2-3, etc.) is charged at a different rate. Demonstrate that your class works on tests. (Hint: consider what data structure would be good for holding and keeping track of all your parking slots.)