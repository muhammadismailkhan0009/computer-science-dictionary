# Software Development Terms

## Word: Test Driven Development
### Description:
TDD is the software development approach in which we write the failing test of the action we want to code. Then we write the code of the action that passes the previously written test. Then we again write the failing test, and then code to pass that test. This iteration process continues for whole application development.  
In simple form: write test -> write code to pass the test -> write test -> write code to pass the test ......
#### search keywords: TDD, test, testing
#### relevant words: Unit Testing, Integration Testing, Mock 
#### scope: beginner


## Word: Unit Testing
### Decription:
Unit testing is TDD approach in which single methods/units of code are tested to see if they work, and are providing desired results.  
For example, Let's say your calculator application contains methods such as addition, and multiplication. Here, addition, is independent methods, while multiplication depends upon additoin. You may unit test additon by calling method on two random numbers to check if it is giving correct results.  
Once addition passes your tests, you can then use addition method to write multiplication logic without worrying about whether addition method will give wrong results.  
This way, if some error occurs, you can be sure that the error is not in addition method.
#### search keywords, unit test, tests, test
#### relevant words: Test Driven Development, 
#### scope: beginner


## Word: Job Scheduling
### Description
Job Scheduling is the way of executing actions at specific time, either once or repitively. For example, you can schedule a random number generator to generate random numbers after every 2 hours.
#### search keywords: schedule, schedular
#### relevant words: cron, schedular
#### scope: beginner
