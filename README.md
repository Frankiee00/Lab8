# Lab8_Starter

## Check your understanding q's (FILL OUT)
1. In your own words: Where would you fit your automated tests in your Bujo project development pipeline? (just write the letter) 1

2. Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

No, because this feature would probably contain multiple smaller features and several other functions to make it all work. This should be tested by seperate and smaller unit tests. Some tests to run would be to check if writing the message updates the data in the message, etc.

3. Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters

Yes, I would, this is because testing the feature can be made into a small function which is what unit tests are best made for. Designing the test would require one to fill a message with some data and checking to see if the max length of the characters is working as it is suppose to. 

4. What do you expect to happen if we run our puppeteer tests with the field “headless” set to true?

5. What would your beforeAll callback look like if you wanted to start from the settings page before every test case?

