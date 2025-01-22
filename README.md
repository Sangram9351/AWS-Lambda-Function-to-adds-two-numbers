# AWS-Lambda-Function-to-adds-two-numbers

**Instructions to Run the Project**

1. Create a Lambda Function
Go to the AWS Management Console for Lambda.
Click Create function.
Choose Author from scratch.
Enter a function name (e.g., AddTwoNumbers).
Select Python 3.x as the runtime.
Choose the execution role you've created.

2. Upload the Code
In the Lambda function's dashboard, scroll down to the "Function code" section.
Replace the default code with the provided code or upload a .zip file containing it.

3. Set Test Event
Click on Test at the top of the Lambda function dashboard.
Create a new test event with the following JSON structure:
     {
           "num1": 5,
           "num2": 7
     }
Save the test event.

4. Run the Lambda Function
Click Test to invoke the function.
You should see a response similar to:
        {
             "statusCode": 200,
              "body": "{\"result\": 12}"
        }


