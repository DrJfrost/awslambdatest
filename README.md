# awslambdatest

# Tasks API

This project defines a serverless CRUD API for managing tasks using AWS CDK.

## Features
- DynamoDB for data storage.
- Lambda functions for backend logic.
- API Gateway for HTTP endpoints.

## Requirements
- AWS CLI configured with appropriate credentials.
- Node.js and npm installed.
- AWS CDK installed globally (`npm install -g aws-cdk`).

## Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd tasks-api
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Deploy the stack:
   ```bash
   npm run deploy
   ```

4. Test the API using Postman, curl, or similar tools.

## Cleanup
Destroy the stack when no longer needed:
```bash
npm run destroy
```
```
