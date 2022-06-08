# Bug Fixing in Python

Buxing is a concept. Language is the execution.

### Why use Python
- Easy to code: Python is very easy to learn the language as compared to other languages
- Free and open source: it means Python source code is freely available to the public for download
- Object-oriented language
- Python is portable language: Python code for windows can be run on other platforms such as Linux, Unix, and Mac
- Interpreted Language: Python code is executed line by line at a time, there is no need to compile python code
- Dynamically typed language: that means the type for a variable is decided at run time not in advance, so we don't need to specify the type of variable

### Function
A resusable piece of code that completes a specific task
- You can recognise a function as they are a word followed by round brackets (). e.g. print()
- The print() function is used to output a message to the programmer
- You can change the data given to the function to change the output

![image](https://user-images.githubusercontent.com/60888123/172621273-be3b5aba-934f-481b-8743-ddd887172135.png)

### Variables
A reusable label for a data value in Python
- Creating (assigning) a variable has three parts:
1. The variable's name
2. An equals sign =
3. The data value it references

Example: username = 'Jenny_1995', age = 23

Values and variables are interchangeable.
A variable can be put anywhere that a data value can be used.
Example: print('spaghett')
or 
food = 'spaghetti'
print(food)

### Manual Approach
Being human means we can more intuitively find errors developers have made, as well as be able to fix it and ensure the fix is working. The manual approach to bugfixing is exactly that: finding issues, fixing it and testing.

![image](https://user-images.githubusercontent.com/60888123/172622360-3a82a84f-5cb2-4e46-ba88-4aebf3897af9.png)

![image](https://user-images.githubusercontent.com/60888123/172622554-1141cf42-0b96-4687-921d-6aaea7cef8b1.png)

![image](https://user-images.githubusercontent.com/60888123/172622658-f3fbaf13-d59a-4384-9816-4cdfada8c209.png)

![image](https://user-images.githubusercontent.com/60888123/172622843-84121e16-b9e5-4803-97b9-773c53ce8307.png)

![image](https://user-images.githubusercontent.com/60888123/172623117-d0c1616a-1810-4817-afed-c457163eade8.png)

![image](https://user-images.githubusercontent.com/60888123/172623844-0c018aba-0c38-4142-994a-9d8ace39a4bc.png)

![image](https://user-images.githubusercontent.com/60888123/172627562-5e18f32e-a18a-4aad-b80b-f833aa6245ea.png)

### Automated Approach
Simply put...smarter testing
Testing makes the end-product as bug-free as possible, and by testing code using an automated process you will find bugs that crop up in further code development.

![image](https://user-images.githubusercontent.com/60888123/172627854-d5492c38-5cf8-4725-828e-d993af87492a.png)

![image](https://user-images.githubusercontent.com/60888123/172628157-311da2f0-9824-44c0-a693-bc6c44935b86.png)

### Bugfixing in Python Summary
- Bugfixing is a concept, language is the execution - in this course we will be using Python
- The manual approach to bugfixing is how we would do the whole process as developers, finding by debugging, fixing it and then using manual test methods
- A handy debug tool in PyCharm is the pdb (python debugger), where you can step through the code to assess when the bug occurs
- Another debug tool are exceptions, which are errors thrown by Python
- Errors thrown in PyCharm give 3 handy things to the user
  - The line where the error occurred
  - The type of error
  - A descriptor
- After figuring out the issue, the fix is in reach- research or use past experience
- Once you've done a fix, test!
- Automated testing is a more efficient method of checking to see if your code does what you expect
- Can run it as part of a regression pipeline
- Unit tests are the developers tests, and test the functionality of a newly developed piece of work

