# AWS_PowerOfMath

A super simple application, but it ties together all of the component that you would need to build a much larger real world cloud application

Built using: Amplify, Lambda, API Gateway, Dynamo DB and IAM to perform mathematical calculations and store the inside a NoSQL database

![alt aws_services_img](/images/services_used.PNG)


## Architectural Diagram

![alt architectural_diagram](/images/architectural_diagram.PNG)


1. AWS Amplify hosts the frontend
2. AWS API Gateway work as a gateway for our lambda functions
3. Lambda functions provide logic to calculate and store data
4. An IAM role is given to lambda function which allows it to write into DynamoDB
5. Dynamo DB is used to store data