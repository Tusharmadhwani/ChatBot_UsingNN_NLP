## Types of Chat Bot's:
In the world of machine learning and AI there are many different kinds of chat bots. Some chat bots are virtual assistants, others are just there to talk to, some are customer support agents and you've probably seen some of the ones used by businesses to answer questions. For this tutorial we will be creating a relatively simple chat bot that will be be used to answer frequently asked questions.

## Install Packages:
Before starting to work on our chatbot we need to download a few python packages. Please note as of writing this these packages will ONLY WORK IN PYTHON 3.6. Hopefully this will be fixed in the future.
We will simply use pip to install the following:
- numpy
- nltk
- tensorflow
- tflearn

Simply go to CMD and type: pip install "package name". Where you will replace "package_name" with all of the entries listed above.

## Training Data
Now it's time to understand what kind of data we will need to provide our chatbot with. Since this is a simple chatbot we don't need to download any massive datasets. We will just use data that we write ourselves. To follow along with the tutorial properly you will need to create a .JSON file that contains the same format as the one seen below. I've called my file "chatbot.json".
