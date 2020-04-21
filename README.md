# awslambda-serverless

With the growing popularity of Serverless, I wanted to explore how to to build a (Big) Data platform using Amazon’s serverless services. In this article, we will look into what is a data platform and the potential benefits of building a serverless data platform. We will also look at the architectures of some of the serverless data platforms being used in the industry.

## What is a Data Platform?
![.](https://github.com/Ibrokhimsadikov/awslambda-serverless/blob/master/0_Q9oqDIk0KbvjyGJz_.png)


Serverless architectures benefit from significantly reduced operational costs and complexity and thus it is a good fit for building a data platform. It can reduce the amount of time it takes to spin up a fully functional data platform as compared to the traditional “big-data” platforms. Some of the other benefits of a serverless data platform are:

## Why build a serverless data platform

https://github.com/Ibrokhimsadikov/awslambda-serverless/blob/master/new-01-sqs-dynamodb-1.png
The flexibility of data ingestion and consumption.
Cheap & reliable storage
Ability to support ad-hoc querying of data

AWS Lambda: AWS Lambda lets you run any function without provisioning or managing any servers. These functions can be written in a bunch of different languages such as Python, Go, Java, JavaScript. These Lambda functions can be used to transform your raw data into the desired format. Amazon also handles any potential scaling requirements for the application.

As serverless services become more powerful, we are going to see more and more conventional architectures migrating towards being more serverless. I believe for anybody looking to build a new data platform, starting with serverless might be a great choice.

reference: https://www.learnaws.org/2020/01/07/serverless-data-platform/
