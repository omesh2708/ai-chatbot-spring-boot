
# AI Chatbot using Java Spring Boot and Ollama

## About the Project

This project is an AI-powered chatbot developed using
Java, Spring Boot, Spring AI and Ollama.

It integrates a locally running Large Language Model
to generate responses to user questions.

## Technologies Used

- Java 21
- Spring Boot
- Spring AI
- Ollama
- Llama 3.2
- Maven
- REST API

## Architecture

User
  |
Spring Boot REST API
  |
Chat Service
  |
Spring AI ChatClient
  |
Ollama
  |
Llama 3.2

## Features

- Local AI model integration
- AI-generated responses
- REST API-based communication

## How to Run

1. Install Java 21.
2. Install Ollama.
3. Download the model:

   ollama pull llama3.2:3b

4. Start Ollama.
5. Clone this repository.
6. Run the Spring Boot application.

## Author

Omesh Padampalle
