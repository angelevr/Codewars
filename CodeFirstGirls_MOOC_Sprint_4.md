# Bug Prevention

![image](https://user-images.githubusercontent.com/60888123/172655097-768363b1-e17e-4d60-926e-9d67fd01be8a.png)

- Why spend all your time bug fixing when you can work to make sure bugs never happen in the first place?
- The essential stage before a bug is observed is in development
- Improving code quality or adopting measures to reduce the impact of bug behaviour can make all the difference
- Examples of prevention methods include:
  - Exception handling
  - Unit tests
  - Code coverage
  - Test driven development

### Exception Handling - Prevention Method
How does it work:
- Exception and Error handling increases the robustness of your code
- It guards against potential failures that would cause your program to exit in an uncontrolled fashion
- Exceptions can either be in-built or custom-made
- Receiving the exception object and performing the necessary actions for dealing with the bug refers to 'handling the exception'
- This would be the analysing and correcting steps in the debugging process

--> When coding, have flows for all inputs regardless of validity.

![image](https://user-images.githubusercontent.com/60888123/172656762-669da79d-6f6a-4129-98fd-36154faf6d40.png)

![image](https://user-images.githubusercontent.com/60888123/172657912-7c20e4cf-768c-4faf-812d-48a36d6f29c0.png)

![image](https://user-images.githubusercontent.com/60888123/172658142-419ed8e8-2918-4f0f-b376-84195a95567f.png)

![image](https://user-images.githubusercontent.com/60888123/172658307-7de169d0-a191-4adb-b0ff-6750e31e805f.png)

![image](https://user-images.githubusercontent.com/60888123/172659801-dd8e1443-738c-41a1-8268-5a5a8e2c09c9.png)

![image](https://user-images.githubusercontent.com/60888123/172660477-be9f12aa-d2e8-4a97-8685-1adcd9cbc5c0.png)

### Conclusion
- With bug prevention, it's not a pick one or the other
- You can integrate many different methods
- The more you use, the lower the likelihood of bugs remaining
  - The better the code

### Summary
- Bug prevention is the concept of reducing the likelihood of bugs getting into production by finding and dealing with them in development
- Examples of bug prevention methods include: Exception Handling, Unit Tests, Code Coverage, and Test Driven Development
- Exception Hanlding is a method that allows for the accommodation of multiple data flows. This means that valid inputs, invalid inputs and erroneous inputs can all be dealt with differently and in a desired way (eliminating unexpected behaviour - a key bug characteristic)
- Unit tests are a way of making sure your functions work as expected, every developer when coding needs to create these to ensure the new code isn't introducing new bugs into the system
- Code coverage is a method strongly linked with tests, as it allows the developer to see how much of the code is covered by tests. In theory, the higher your code coverage - the less bugs you will have
- Test Driven Development is a development practice where you write tests before you implement the code. This is a circular process where the test fails, you write the code, the test passes, you change the test to be more complex and so on. As a result, code should have no unexpected functionality as it is tested at each stage.
- It is not a one and done, you can combine multiple bug prevention methods to reduce your bug likelihood.
