# An-AI-Chatbot-in-Python-and-Flask
An AI Chatbot using Python and Flask REST API 

## Requirements (libraries)
1. TensorFlow
1. Flask

## VsCode Instalation
1. Clone the repository-> cd into the cloned repository folder
2. Create a python virtual environment 
```
# macOS/Linux
# You may need to run sudo apt-get install python3-venv first
python3 -m venv .venv

# Windows
# You can also use py -3 -m venv .venv
python -m venv .venv
```
When you create a new virtual environment, a prompt will be displayed to allow you to select it for the workspace.

3. Activate the virtual environment
```
#linux
source ./venv/bin/activate  # sh, bash, or zsh

#windows
.\venv\Scripts\activate
```
4. Run ```pip install --upgrade tensorflow``` to install ```Tensorflow```
5. Run ```pip install -U nltk``` to install ```nltk```
6. Run ```pip install -U Flask``` to install ```flask```
7. To expose your bot via Ngrok, run ```pip install flask-ngrok``` to install ```flask-ngrok``` Then you'll need to configure your ngrok credentials(login: email + password) Then uncomment this line ```run_with_ngrok(app) ``` and comment the last two lines ```if __name__ == "__main__": app.run() ``` Notice that ngrok is not used by default.
8. To access your bot on localhost, go to ```http://127.0.0.1:5000/ ``` If you're on Ngrok your url will be ```some-text.ngrok.io```

### Step-By-Step Explanation and Installation Guide
> https://dev.to/dennismaina/how-to-create-an-ai-chatbot-in-python-and-flask-1c3m
### Execution
To run this Bot, first run the ```train.py``` file to train the model. This will generate a file named ```chatbot_model.h5```<br>
This is the model which will be used by the Flask REST API to easily give feedback without the need to retrain.<br>
After running ```train.py```, next run the ```app.py``` to initialize and start the bot.<br>
To add more terms and vocabulary to the bot, modify the ```intents.json``` file and add your personalized words and retrain the model again.


<!-- Actual text -->
## Find me on
[![Twitter][1.2]][1]  [![LinkedIn][2.2]][2]

<!-- Icons -->

[1.2]: http://i.imgur.com/wWzX9uB.png (Twitter)
[2.2]: https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/linkedin-3-16.png (LinkedIn)

<!-- Links to my social media accounts -->
[1]: https://twitter.com/dennisjmaina
[2]: https://www.linkedin.com/in/dennismaina/
[3]: https://instagram.com/denno.h_

## Having troubles implementing?
 > Reach out to me maina@dentricedev.com 
 I will be happy to assist 
# 
## want something improved or added?
  > Fork the repo @ [GitHub](https://github.com/mainadennis/An-AI-Chatbot-in-Python-and-Flask).
# 
## Regards,
 > [DentriceDev Solutions](https://dentricedev.com).
