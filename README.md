# AWS SAM Lambda NodeJS S3 Example  
Lambda S3 lab from the Gupta Academy AWS Certified Developer Associate course.  

what this entire project is:

Basically we are creating s3 bucket and we are keeping a track of it. As soon as something get updated in source S3 bucket, we are going to invoke lambda function and it will always create a new s3 bucket with unique name and put the updated file into it. In this Code we are going to put a file into souce bucket and in out we are going to get thumbnail of that file.



## Instructions  
cd aws-sam-lambda-nodejs-s3/code  
npm init  
npm install sharp  
rm -r node_modules  
cd ../  
sam build  
sam deploy --guided


**Note:** A destination bucket will never be created if source bucket won't exist
