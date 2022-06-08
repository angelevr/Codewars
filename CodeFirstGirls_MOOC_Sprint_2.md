# Cause Investigation

- In more cases than not, when a bug is picked up the cause is unknown
- Therefore there needs to be some time investigating the circumstances around the bug so the issue can be isolated
- Once the issue is known, the path to fixing it becomes clearer
- Two common ways of bug investigation are:
  - Troubleshooting
  - Debugging

Backlog --> Investigation --> Fixing --> Bug fixed

### Troubleshooting Vs Debugging
- Troubleshooting and debugging are two concepts programmers need to know and distinguish between
- We must understand the two terms and know how the common traits they share differ
- NOTE: you will spend more time with debugging than with troubleshooting in a day to day work
- HOWEVER: your extended operational duties will cause you to troubleshoot more frequently

### Troubleshooting
- Troubleshooting is a process that helps people identify issues or problems occuring in a system
- Troubleshooting tends to exist at a higher level than debugging and applies to many components of a system
- It's a process of parsing out the items that are causing problems
- This process requires interviewing the end users of the system to find out the steps they took to cause the problems

### Debugging
- Debugging is a subset of troubleshooting
- Debugging implies finding problems as they relate to computer code
- When you are tasked with debugging a module of code, you find what is causeing the problem and then you must fix it (NB: this is an oversimplification)
- There may be several points of failure in the code, and sometimes it's not obvious where the problems are occuring, so we must strive to break down the code into chunks and identify issues

### Golden Rules: When a problem strikes
1. Know and apply debugging techniques
2. Find what has changed
3. Use tools, but don't fully depend on them
4. Give everyone else the benefit of the doubt when dibegging
5. Help others find the problem

### Debugging Techniques: the process of identifying and removing errors form computer hardware or software

### Print Statement
// python: print()
// C#: Console.WriteLine()
// Java: System.out.printIn()

1. Print statements are the fastest, easiest and most direct way to inspect the data values and types of variables
2. Well-placed print statements allow us to track the flow of data through a piece of code and quickly identify the source of the bug
3. The humble print statement is always a first tool we turn to when trying to debug a piece of code

![image](https://user-images.githubusercontent.com/60888123/172596710-852ca74c-093b-4f43-bc98-328daab14685.png)

### Teddy Bear Method / Rubber Duck Debugging
1. Rubber duck debugging originated in a university computer centre where students were required to sit down across from a teddy bear and explain their bugs to it before they could seek help from a live person
2. This method is so effective that it spread quickly throughout the entire software engineering world, and it persists to this day!
3. Nearly anything can be subsituted for the teddy bear: rubber ducks are a popular choice, as are patient non-programmers

![image](https://user-images.githubusercontent.com/60888123/172597466-1b97e362-2e42-41b2-abaf-bd2e9b43a9e0.png)

#### Key steps to troubleshooting
1. Gather information
2. Iterate potential solutions
3. Test your solution

### Reproduce the problem/develop hypothesis (troubleshooting)
1. Try reproducing the same issue in the non-Prod environment (dev/UAT)
2. You may use mock input to simulate the problem
3. Once recreated, then try to identify and fix the root cause

![image](https://user-images.githubusercontent.com/60888123/172598172-cb4ac66b-83dc-4ffb-9721-65d8834d40f2.png)

### But Investigation: Summary
- Investigation is needed when the cause of the bug is not known, in this case there is set time allocated by developers towards investigating and diagnosing the issue
- Once the issue is known, the path to fixing the bug becomes clearer
- There are two main ways this is done: troubleshooting an debugging
- Troubleshooting is a high-level process that helps people identify issues or problems occuring in a system
- Debugging is a subset or troubleshooting and implies finding problems as they relate to computer code
- As a software developer, knowing how to troubleshoot at a high level is helpful, but you will spend more time debugging. Therefore, it's beneficial to learn a few debugging techniques
- Print statements are a good way of observing the current state of the system
- Version control is another technique that ensures code can be rollbacked to a previous codebase version to reverse the bug state
- Linter and IDEs also help out with common issues
- When you troubleshoot, you investigate, find potential issues and very importantly...test

