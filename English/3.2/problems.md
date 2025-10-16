# In-Class Problems

## ⭐ Task 01
Create a base class `Vehicle` with attributes `speed`, `fuel_capacity`, and `fuel_consumption`. Create child classes `Car`, `Motorcycle`, and `Truck` that inherit from `Vehicle`. Each child should have a method `travel_distance(hours)` that calculates how far they can travel.

## ⭐ Task 02
A pet shelter tracks animals with their age, weight, and adoption fee. Dogs have a base fee of $50 plus $10 per year of age. Cats have a base fee of $40 plus $8 per year. Birds have a flat fee of $25. The shelter just received a donation that covers adoption fees for all animals under 2 years old. Build a system that computes hwo much money from the donation will be used if there are currently 5 dogs (ages: 1, 3, 5, 1, 7), 8 cats (ages: 2, 1, 4, 1, 6, 1, 3, 8), and 3 birds (ages: 1, 2, 4).

## ⭐ Task 03
Create a `LaundryItem` class where each item has a color (white, light, or dark) and fabric type (cotton, synthetic, or delicate). Whites must be washed separately, lights and darks can mix if both are non-delicate. Delicates always wash alone. Create a function that takes a list of laundry items and returns the minimum number of loads needed. Generate 30 random laundry items using random.choice() for colors and fabrics, then show how many loads are required and which items go in each load.

## ⭐ Task 04
Create a base class `Shape` with an abstract method `area()`. Subclasses `Circle`, `Rectangle`, and `Triangle` must each implement their own formula for area. Then, write a function `total_area(shapes)` that takes a list of unspecified shape objects and returns the combined area. Show that your method works using unit tests.

## ⭐ Task 05
A zoo has different animals with different feeding schedules. Carnivores eat every 8 hours and consume 5kg of meat per feeding. Herbivores eat every 6 hours and consume 8kg of plants per feeding. Omnivores eat every 7 hours and consume 3kg of meat + 4kg of plants per feeding. The zoo has 3 lions (carnivores), 4 elephants (herbivores), and 2 bears (omnivores). The first time each week carnivores are fed in Monday 7am, herbivores Monday 5am, and omnivores Monday 6.30am. Finally, every group sleeps for eight hours a day, in random intervals of two hours at a time, and cannot be fed when asleep. Print exactly when each animal group was fed. 

<details>
<summary>Tip</summary>
Remember to print when an animal was <em>not</em> fed for some reason (e.g. being asleep) to make sure your function works correctly.
</details>

## ⭐ Task 06
Create a base class `Shape` with attributes for name and the number of sides, and a method `roll_distance()` that takes in the force used to push a given shape and returns how far the shape rolls when pushed. Then create subclasses `Circle`, `Square`, and `Hexagon`, each defining how the number of sides affects rolling, where the distance each shape gets to travel is equal to (force * 10) / number of sides. Write a function `roll_tournament()` that takes in a list of shapes and a singular force used on all shapes, calls each shape’s `roll_distance()` method, and prints which shape rolled the farthest. Demonstrate that your program works with at least three different shapes.

## ⭐ Task 07
Each subclass of `Shape` (`Circle`, `Rectangle`, `Triangle`) implements a method `cast_shadow` that takes in the light angle relative to the ground the shape is placed on and returns the length of the shadow depending on shape geometry. Then write a function that, given a list of shapes and one light angle, returns the longest shadow.

## ⭐ Task 08
Create a base class `Message` with subclasses `TextMessage` (which is a list of string characters), `ImageMessage` (list of RGB tuples), and `VoiceMessage` (list of float frequencies). Each type must know how to compress. Comrpessing means that if two equivalent values are immediately next to each other, the message will only keep one of them (e.g. if a text message consists of characters `h`, `e`, `l`, `l`, and `o`, the compressed text message will consist of `h`,`e`,`l`,`o`). Write a function that takes a list of mixed messages and calculates total storage saved after compression.

## ⭐ Task 09
Create a base class `ElectricDevice` with a method `consume_energy(hours, usage)` that calculates energy used based on how long a device is running for and how much energy it uses per hour. First-generation subclasses `Lights`, `HeatingDevice`, or `ScreenDevice` define the maximum runtime allowed per day for that type. Second-generation subclasses like `LEDLight`, `HalogenLigh`t, `Heater`, `AirConditioner` and `TV` have their own specific power usage per hour and inherit runtime limits from their parent type. Implement a `smarthome` class that takes in a list of multiple devices and computes how much the household will be paying given different day and night electricity rates.

## ⭐ Task 10
Design a base class `TrafficLight` with methods to cycle through states: 'Red', 'Yellow', 'Green'. Implement a subclass `PedestrianCrossingLight` that overrides the state logic; it must only switch from 'Green' to 'Red' after a `pedestrian\_request()` method is called. Consider an interaction of these two objects: if the pedestrian light shines green, then the traffic light must be red and no cars can pass. When the light shines green, a car gets to pass the traffic light every 5 seconds. Implement a function that computes how many cars pass over an hour-long time period where pedestrian requests occur at random times.