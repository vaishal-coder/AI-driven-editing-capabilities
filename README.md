I Deploy a Serverless Web Application to Edit Images using Amazon Bedrock Complete Step-by-Step Workshop Documentation. This document provides a comprehensive, step-by-step guide to building a fully serverless image editing web application using Amazon Web Services (AWS). The solution integrates secure authentication, scalable backend services, and Generative AI capabilities powered by Amazon Bedrock. In this REPO, I design, deploy, test, and clean up a modern serverless application that enables users to edit images using AI-powered prompts. The application is built entirely using managed AWS services, ensuring high scalability, security, and cost efficiency.

Architecture Overview

•Frontend: AWS Amplify hosting a Single Page Application (HTML, CSS, JavaScript)
•Authentication: Amazon Cognito User Pool for secure user authentication
•API Layer: Amazon API Gateway exposing RESTful endpoints
•Compute: AWS Lambda for backend request processing
•AI Service: Amazon Bedrock with Titan Image Generator G1
•Database: Amazon DynamoDB for logging image generation metadata
Security: AWS IAM roles and policies enforcing least-privilege access 

