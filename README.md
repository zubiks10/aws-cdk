# aws-cdk
The Cloud Development Kit simplifies the process of defining and managing cloud infrastructure by allowing developers 
to use familiar programming languages and leveraging the power of infrastructure as code principles.


Let's walk through a simple scenario using the Cloud Development Kit (CDK) to create an 
AWS infrastructure. In this scenario, we'll create an 
AWS Lambda function triggered by an S3 bucket event. 
Whenever a new object is uploaded to the S3 bucket, 
the Lambda function will be invoked to process the object.

We'll use TypeScript as the programming language for defining our infrastructure using CDK.
