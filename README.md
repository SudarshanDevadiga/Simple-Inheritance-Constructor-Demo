# Simple Inheritance Constructor Demo

A C++ program demonstrating basic inheritance and constructor behavior in a vehicle class hierarchy.

## Description

This program shows how constructors work in inheritance by implementing a simple parent-child class relationship between `Vehicle` and `Car` classes. It demonstrates automatic parent constructor calling when a child object is created.

### Key Features
- Basic inheritance implementation
- Constructor demonstration
- Automatic constructor chaining
- Simple class hierarchy

## Class Structure

```cpp
class Vehicle {
public:
    Vehicle(); // Base class constructor
};

class Car : public Vehicle {
    // Inherits from Vehicle
};
