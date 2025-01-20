# Chatpot

## Description
I have created a small chatbot that talks about plants. It is not refined and requires extensive training. The data used has been extracted from Whatsapp chats and cleaned. The chatbot has been created using Chatterbot and its dependencies. Sqlite3 is used to store the data for the trained chatbot. 

## Files
1. [Main file](./bot.py)
This file contains the source code to create the chatbot. It starts with importing nlkt and the required necessary files. 
2. [Cleaning code](./cleaner.py)
I used a whatsapp exported chat hence I had to clean it to remove unwanted data such as date, name of the sender and receiver and non-message characters.
3. [Whatsapp Chat](./chat.txt)
Raw exported chat to use in the project. 

## Installation 
### Requirements
Python 3.8
Chatterbot ==1.0.4 

### Set up the virtual env. 
$ python -m venv venv
$ source venv/bin/activate
(venv) $ python -m pip install chatterbot==1.0.4 pytz

### Clone 
Git clone https://github.com/CheropS/chatpot

