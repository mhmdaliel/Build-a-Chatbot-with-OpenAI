# Build-a-Chatbot-with-OpenAI

# Setting Up Your Node.js Project with OpenAI and Express

This guide walks you through the steps to set up a Node.js project using Express and OpenAI, enabling you to interact with the OpenAI API.

## Prerequisites

Before you begin, ensure you have the following installed:

1.  **Node.js:**
    * Download and install Node.js from the official website: [https://nodejs.org/fr](https://nodejs.org/fr)

2.  **Visual Studio Code (VS Code):**
    * Download and install VS Code from the official website.

## Project Setup

Follow these steps to set up your project:

1.  **Open the `software-dev-chatbot` Folder in VS Code:**
    * Open the `software-dev-chatbot` folder in VS Code.

2.  **Open a New Terminal:**
    * In VS Code, open a new terminal (e.g., by going to `Terminal > New Terminal`).

3.  **Install Dependencies:**
    * Run the following command in the terminal to install the necessary packages:
        ```bash
        npm install express openai
        ```

4.  **Install Live Server Extension (VS Code):**
    * In VS Code, go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).
    * Search for "Live Server" and install it.

5.  **Run the Server:**
    * In the terminal, execute the following command to start your server (assuming your server file is named `server.js`):
        ```bash
        node server.js
        ```

6.  **Access Your Application:**
    * Open your web browser and navigate to:
        ```
        http://localhost:3000/
        ```
    * If the application is running on a different port, replace `3000` with the correct port number.

## Using Your Own OpenAI API Key

To use your own OpenAI API key, follow these steps:

1.  **Create an OpenAI Account:**
    * Go to the OpenAI platform and create an account: [https://platform.openai.com/](https://platform.openai.com/)

2.  **Generate an API Key:**
    * Navigate to the "API keys" section and create a new API key.

3.  **Configure Your API Key:**
    * Open the `config.js` file in your project.
    * Replace `YOUR_API_KEY` with your actual OpenAI API key:
        ```javascript
        OpenAIAPIKey: 'YOUR_ACTUAL_API_KEY'
        ```

4.  **API Plan Requirement:**
    * **Note:** You must have an active OpenAI API plan for your API key to work. Ensure you have purchased a plan from OpenAI.
