# FlashLearn Auth Frontend

FlashLearn Auth Frontend manages authentication and secure session handling for the FlashLearn platform.

It integrates with Amazon Cognito for identity management.

## Features

- User registration
- User login
- JWT token handling
- Session validation
- Logout functionality
- Protected route integration

## Architecture

Built with:

- React
- Amazon Cognito (User Pools)
- AWS Amplify or Cognito SDK
- Webpack Module Federation
- Shared UI library components

This microfrontend provides authentication context across the FlashLearn system.

## AWS Always Free Tier Deployment

Frontend:
- Amazon S3 (static hosting)
- Amazon CloudFront (CDN)

Authentication Backend:
- Amazon Cognito
- API Gateway with Cognito Authorizer
- AWS Lambda (if custom logic required)

CI/CD:
- GitHub Actions automated deployment

## Security Model

- JWT based authentication
- Secure API access via Cognito
- Role based access support
- No custom password storage

## Portfolio Value

Demonstrates:

- Serverless authentication
- Cognito integration
- Secure microfrontend architecture
- Production ready identity system
