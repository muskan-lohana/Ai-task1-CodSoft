# Ai-task1-CodSoft
# Simple Python Chatbot

This is a simple chatbot created in Python that responds to user inputs based on predefined rules. The chatbot uses if-else statements and pattern matching techniques to identify user queries and provide appropriate responses.

## How it Works

The chatbot operates with a set of predefined rules and responses. When a user enters a message, the chatbot checks for specific keywords in the input and selects a response from the corresponding rule. If the user's input doesn't match any rules, the chatbot provides a default response.

## Predefined Rules

The chatbot currently supports the following rules and responses:
- "hello": Greeting responses.
- "how are you": Responses about the bot's well-being.
- "bye": Farewell responses.
- "name": Responses regarding the bot's name.
- "default": Responses for unrecognized queries.

## Usage

1. Run the Python script in your development environment.
2. The chatbot will greet you and await your input.
3. Type your message, and the chatbot will respond accordingly.
4. Type "bye" to exit the chat.

## Example

```plaintext
Chatbot: Hello! How can I assist you today? (Type 'bye' to exit)
You: How are you?
Chatbot: I'm just a bot, but I'm doing fine. How can I help you?
You: Tell me a joke.
Chatbot: I'm not sure I understand. Can you please rephrase that?
You: Bye
Chatbot: Goodbye!
