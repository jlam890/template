---
layout: essay
type: essay
title: "Programming Plagiarism"
date: 2017-12-05
labels:
  - Software Engineering
  - Design Patterns
---

# Design Patterns

Students go to school every day and learn how to solve certain problems. The problem with this is that most of these problems have already been solved by somebody else. What is the point of putting in effort to solving something that has already been resolved. Now you can argue that the process of getting the answer is what matters and the answer is just the end product, and I would actually agree with you, but this is not about the school system, this is about design patterns. Design patterns are commonly occurring problems in software developement that somebody else has already solved and has generously shared to allow other developers the opportunity to skip solving the problem on their own. One example of this is porting in libraries to communicate with lower level hardware in embedded systems. The embedded systems library contains helper functions that somebody else already implemented and wrote to talk with the pin inputs and outputs. Using the library saves a lot of time for the developer and lets them work on other issues in their project. Isn't this some form of plagiarism though?

# Does Plagiarism Exist for Programmers?

To answer the previously presented question simply, no. The people who put out the solutions to these common problems do so willingly with the goal of helping out other programmers. There is no point in reinventing the wheel so why do it? Programmers all know the aches and struggles debugging code that doesn't work and using libraries or design patterns helps alleviate the stress. Developers can focus more of their energy working on other problems that aren't solved yet. There is a downside of using design patterns as users must learn how to work with the code that they haven't seen before. This confusion falls on the original developer to make the design pattern easy to use and implement with existing code. Using open source code in your project is completely fine and open source code helps all developers in their endeavors.

# My Own Experience

One experience with design patterns I had was the previously mentioned one with the design of an embedded system. Developers using the STM32F4 microprocessor from ARM usually use the pinouts and timers on the chip for the same purposes. One example is using a timer in a PWM (pulse width modulation) application. PWM is a square wave that is on for a certain amount of time and then off. This cycle repeats and the duty cycle, or the percentage on, can be changed with the microprocessor. PWM is extremely useful for applications with motors and blinking LED lights. Configuring all the lower level hardware is something that is tedious and confusing because everything works on the lower level and a developer has to deal with address spaces, heaps, and stacks. There is an application called STMCube which is used to generate all the lower level code for developers. This saves projet developers the time it would take to duplicate the same code that everybody else would use for the same applications. Design patterns helped save lots of time and frustration for my team and without it programming would be much harder than it already is.
