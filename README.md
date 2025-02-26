# Assignment_2.12

**Given a Lambda function that is triggered upon the creation of files in an S3 bucket, answer the following:**

**1. What is the purpose of the execution role on the Lambda function?**

The execution role is an IAM role that provides the Lambda function with necessary permissions to access AWS resources/services as specified.
   

**2. What is the purpose of the resource-based policy on the Lambda function?**

The resource-based policy allows other AWS resources/services to invoke the Lambda function.
  

**3. If the function is needed to upload a file into an S3 bucket, describe (i.e no need for the actual policies)
  a. What is the needed update on the execution role?**

The execution role must be updated to include the necessary S3 permissions for uploading the file. (eg. s3:PutObject)
  

  **b. What is the new resource-based policy that needs to be added (if any)?**

If the Lambda function is only triggered by the S3 bucket, there is no additional resource-based policy needed for uploading the file to S3.



  

    
