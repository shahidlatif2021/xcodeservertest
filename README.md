![](https://argaamplus.s3.amazonaws.com/159afd60-8669-4140-aa9e-fe46791f515d.png)

## Native Apps QA - Code Challenge
The main objective of this assignment is measuring test engineering skills. 

## Requirements and Output

### Main Test Scenario:

1- Checkout code from https://github.com/shahidlatif2021/Splito and start implement following scenarios. create a test plan in iOS testing framework and add bill tip value. This value will be configurable. from test plan. You need to use this value from test plan and select this value while enetring the bill

2- Verify following scenarios when application first time install.
- Verify that user cannot enter bill more than 10000.
- Verify that in "View Bill History" Screen there is no record.
- Veirfy that in "View Bill History" Screen that total number of people is 0 by default.
- Verify that in "View Bill History" screen that total bill is 0 by default..

3- Create random number of people and bill amount for 10 records. i.e [[4, 1000], [2, 500], .......] where 4 is number of people and 1000 is bill in this example

4- Add bills created in Step 3 in the application in same order and verify that in it is showing in same order as entered in "View Bill History screen".

5- Open "View Bills History" screen that correct count of Total People and Total Bill is shown by reading the values in this screen. Please see following screenshot.

<img width="405" alt="Screen Shot 2022-06-22 at 4 53 46 PM" src="https://user-images.githubusercontent.com/94293020/175033925-b0bd7b8c-b165-4a83-97b6-a146b9ac5a00.png">

You need to read each record data and count total number of people and total bill.


## Conditions:
- iOS Native App
- Code challenge to be done using Swift
- For automated tests, assertions are the key. We want you to explore the application and add the assertions that you think are important.
- Follow best practices for coding & automation (OOP, POM, reusable, clean, documented code).
- Start Appium server Programatically
- Test Report for the Automation (Optional)
- Minimum Xcode version is 13.2.1


## What we are looking for:
A code we can Trust!

This code is meant for testing, and passed execution does not mean working application; maybe testing code needs to be tested in the first place.

## Important points related to Delivery:
- Code challenge should be delivered as a link to a public git repository (github.com is preferred). 
- Implementations focusing on **quality over feature completeness** will be highly appreciated.  Don’t feel compelled to implement everything, while compromising on code quality.
- Follow All the Best Practices for Implementing a Quality Automation Framework.
- Even if you are not able to complete the challenge, please do submit it anyways.
- Make sure you are able to run the tests successfully
- Please avoid any ToDo's in the code.


