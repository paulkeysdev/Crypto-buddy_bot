# CryptoBuddy: Your Intelligent Cryptocurrency Assistant

Welcome to **CryptoBuddy**, an interactive AI chatbot designed to help you navigate the dynamic world of cryptocurrencies. CryptoBuddy provides insights into profitability and sustainability, offering investment advice based on key metrics like price trends, market capitalization, energy efficiency, and project viability.

---

## Features

* **Intelligent Conversational AI**: Engages in natural language conversations, handling greetings, acknowledgements, and general queries.
* **Cryptocurrency Data Analysis**: Provides insights into various cryptocurrencies from a sample dataset.
* **Profitability Recommendations**: Identifies cryptocurrencies with "rising" price trends and "high" market capitalization.
* **Sustainability Recommendations**: Suggests eco-friendly cryptocurrencies with "low" or "very low" energy consumption and high sustainability scores.
* **Real-time Data Integration (Conceptual)**: Includes a framework to integrate with the CoinGecko API for real-time price and market cap updates (requires API calls and rate limit awareness).
* **Pre-defined Responses**: Handles a variety of specific questions and phrases, from common chatbot queries to fun interactions and even unhappy sentiments.
* **Disclaimer**: Reminds users of the inherent risks in cryptocurrency investments.

---

## How to Get Started

To run CryptoBuddy, follow these simple steps:

### 1. Prerequisites

Make sure you have Python installed on your system (Python 3.7+ is recommended).

### 2. Install Necessary Libraries

CryptoBuddy relies on the `nltk` and `requests` libraries. You can install them using pip:

```bash
pip install nltk requests

## To test General Conversation and Greetings:

"Hello"
"How are you?"
"What's up?"
"Good morning!" (or "Good evening!", "Good afternoon!", "Good night!" depending on the time)
"My name is John. Hi!"
"Happy birthday!"
"Thank you!"
"Goodbye!"
"What can you do?"
"I have a question."
## To test Fun Phrases:

"Tell me a joke."
"Do you love me?"
"Will you marry me?"
"Do you like people?"
"Does Santa Claus exist?"
"Are you part of the Matrix?"
"You're cute."
"Do you have a hobby?"
"You're smart."
"Tell me about your personality."
## To test Unhappy Phrases/Error Handling:

"This is boring."
"You're bad."
"Are you crazy?"
"I want to speak to a human."
"Don't you speak English?"

## To test Pre-defined Test Questions:

"Are you human?"
"Are you a robot?"
"What is your name?"
"How old are you?"
"What day is it today?"
"What do you do with my data?"
"Do you save what I say?"
"Who made you?"
"Which languages can you speak?"
"What is your mother's name?"
"Where do you live?"
"How many people can you speak to at once?"
"What's the weather like today?"
"Do you have a job for me?"
"Where can I apply?"
"Are you expensive?"
"Who's your boss?"
"Do you get smarter?"
## To test Core Crypto Advice Logic:

"What's the best investment?"
"Which crypto is sustainable?"
"Tell me about rising trend cryptos."
"What is the most sustainable coin?"
"What is Ethereum?"