# Wardrobe AI Platform

AI-powered wardrobe management system built on AWS serverless architecture, enabling users to store clothing items and generate AI-based outfit recommendations.

---

## Overview

Wardrobe AI Platform is an AI-powered wardrobe management application originally developed during an AWS hackathon. The platform allows users to upload clothing images, organize them into a digital wardrobe, and receive outfit recommendations generated through AI.

This repository represents my personal portfolio version of the project, with a focus on backend architecture, AWS integration, and system design.

---

## My Role

I focused on backend infrastructure and cloud integration, using AI-assisted development tools to accelerate implementation and debugging.

My contributions centered on integrating core AWS services and enabling data flow across the system:

- Configured AWS S3 for storing user-uploaded clothing images  
- Structured DynamoDB tables for wardrobe data and AI-generated metadata  
- Implemented backend logic using AWS Lambda  
- Connected frontend and backend through API Gateway  
- Used AWS Amplify to support deployment and service integration  

AI tools were used to assist with code generation, debugging, and understanding AWS service interactions. I verified, adapted, and integrated outputs to ensure the system functioned cohesively.

---

## Tech Stack

**Frontend:**  
- React  

**Cloud & Backend:**  
- AWS Amplify  
- AWS Cognito  
- AWS S3  
- AWS DynamoDB  
- AWS Lambda  
- API Gateway  

**AI & Processing:**  
- AWS Rekognition  
- OpenAI API  

---

## Key Features

- Secure user authentication via AWS Cognito  
- Image upload and storage using AWS S3  
- Digital wardrobe management with DynamoDB  
- Serverless backend powered by AWS Lambda  
- RESTful API communication via API Gateway  
- Clothing detection using AWS Rekognition  
- AI-generated outfit recommendations using OpenAI APIs  

---

## Architecture Overview

### Data Flow (Simplified)

Frontend (React) → API Gateway → AWS Lambda → (S3 for image storage, DynamoDB for structured data)

The application follows a serverless architecture:

1. Users interact with the React frontend  
2. Requests are routed through API Gateway  
3. AWS Lambda handles backend processing  
4. Clothing images are stored in AWS S3  
5. Structured wardrobe data and AI outputs are stored in DynamoDB  
6. AWS Rekognition analyzes clothing attributes  
7. OpenAI APIs generate outfit recommendations  

AWS Amplify is used to deploy the frontend and connect it with backend services.

---

## Deployment Note

This project was deployed using AWS services during a hackathon environment.

Cloud resources are not currently active due to limited AWS access after the event. This repository is maintained as a portfolio project to demonstrate system architecture, AWS integration, and backend design.

The project can be redeployed by reconfiguring AWS services and environment variables.

---

## Personal Version Note

Originally developed as part of a team during an AWS hackathon, this repository represents my personal portfolio version of the project.

It highlights my contributions to backend infrastructure, cloud integration, and system-level design.

---

## Project Links

- Original Repository: https://github.com/EricDeanRoss808/wardrobe-app  
- Demo Video: https://youtu.be/pnm0jRh5hFI?si=ZM79SS-bcES7QvNR  
- Devpost: https://devpost.com/software/drip-management  
