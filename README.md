# WebApp-Hosting-on-AWS 🚀☁️

![d4747cb7dcbecb5223b83355ea97a3be-removebg-preview](https://github.com/WaseemCloud/Tic-Tac-Toe-AI-Game-on-AWS-Management-Console-/assets/157589909/6c41585d-d5de-467c-835c-da0cbfe15838)


The aim of this project is to demonstrate how to utilize different AWS services to host a web application. A full step-by-step tutorial has been recorded and uploaded to my Youtube channel:

👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇👇

https://www.youtube.com/watch?v=50swNYkvo3A&t=273s

--------------------------------------------------
# AWS Services:
--------------------------------------------------
In this tutorial, I will be using the following AWS services:
- AWS Amplify
- AWS API Gateway
- AWS Lambda Function
- DynamoDB

--------------------------------------------------
# AWS Architecture:
--------------------------------------------------

![Archeticture](https://github.com/WaseemCloud/WebApp-Hosting-on-AWS/assets/157589909/97eadf66-4172-43cf-9d56-4c251f6089f9)

--------------------------------------------------
# Description:
--------------------------------------------------
We will be hosting our calculator web app (front-end) on AWS Amplify. Lambda function will act as our back-end and will be the brain of our application, where all the calculations are performed. Also, Lambda function will store the results in a database, where we will use DynamoDB in this case. In order to invoke our lambda function, we will need to use API Gateway to be the link between our front-end and back-end. In other words, as soon as we click on "calculate" button in our calculator, an API call "POST request" will be made to invoke our lambda function and it will also pass the mathematical operation parameters that need to be calculated.

When Lambda function receives those parameters, it executes the mathematical operations and does 2 actions:

a) Return the result to our front-end, where the result will be displayed on the calculator's screen.

b) It will store in DynamoDB the numbers, the expression (mathmatical operation), result, and the timestamp where this calculation took place.

--------------------------------------------------
# Repository Structure:
--------------------------------------------------
In the repository, you can find the following files:
- .py file: which needs to be configured in lambda function.
- .txt file: This will contain a JSON IAM policy to allow Lambda function to access the DynamoDB.
- .html file: This is our front-end web page which has some styling and javascript to handle API calls and displaying the operations on the calculator's screen.


# Enjoy ... 😉

