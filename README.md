# Study Helper Chatbot powerd by Rasa

## Features

- Responds to greetings and goodbyes
- Provides study tips
- Offers motivational messages
- Suggests taking breaks when needed
- Includes basic small talk from Rasa’s starter model


## Setup Instructions
(Rasa Had issues installing when using Python 3.13.3 so this project uses Python 3.10)

Use    py -3.10 -m pip install rasa    to install the Rasa library

Use   py -3.10 -m rasa train    to train the bot after making edits to files

Use   py -3.10 -m rasa shell    to run the bot and start chatting

All responses and intents are defined in nlu.yml, domain.yml, rules.yml
