# Exercise report
- Student: Jakub Volák
- DAT250-JPA-example repository: https://github.com/volakjakub/dat250-jpa-example

## Technical issues

I didn't have any technical issues during installation. I had only one issue with project in experiment 1 with Todo model class. My IDE couldn't find the file even it was in right directory. I solved it with deleting the file and creating it again.

## Database inspection

I used built-in function in IDE for connecting to database. I created connection to Apache Derby. In settings, I selected path to DB and filled username and password. Then I was able to look on DB structure and data in DB through my IDE. Screenshot is in this repository.

## Pending issues

I don't know why, but everytime when I run test on my PC I got error on line 44. Here the test tries to get addresses from person and compares size of collection with value 1. Every time the collection is empty, even if I can see data in DB. In GitHub the test passes successfully, so I don't have any idea why the test fails on local machine.