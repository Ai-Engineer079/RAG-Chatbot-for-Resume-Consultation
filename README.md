
# RAG Chatbot for Resume Consultation

## Overview

The **RAG Chatbot for Resume Consultation** is an AI-powered chatbot built to help users schedule free resume consultations. The bot is integrated with OpenAI's GPT-4 and utilizes the Langchain framework for efficient task automation.

## Workflow Description

- **AI Agent**: The core chatbot agent that communicates with users in a friendly, supportive tone.
- **OpenAI Chat Model**: Uses GPT-4 to engage with users and offer personalized responses for resume consultations.
- **Window Buffer Memory**: Remembers conversation history to make the chatbot experience more personalized.
- **Qdrant Vector Store**: Stores user inputs for future reference and query-based interactions.
- **Embeddings OpenAI**: Provides context-aware recommendations for users based on the conversation history.
- **Manual Trigger**: Allows manual activation of the workflow for testing purposes.

## Features

- **Interactive Chatbot**: Engages with users in a conversational manner, providing resume advice and consultation scheduling.
- **Real-time Scheduling**: Direct integration with scheduling tools to offer real-time appointment availability.
- **Knowledge Store**: Uses vector databases to retrieve user-specific information for tailored responses.
- **Memory**: Retains context from previous interactions to enhance the user experience.

## Usage

1. Start a conversation with the chatbot via LinkedIn or Instagram DMs.
2. Provide a brief summary of your resume and career challenges.
3. The bot will schedule a free consultation based on available slots and send the details to your email.

## Example Flow

- **User**: "I need help improving my resume."
- **Chatbot**: "Sure! Can you share some details about your current resume and what you'd like to improve?"
- **User**: Provides information.
- **Chatbot**: "Great! I’ve scheduled a free consultation for you on [date and time]. Check your email for the invite!"

---
### Placeholder Image

![RAG Chatbot for Resume Consultation Workflow](path/to/your/rag.png)

---


## Installation

1. Clone this repository:

   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

3. Start the n8n server:

   ```bash
   n8n start
   ```

4. Trigger workflows via the n8n UI or via webhook.

---
