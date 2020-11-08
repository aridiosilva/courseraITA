# Refactoring - Improving the Design of Existing Code

## What is Refactoring?

- "Is a processo of improving the design of existing code (without changing its bhavior)" (Martin Fowler 2003 - Creator of Refactoring);

- if we can idenfity design problems in the code an safe transformations, then we can improve our code a little bit more at time;
- One of the defining aspects of Refactoring is the focus on safe transformations;
- Refactoring is a step-by-step process and the steps are smaller than people typically espect. Most refactorings tend to take a minute to an hour to apply. The average is probably five to ten minutes, the steps are even smaller. Refactoring works in tiny steps;
- Refactoring has the goal of "improve the design of existing code";

## What is not Refactoring?

- Refactoring is not the change to add new features into the code;
- While Refactoring can be part of the process used to create new code, it is not the part that add new features to the code;
- TDD which consists of Test-First Programming technique, where each TDD Cycle is: first you create a test with the new feature´s interface that fails; second you create the code to introduce the new feature and test it until the test can pass; third you do the refactoring to improve the design of the new code;
- Some peple misunderstand Refactoring to be an re-structuring intended to improve code; 
- What distinguish the definition of Refactoring from this, is the idea of the Refactoring strives to be safe transformations - refactoring can´t leaves the code not working;
- Refacoring is not changes in the code to fix bugs - the processo of fix bugs is inside of TDD Cycle to create a test that will fail showing the bug in the code and then change the code to make the test to pass;
- Some people misuderstand Refactoring to include only Large-Scale Chanves. Most of all refactoring in the TDD Style are small. Ideally, the small refacotring are applied "mercilessly" enough that large refactoring are rarel needed. But, even when Large-Scale Refactorings are needed, the approach is not "no new features for a month while we refacor", but rayther: refactor as you go, and keep the system running all the time.

## Books Recommended to Read Related to Refactoring Technique and Approch and Code Smells

(1) **Book Refactoring - Improving the Design of Existing Code**
    
    - First Edition  by Martin Fowler - 2002 - 337 pages - This book contains examples of code written in Java 
    - Second Edition by Martin Fowler - 2019 - 455 Pages - This book contains examples of code written in Javascript
    
(2) **Book Refactoring-  Ruby Edition by Martin Fowler & Kent Beck · 2009 481 - Pages **

    - Examples of code written in Ruby
    
(3) **Book Refactoring Workbook by William C. Wake  199 pages 2003**

    - Examples of Code written in Java

(4) **Book Clean Code - A Handbook of Agile Software Craftsmanship by Robert C. Martin - 462 pages - 2009**

    - Examples of code written in Java
    
(5) **Book Test-Driven Development By Example by Kent Beck - 137 pages 2002**

    - Examples of code written in Java
    
    
    
    
