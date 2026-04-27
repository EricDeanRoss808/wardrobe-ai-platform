# Wardrobe AI Platform

## Overview

Wardrobe AI Platform is an AI-powered wardrobe management application originally developed during an AWS hackathon. The app allows users to upload clothing images, store them in a digital wardrobe, and receive AI-generated outfit recommendations.

This repository represents my personal portfolio version of the project, focused on backend architecture, AWS integration, and system design.

## My Role

I focused on backend infrastructure and cloud integration, using AI-assisted development tools to support implementation and debugging.

My contributions involved working with and connecting core AWS services, including:

- AWS S3 for storing user-uploaded clothing images
- AWS DynamoDB for storing structured wardrobe data and AI-generated metadata
- AWS Lambda for backend processing
- API Gateway for handling frontend-backend communication
- AWS Amplify for deployment and integration

AI tools were used to assist with generating code, troubleshooting issues, and understanding how AWS services interact. I verified, adapted, and integrated this code to ensure the system worked cohesively.

## Tech Stack

- React
- AWS Amplify
- AWS Cognito
- AWS S3
- AWS DynamoDB
- AWS Lambda
- API Gateway
- AWS Rekognition
- OpenAI API

## Key Features

- User authentication using AWS Cognito
- Image upload and storage with AWS S3
- Digital wardrobe metadata stored in DynamoDB
- Serverless backend using AWS Lambda
- API communication via API Gateway
- Clothing detection using AWS Rekognition
- AI-generated outfit recommendations using OpenAI APIs

## Architecture Overview

The application follows a serverless architecture:

1. Users interact with the React frontend.
2. Requests are sent through API Gateway.
3. AWS Lambda functions process backend logic.
4. User-uploaded images are stored in AWS S3.
5. Structured wardrobe data and AI-generated outputs are stored in DynamoDB.
6. AWS Rekognition can be used to analyze clothing images.
7. OpenAI APIs are used for generating outfit recommendations.

AWS Amplify is used to deploy the application and connect the frontend to AWS services.

## Deployment Note

This project was originally deployed using AWS services during a hackathon environment.

The cloud resources are not currently active due to limited AWS access after the event. This repository is maintained as a portfolio project to demonstrate system design, architecture, and AWS integration.

The project can be redeployed by reconfiguring AWS services and environment variables.

## Personal Version Note

This project was originally developed as part of a team during an AWS hackathon.

This repository represents my personal version for portfolio use, highlighting my contributions to backend infrastructure, cloud integration, and system design.

## Project Links

- Original Repository: [Add team repo link]
- Demo Video: [Add link if available]
- Devpost: [Add link if available]
