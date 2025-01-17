# Smart Photo Album: AI-Powered Image Search

## Overview

Smart Photo Album is a cutting-edge web application that leverages AWS services to create an intelligent photo storage and retrieval system. Using natural language processing capabilities, users can effortlessly search through their photo collection using simple text queries.

## 🚀 Key Features

- Natural Language Search: Find photos using conversational queries.
- AI-Powered Image Recognition: Automatic labeling of objects, scenes, and activities in photos
- Custom Labeling: Add personalized tags to enhance searchability
- Scalable Cloud Architecture: Built on robust AWS services for reliability and performance

## 🛠️ Technology Stack

- Frontend: HTML, CSS, JavaScript
- Backend: AWS Lambda (Python)
- Storage: Amazon S3
- Search: Amazon Elasticsearch
- Image Analysis: Amazon Rekognition
- Natural Language Processing: Amazon Lex
- API Layer: Amazon API Gateway
- Continuous Deployment: AWS CodePipeline
- Infrastructure as Code: AWS CloudFormation

## 🔧 Setup and Deployment

1. Clone the repository
2. Deploy the CloudFormation template (template.yml)
3. Set up CodePipeline for continuous deployment
4. Configure the frontend S3 bucket for static website hosting

## 🔍 How It Works

1. Users upload photos to the S3 bucket
2. Lambda function triggers image analysis with Rekognition
3. Image metadata and labels are indexed in Elasticsearch
4. Users enter natural language queries in the frontend
5. Lex bot interprets the query and triggers the search Lambda
6. Search results are fetched from Elasticsearch and displayed[1]

## 📜 License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

This project was developed as part of the Cloud Computing course at New York University, Fall 2024.
