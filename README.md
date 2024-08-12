# AI Customer Support

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Deployment](#deployment)
- [Running Locally](#running-locally)
- [License](#license)

## Description

The AI Customer Support Chatbot is a web application designed for the "Headstarter" platform, providing users with real-time assistance through an AI-powered chatbot. Built using Next.js and Anthropic Claude 3 Haiku, the chatbot offers intelligent responses to user inquiries, leveraging AWS Bedrock API for advanced Large Language Model (LLM) processing. The application is deployed on AWS EC2 for robust and scalable performance.

## Features

- **Intelligent Responses:** The chatbot dynamically interacts with users, providing context-aware and detailed answers based on the system prompt and LLM capabilities.
- **System Prompt Control:** A structured system prompt ensures the chatbot adheres to predefined customer support guidelines.
- **AWS Integration:** The application utilizes AWS Bedrock API and is deployed on AWS EC2, offering secure and efficient cloud-based operations.

## Deployment

The application is deployed on AWS EC2, utilizing AWS's reliable infrastructure for hosting and scaling.

To access the live application, please visit: [Headstarter Chatbot](#).

## Running Locally

To run the chatbot locally for development purposes, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone <repository_url>
    ```

2. **Navigate to the project directory:**
    ```bash
    cd <repository_folder>
    ```

3. **Install dependencies:**
    ```bash
    npm install
    ```

4. **Set up environment variables:**
   - Create a `.env` file in the root directory with the following content:
     ```plaintext
     accessKeyIdEnv=<your_aws_access_key_id>
     secretAccessKeyEnv=<your_aws_secret_access_key>
     ```

5. **Run the development server:**
    ```bash
    npm run dev
    ```

   Open your browser and navigate to `http://localhost:3000` to view the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
