# ChatBot

## Abstract
This paper details the process of building a Chatbot using conversational AI. A chatbot is an AI-based software designed to interact with humans in their natural languages. These chatbots are usually converse via auditory or textual methods, and they can effortlessly mimic human languages to communicate with human beings in a human-like manner. A chatbot is arguably one of the best applications of natural language processing.
A Rule-based approach trains a chatbot to answer questions based on a set of pre-determined rules on which it was initially trained. It can be used if our goal is to answer FAQs and or just funnel further questions to human agents. While rule-based chatbots can handle simple queries quite well, they usually fail to process more complicated queries/requests. We are not going to use a Rule-based approach, but instead, we will develop a self-learning bot which leverage advanced technologies like Artificial Intelligence and Machine Learning to train themselves from instances and behaviors. Naturally, these chatbots are much smarter than rule-based bots. 
Advantages of AI Chatbot:
o	Learn from information gathered
o	Continuously improve as more data comes in
o	Understand patterns of behavior
o	Have a broader range of decision-making skills
o	Can understand many languages
o	Are highly accountable and secure
o	Can include interactive elements and media
o	Are not restricted to text interactions


## Method

As we are going to develop a deep learning-based model, we need data to train our model. But we are not going to gather or download any large dataset since this is a simple chatbot. We can just create our own dataset to train the model. To create this dataset, we need to understand what are the intents that we are going to train. An “intent” is the intention of the user interacting with a chatbot or the intention behind each message that the chatbot receives from a particular user. According to the domain that you are developing a chatbot solution, these intents may vary from one chatbot solution to another. Therefore, it is important to understand the right intents for your chatbot with relevance to the domain that you are going to work with.
Then why it needs to define these intents? That’s a very important point to understand. In order to answer questions, search from domain knowledge base and perform various other tasks to continue conversations with the user, your chatbot really needs to understand what the users say or what they intend to do. That’s why your chatbot needs to understand intents behind the user messages (to identify user’s intention).
How can you make your chatbot understand intents in order to make users feel like it knows what they want and provide accurate responses. The strategy here is to define different intents and make training samples for those intents and train your chatbot model with those training sample data as model training data (X) and intents as model training categories (Y).
