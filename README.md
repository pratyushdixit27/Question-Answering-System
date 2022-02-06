# Question-Answering-System


Question-Answering-System (QAS):
Application link: wikianswers.herokuapp.com
A factoid based question answering system



QAS is a system that automatically answer questions posed by humans in natural language query. Natural language (e.g. English) is the common way of sharing knowledge.

Characteristics of the factoid based QAS:
The Question Answering System (QAS):

tries to answer factoid based questions.
provides concise facts about the question. For example, "where is Taj Mahal located?", “Who is the father of nation of India?”.
is a web-based QAS.
answer open-domain fact based questions.
uses wikipedia and google search pages to extract concise answers.
Block diagram of the system:


Setup Instructions

Requirements
Python version : 2.7
Operating System: Windows

Python Packages required

nltk
flask
gunicorn
unidecode
wolframalpha
wikipedia
gevent
flask_bootstrap
flask_appconfig
flask_wtf
wtforms
google

Generate Wolframalpha API Key (You can use our to test things)

Visit the Wolframalpha APIs Console and log in with your Wolframalpha account.

In the API admin page, you will get your API Key.

Open Question-Answering-System/app.py program. Search this sentence in the program. (At line number 28)

app.config['SECRET_KEY']= ## insert your secret key
Now insert your secret key after '=' sign

Example: app.config['SECRET_KEY']= '\\ffedg0890489574'

Save the file.
To Run
Install python 2.7 to your system
Install the packages givn in the requirements.txt file
Open command prompt.
Go to the directory in command prompt.
Type in command prompt:
py -2 app.py
Now run the browser and type localhost:9191/
Input your question. (Make sure, you are connected to Internet)
Wait for the answer
