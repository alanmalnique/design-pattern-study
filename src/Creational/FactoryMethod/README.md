## Factory Method
Factory Method is a creational design pattern that provides an interface for creating objects in a superclass, but allows subclasses to change the type of object that will be created.

## Problem
In a fictitious system, we have the calculation if a bicycle can travel a value of miles traveled. This system began to expand and it was necessary to add support for Electric Scooters, but the code is not ready to calculate the miles driven and needs to be modified to also perform the calculation.

## Resolution
After an analysis, it was decided to refactor this code with the implementation of the Factory Method.