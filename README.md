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

## What are Bad Smells (or Code Smell)?

As stated by Martin Fowler we have the following:

- "A code smell is a surface indication that usually corresponds to a deeper problem in the system. The term was first coined by Kent Beck while helping Martin Fowler when he was writting te first edition of his famou Refactoring book. This definition of smell contains a couple of subtle points. Firstly a smell is by definition something that's quick to spot - or sniffable as I've recently put it. A long method is a good example of this - just looking at the code and my nose twitches if I see more than a dozen lines of java. The second is that smells don't always indicate a problem. Some long methods are just fine. You have to look deeper to see if there is an underlying problem there - smells aren't inherently bad on their own. The smell are often an indicator of a problem rather than the problem themselves";
- "The best smells are something that's easy to spot and most of time lead you to really interesting problems. Data classes (classes with all data and no behavior) are good examples of this. You look at them and ask yourself what behavior should be in this class. Then you start refactoring to move that behavior in there. Often simple questions and initial refactorings can be the vital step in turning anemic objects into something that really has class";
- "One of the nice things about smells is that it's easy for inexperienced people to spot them, even if they don't know enough to evaluate if there's a real problem or to correct them. I've heard of lead developers who will pick a "smell of the week" and ask people to look for the smell and bring it up with the senior members of the team. Doing it one smell at a time is a good way of gradually teaching people on the team to be better programmers".

## Approaches to Do Refactorings

(Image - Diagram about the Types of Refactorings - by Aridio Silva Nov-2020.jpg)

## Books Recommended to Read (Refactoring, Bad Smells, Code Smells and TDD)

       - Refactoring - Improving the Design of Existing Code  by Martin Fowler  (1st Ed 2002 337 pages Code in Java)
       - Refactoring - Improving the Design of Existing Code  by Martin Fowler  (2nd Edition 2019 455 Pages Code in Javascript)
       - Refactoring-  Ruby Edition by Martin Fowler & Kent Beck 481 Pages 2009 (Code in Ruby)
       - Refactoring Workbook by William C. Wake  199 pages 2003 (Code in Java)
       - Clean Code: A Handbook of Agile Software by Robert C. Martin 462 pages 2009 (Code in Ruby)
       - Test-Driven Development By Example by Kent Beck - 137 pages 2002 (Code in Java)
       - Extreme Programming Explored by William C. Wake 159 pages - 2000 (Code in Java)
       - Extreme Programming Installed  by Ron Jeffries and At all - 329 Pages 2000 (Code in Java) 
       - Agile Modeling: Effective Practices for XP & UML by S.Ambler 402 pages 2002
    
    
