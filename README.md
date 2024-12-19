# RASA-CHATBOT
A conversational AI chatbot developed with the Rasa framework. It uses natural language processing for understanding user queries and provides relevant responses.

Features
Natural Language Understanding: Uses Rasa NLU to parse user inputs.
Custom Actions: Implements custom actions to perform various tasks.
Form Handling: Manages forms to collect user information.
Fallback Mechanism: Handles unrecognized inputs gracefully.

Technologies Used:
Rasa Framework: For building conversational agents.
Python: Core programming language for developing custom actions and logic.
HTML/CSS/JavaScript: For web development tasks.
Natural Language Processing (NLP): For understanding and generating responses.

Project Structure
data/nlu.yml: Training data for NLU.
data/stories.yml: Training data for dialogues.
domain.yml: Defines intents, entities, slots, and responses.
actions.py: Custom actions code.
config.yml: Configuration for NLU and Core pipelines.
credentials.yml: Credentials for connecting to external services.
endpoints.yml: Endpoint configurations for custom actions and tracker store.

Usage Scenarios:
Inquiry Handling: Responding to questions about product and services.
Information Provision: Offering predefined information and answers to common questions.

Customization
You can customize the chatbot by modifying the training data, domain, and custom actions. Refer to the Rasa documentation for more details.
