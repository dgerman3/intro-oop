# Lab: Implementing Decorators in C#

## Objectives
- Understand and implement the Decorator design pattern.
- Gain hands-on experience with dependency injection.

##  Exercise (5 points)
### Do the following exercises from your textbook:
- **12.5 (Abstract Methods)**: What are abstract methods? Describe the circumstances in which an abstract method would be appropriate.
- **12.8 (Abstract Classes vs. Interfaces)**: Compare and contrast abstract classes and interfaces. Why would you use an abstract class? Why would you use an interface?

## Coding Exercise (5 points)

### Overview
In this part of the lab, you'll be working on adding decorators to a basic `Smartphone` application. You will be given the starter code, which includes basic implementations for `Camera` and `Battery` classes along with dependency injection in the `Main` method. Your task is to implement at least two decorators.

### Decorator Options
You can choose from the following list or come up with your own ideas for the decorator.

#### For Camera:
- **ImageStabilization**: To ensure that the photo is not blurry.
- **AutoFocus**: To automatically focus before capturing.
- **FaceRecognition**: To identify if a face is present in the shot.
- **Timestamp**: To add a timestamp on the photo after capture.

#### For Battery:
- **BatterySaver**: To reduce charge consumption during charging.
- **QuickCharge**: To charge faster if the condition allows.
- **OverheatProtection**: To halt charging if overheating is detected.
- **ChargeNotification**: To notify when the battery reaches certain levels (e.g., 50%, 80%).

### Requirements
- Implement at least two decorators. You can mix and match or use nested decorators.
- Update the `Main` method for dependency injection setup.

### Tips
- You don't have to update any existing classes except for the low-level dependency injection setup in the `Main` method.
- Simple console output for the decorator's function will suffice as the goal is to understand and implement the Decorator pattern.

## Submission
Please submit your code along with answers to the exercises in the format specified by your instructor.
