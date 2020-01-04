# Braddell Carpark Counter
## Introduction
### Contextual problem
As Braddell View's 10B block is on a hill, there are limited parking lots available.
Once it is full, cars will have to drive to multistory carpark, which is further from the block, to park their cars.
When one (who stays in Block 10B) is driving back, he will have to make a decision if he would like to
* drive to the block's carpark where there are limited lots, rewarding him with a nearby parking space if there are lots, and wasting his time if there are no lots
* drive straight to the multistory carpark

This decision is currently based on the rough intuition of people's schedules.
For instance, in the late evening, people have already driven back to work and thus, no lots are available.
Can we better this decision making process?


### Proposed solution
If we could study the number of cars in the carpark throughout the day, and model it as a probabilistic distribution, we can find the expected payoff of finding a parking lot in the as a function of time.

## Part 1 - Data Engineering
Using Python's OpenCV library and the Raspberry Pi 4 to collect traffic data with the limited view of the carpark entrance.

## Part 2 - Modelling / Interface
Giving users the information


