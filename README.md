# Sun Position

Sun Position is a small C# .NET Console Project intended for practicing clean object-oriented design and implementation patterns.

This project models a Sun object. This Sun will be able to answer simple questions like:
What position it currently is at based on location and time.

## Goal

The goal is not to build a perfect astronomy engine.

It is to practice having
`clear object behaviour
`readable method names
`small classes
`separating public API from internal implementation
`writing code that another developer can understand quickly


## Intended Usage

External developers using this library will be able to:

var sun = new Sun();

Console.print(sun.Get);