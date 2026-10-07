# University FAQ Chatbot

A university FAQ chatbot developed for CodeAlpha’s Artificial Intelligence internship.

## Features

- Answer questions about university services
- Send questions using the Send button or Enter key
- Display questions and answers in a chat window
- Clear the conversation

## Technologies

Python, Tkinter, NLTK, and scikit-learn.

## How it works

The chatbot cleans and tokenizes the text, converts questions into TF-IDF vectors, and uses cosine similarity to find the closest FAQ question. It returns the corresponding answer from faqs.json.

## How to run

3. On Windows, double-click START_WINDOWS.bat.
4. Type a question and click Send.

## Example questions

- How can I check my grades?
- I forgot my password.
- How can I pay my tuition fees?
- How do I register for courses?

## Limitations

The FAQs are examples, not official university policies. Questions outside the available topics may receive an unrelated answer.
