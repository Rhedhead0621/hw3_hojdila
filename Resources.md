All example docs and loops
Review 2downloading_files.ipynb

Remember to use "inspect" on the website I am looking at


https://datasciencedojo.com/blog/what-are-chatbots/

https://datasciencedojo.com/blog/building-chatbot-google-dialogflow/

https://landbot.io/academy-episode/create-first-dialogflow-agent

https://stackoverflow.com/questions/48760129/im-scraping-a-faq-pages-and-i-need-to-find-which-tag-has-answers-in-faq-pages

https://www.tidio.com/blog/nlp-chatbots/

https://realpython.com/build-a-chatbot-python-chatterbot/

https://botpress.com/blog/nlp-chatbot#:~:text=How%20is%20an%20NLP%20chatbot,%22rule%2Dbased%22%20bots.


A web page DOM (document object model) can be thought of as a type of family tree. Objects at the same level are *siblings* while from the perspective of a current object, *parents* are higher up in the tree and *children* are further down.


NLTK Library Option
-------------------

https://www.analyticsvidhya.com/blog/2021/07/build-a-simple-chatbot-using-python-and-nltk/

Chatterbot is not working - a lot of known issues

I'm going to try using the nltk library



There are several options for creating chatbots in Python that do not rely on ChatterBot. Here are a few alternatives:

1. **NLTK (Natural Language Toolkit)**: NLTK provides tools for building chatbots, including tokenization, part-of-speech tagging, and parsing. While it doesn't offer pre-trained models like ChatterBot, you can create rule-based or machine learning-based chatbots using NLTK's functionality.

2. **TensorFlow**: TensorFlow is a popular machine learning framework that can be used to build chatbots. You can create sequence-to-sequence models or other types of neural networks to generate responses based on input.

3. **PyTorch**: Similar to TensorFlow, PyTorch is another machine learning library that can be used for building chatbots. It offers flexibility and ease of use for building neural networks.

4. **Rasa**: Rasa is an open-source conversational AI platform that allows you to build chatbots and virtual assistants. It provides tools for natural language understanding, dialogue management, and integrations with messaging platforms.

5. **spaCy**: spaCy is a natural language processing library that can be used for building chatbots. While it doesn't provide chatbot-specific functionality out of the box, it offers powerful tools for text processing and entity recognition, which are essential components of chatbots.

These are just a few alternatives to ChatterBot for building chatbots in Python. Depending on your requirements and expertise, you can choose the one that best fits your needs.



Building an AI-based chatbot:
----------------------------

https://datasciencedojo.com/blog/ai-based-chatbots-in-python/

In this tutorial, we will be using the Chatterbot Python library to build an AI-based Chatbot.

We will be following the steps below to build our chatbot

Importing Dependencies
Instantiating a ChatBot Instance
Training on Chatbot-Corpus Data
Training on Custom Data
Building a front end



Basic rule-based Chatbot:
------------------------

https://datasciencedojo.com/blog/rule-based-chatbot-in-python/

Building a list of keywords
---------------------------- 
Once we have imported our libraries, we’ll need to build up a list of keywords that our chatbot will look for. This list can be as exhaustive as you want. The more keywords you have, the better your chatbot will perform.

As discussed previously, we’ll be using WordNet to build up a dictionary of synonyms to our keywords. For details about how WordNet is structured, visit their website.

Building a dictionary of intents
--------------------------------
Once our keywords list is complete, we need to build up a dictionary that matches our keywords to intents. We also need to reformat the keywords in a special syntax that makes them visible to Regular Expression’s search function.

Defining responses
------------------
The next step is defining responses for each intent type. This part is very straightforward. The responses are described in another dictionary with the intent being the key.

We’ve also added a fallback intent and its response. This is a fail-safe response in case the chatbot is unable to extract any relevant keywords from the user input.

Matching intents and generating responses
-----------------------------------------
Now that we have the back end of the chatbot completed, we’ll move on to taking input from the user and searching the input string for our keywords.

We use the RegEx Search function to search the user input for keywords stored in the value field of the keywords_dict dictionary.  If you recall, the values in the keywords_dict dictionary were formatted with special sequences of meta-characters.

RegEx’s search function uses the sequences to compare the character patterns in the keywords with the input string. If a match is found, the current intent is selected and used as a key to the responses dictionary to select the correct response.


