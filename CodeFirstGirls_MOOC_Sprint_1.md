### What is a 'bug'?
- A bug in software is a mistake, flaw or oversight in code which causes erroneous or unexpected functionality.
- The definition of a bug is broad meaning that there can be many causes, as well as many different ways in how a bug can manifest.

##### Etymology
The terminology for this is widely linked to Grace Hopper - a prominent female pioneer in the field - who isolated the cause of Harvard's Mark II computer error to a moth trapped in a relay.

### Where are bugs
- 'Everywhere'
- It is almost impossible for a large-scale program to have no bugs
- Bugs can present as:
  - Glitches
  - Missing features
  - Lag/Loading times
  - Miscalaculations
  - Formatting that goes against the product design
  - Payments not being processed
  - and many more!!

![image](https://user-images.githubusercontent.com/60888123/172578629-1ee74aa5-1b9e-4be8-9111-928a2c540c22.png)

### Famous Example 2 - Ariane 5
- Less than 40 seconds into the maiden launch of European Space Agency's Ariane 5 in 1996, it veered off-course, began to disintegrate and self-destructed
- The cause of this was integer overflow
- A redundant maths calculation was brought over from its predecessor, the Ariane 4 which had an immensely high velocity value
- 2,147,483,647 is the maximum positive value that can be stored by 32-bits. Ariane was using a 16-bit register, which is only capable of storing a maximum value of 32,767
- The calculation surpassed the maximum value, and it overflowed leading to a hardware fail
- It's one of the most expensive bugs in history --> $370M lost

![image](https://user-images.githubusercontent.com/60888123/172579585-0cea114d-557b-440c-84f9-17677502a9ce.png)

### The path to bug-fixing
- Before bugs can be fixed, they need to be found
- Bugs are found in multiple ways, in development by a software developer, or business analyst or observing as an end user
- The most common role where bugs are found is as a software tester, where their job is to make the end-product as bug-free as possible

![image](https://user-images.githubusercontent.com/60888123/172580079-bc0ebbc1-7743-4dfc-b2c7-58963e083a6e.png)

### Bug reporting
Bug observed --> Bug reported
Good bug reports need to include the following:
- A summary and description of the bug
- Steps to replicate
  - How/when/where can this bug be observed
- Expected behaviour
  - What is the desired behaviour
- Observed behaviour/error
  - The bug behaviour
- Evidence
  - Media to show bug existence (e.g. screenshots, video)
- Priority
  - How critical would you class this bug

The clearer the bug report, the easier and quicker the handover is so the bug can be fixed.

![image](https://user-images.githubusercontent.com/60888123/172581018-7463cc12-9661-4738-bd38-e797249aad33.png)

### Why do bugs exist?
Some common reasons...
- Ever-changing system requirements
- Poor communication between leadership, analysts and developers
- Programming Errors
- Security Vulnerabilities
- Obsolete Dependencies
- Untested Code

### Bug Classifications
- We have already discussed that bugs can be presented in many different ways
- There are ways to classify bugs together, and work out what type of bug your bug is
- Once yo uknow the bug type, the approach to fixing it becomes clearer
- We're going to go over 5 types of bugs whilst keeping in mind what the definition of a bug is

#### 1. Functional Errors
- This type is quite broad and relates to any bug behaviour where something is observed to not work as expected
- Issues may be diagnosed as functional errors until an investigation process, this is another optional step in the bugfixing process where developers look into an issue further to assess the cause
- Some will then be classified later to another bug

Examples:
Button not responsive
Search doesn't react to the user input
App crashes

#### 2. Syntax Errors
- Errors that occur because you're not correctly following the programming language's syntax
  - Syntax is the expected structure of statements

#### 3. Logic Errors
- Logic or control flow errors, describe a situation where a coding flaw leads to an error in the flow of your program
- Consequences can range from a wrong output to a system crash
- A common example of a logic error is an infinite loop
  - limit_not_reached is always true, so the loop persists
  - system has to be interrupted out of this state otherwise the memory will overflow and it will crash

#### 4. Calculation Errors
- An error caused by a miscalculation when programming
- For example, divide_by_4 function, which returns the number divided by 5 and not 4
- This means that for any important code using that function, there will be a miscalculated value
- This could go on to have big consequences

#### 5. Out of Bounds Errors
- These occur when the user interacts with the program in unexpected ways
- An example of this is where the user is passing in something that is not a number to the divide_by_4 function
- Out of bounds errors can also happen if there is a higher or lower value inputted or used than accounted for by the system limits

### Summary
- A bug is a mistake, flaw or oversight in code which causes erroneous or unexpected functionality
- They are everywhere, and can present themselves in many ways
- Bugs need to be found before they can be fixed, the full bug timeline in industry is:
  - Observed --> Reported --> Prioritised --> Put in Backlog --> Fixed
  - In a single-user project you may deal with bugs as they come, and not have a formal report, prioritisation or backlog in your process
- When fixing a bug, you look at the bug report to understand the issue
- Bug reports need to be clear and have several essential categories:
  - Summary, Expected behaviour, Observed behaviour, Evidence, Steps to replicate
- There are many reasons bugs occur, from changing requirements to developers being human
- You can also classify bugs into types which should help you better approach your bug fix, such as:
  - Functional - Broad category of a bug, where the feature doesn't function as expected. Normally gets reclassified into a more niche category after investigation
  - Syntax - Errors caused by not following the language syntax rules
  - Calculation - Errors caused by function calculations
  - Out of Bounds - Errors caused by unexpected inputs that aren't accounted for
