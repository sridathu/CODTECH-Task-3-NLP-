# CODTECH-Task-3-NLP-
Name: Nandimedala Sri Dathu

Company: CODETECH

ID: CT12AI94

Domain: Artificial Intelligence

Duration: May to July

 Overview of the NLTK Chatbot Project
This project involves creating a simple chatbot using the Natural Language Toolkit (NLTK) library in Python. The chatbot is designed to interact with users by matching their inputs against predefined patterns and responding accordingly. Here are the main components and steps involved:
1. Importing Required Libraries:
     The NLTK library is used, specifically the `Chat` and `reflections` modules.

2. Defining Chat Pairs:
     A list of pairs is defined, where each pair consists of a regular expression (used to match user inputs) and a list of possible responses.

3. Printing Reflections:
     The `reflections` dictionary is printed, which contains common inputoutput word pairs for transforming user inputs to make responses more natural.

4. Custom Reflections:
     A custom reflections dictionary (`my_dummy_reflections`) is created to override or add to the default reflections.

5. Starting Message:
     A welcome message is printed to the user to start the chat.

6. Creating the Chatbot:
     An instance of the `Chat` class is created using the predefined pairs and reflections.

7. Starting the Conversation:
     The `converse()` method is called to start the conversation. The chatbot continues to listen for user input until the user types "quit".

When the chatbot runs, it processes the user's input by matching it against the regular expressions in the pairs list. It responds with one of the predefined responses if a match is found, otherwise, it uses a default response. The `reflections` dictionary helps in transforming certain words in the user's input to make the conversation more natural.

Output:-


![Screenshot 2024-06-27 130056](https://github.com/sridathu/CODTECH-Task-3-NLP-/assets/89682010/5fb9426b-f1bb-4455-8743-1fc7c7fd83d7)


