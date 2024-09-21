# ⚡ COIN DASH 3
 
A simple Streamlit app that shows muti user chatbot using Groq with agents using Fetch.ai.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://coindash3.streamlit.app/)

### How to run it on your own machine

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```
## Coin Dash Functionality

A simple algorothem that highlights price action movement. 

## Arbitwatch Functionality 

Identifiy price difference above a user specified threshold upon multiple exchanges. 

## Multi-user chat bot with an analyst bot and trade agents 

Many users can login and get information and trigger trades

### Groq LLM-based Analyst Bot

Add your groq api-key

### Fetch.AI Agents

Three agents are needed... 
1. Main Agent
2. Get Price Agent
3. Buy Agent
4. Sell Agent

#### Get a Fetch AI Wallet

https://fetch.ai

#### Set up an agent for:

##### Main Agent

- Holds pertinent account information and communicates between buy, sell and get price agents.

##### Get Price

- Get the price of commodity.
- Alert when price is above an user-defined number
- Alert when price is above a user -defined percentage change in the past 24 hours
- Alert when price is different by a user-defined percentage

##### Buy Order

- Connect to exchange
- Place buy order
- Confirm buy order
- Alert confirmation

##### Sell Order

- Connect to exchange
- Place sell order
- Confirm sell order
- Alert confirmation
