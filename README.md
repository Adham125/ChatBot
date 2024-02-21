# ChatBot

This is a terminal chatbot that was developed to help users navigate an online university's website.

## Method

The bot uses keyword search with regular expressions to reply with the appropriate response. Responses are in a tree structure with every line down the tree associated with a set of keywords. If the user inputs a keyword associated with the top of the tree then the bot "restarts" the tree search.

