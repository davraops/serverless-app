# Serverless Application

This is a demo serverless application using AWS Lambda, API Gateway, and DynamoDB.

## Prerequisites

1. AWS Account
2. Node.js installed
3. Serverless Framework installed (`npm install -g serverless`)

## Setup

1. Clone the repository
    ```bash
    git clone https://github.com/davraops/serverless-app.git
    cd serverless-app
    ```

2. Install dependencies
    ```bash
    npm install
    ```

3. Deploy the service
    ```bash
    serverless deploy
    ```

4. Test the endpoint
    The deployment output will provide an API endpoint URL. Use this URL to test your Lambda function.

## Additional Commands

- Remove the service
    ```bash
    serverless remove
    ```

## License

This project is licensed under the MIT License.