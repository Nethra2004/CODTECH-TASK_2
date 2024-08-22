# Building a Serverless Application with AWS Lambda

**NAME:** Nethra V  
**COMPANY:** CodTech IT Solutions  
**INTERN ID:** CT08DS5285  
**DOMAIN:** Cloud Computing  
**BATCH DURATION:** 23 July to 23 August 2024  
**MENTOR:** Muzammil Ahmed  

## Project Description

This project involves deploying a serverless web application using AWS Lambda and API Gateway. The application code is written in Python, tested, and then deployed. API Gateway is configured to trigger the Lambda function, making the web application accessible via a URL.

## Technologies Involved

- **AWS Lambda:** A serverless compute service that allows you to run code without provisioning or managing servers.
- **API Gateway:** A managed service that allows developers to create, publish, maintain, monitor, and secure APIs at any scale.
- **Python:** The programming language used to write the Lambda function.

## Detailed Procedure

### **Creating an AWS Lambda Function**

1. **Navigate to the AWS Lambda Console:**
   - Log in to your AWS Management Console.
   - Search for and select "Lambda" from the AWS services.

2. **Create a New Function:**
   - Click on "Create function."
   - Choose "Author from scratch."
   - Provide a function name.
   - Select Python 3.12 as the runtime environment.
   - Click "Create function."

### **Writing and Deploying the Lambda Function Code**

1. **Write the Code:**
   - In the function’s code editor, write your Lambda function code in Python. The code should handle HTTP requests and return appropriate responses.
 
2. **Deploy the Code:**
   - Click "Deploy" to save and deploy your code.
   - This makes the function live and ready to be invoked.

### **Testing the Lambda Function Code**

1. **Create a Test Event:**
   - In the Lambda console, click on "Test."
   - Configure a new test event, simulating an HTTP request. You can use a sample event template provided by AWS.
   - Save the event with a name.

2. **Run the Test:**
   - Click "Test" to invoke your Lambda function with the test event.
   - Verify the output logs to ensure the function executed successfully and returned the expected response.

### **Setting Up API Gateway Trigger**

1. **Add a Trigger:**
   - Scroll down to the "Function overview" section of the Lambda function console.
   - Click on "Add trigger."
   - Choose "API Gateway" as the trigger type.
   - For "API," select "Create an API."
   - Choose "HTTP API" for a simpler setup.
   - Configure the API with any necessary settings and click "Add."

2. **Deploy the API:**
   - API Gateway will be automatically configured as a trigger for your Lambda function.
   - Once configured, API Gateway provides a public URL that you can use to access your web application.

### **Deploying the Web Application**

1. **Access the API Gateway URL:**

   - After setting up the trigger, API Gateway will generate a public endpoint URL.
   - This URL serves as the web address for your serverless web application.

2. **Testing the Web Application:**

   - Open the API Gateway URL in a web browser.
   - The web application should load, displaying the HTML content served by your Lambda function.

3. **Verify Functionality:**

   - Test the web application by sending HTTP requests (e.g., using a browser, Postman, or CURL).
   - Ensure that the responses are correct and that the Lambda function is triggered appropriately.

 The application is now live and can be accessed via the provided API Gateway URL.
