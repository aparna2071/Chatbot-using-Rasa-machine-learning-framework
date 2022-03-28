# Chatbot-using-Rasa-machine-learning-framework

### PREREQUISITES
The prerequisites for developing and understanding a chatbot using Microsoft Azure are:
•	Python installed
•	Microsoft Build tools with visual c++ 14.0 installed. 
Link: https://visualstudio.microsoft.com/downloads/

I have made this project using Anaconda and Visual C++ 

### INSTALLATION OF RASA X
1.	Make a folder where chatbot will be saved.
2.	Open Anaconda Prompt
3.	Enter cd <path where chatbot will be saved>
 For example:  cd C:\Users\aparn\OneDrive\Documents\Project\Careerbot
4.	Enter conda create --name <name of environment that you want>python==<version>
For example: conda create --name rasa python==3.7.6
 After entering this command, it will install some packages and everywhere give a yes or y.
5.	Now enter:     conda activate<name of environment that was kept in step 4 >
This command will activate the environment of project
6.	Now:   conda install ujson
ujson module allows to convert between Python objects and the JSON data format.
7.	Then,    conda install tensorflow
It will install Tensorflow 
8.	Now install rasa x using following command:


pip install rasa-x –extra-index-url https://pypi.rasa.com/simple
9.	Now install spacy. spaCy is a free open-source library for Natural Language Processing in Python. 

pip install spacy

10.	 Enter the command for rasa init

The rasa init command creates all the files that a Rasa project needs and trains a simple bot on some sample data.
rasa init
Till now an initial model has been trained and necessary files are made by following these steps.. Now talk to the initial bot and after that write /stop to stop the server
  
### Implementation and full project report:
  [chatbotAreport.pdf](https://github.com/aparna2071/Chatbot-using-Rasa-machine-learning-framework/files/8366409/chatbotAreport.pdf)
