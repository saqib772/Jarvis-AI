# Jarvis-AI

### Alpha Voice Assistant

Alpha( Same as Jarvis) is a simple voice assistant created using Python. It uses OpenAI's natural language processing API, speech recognition library, and text-to-speech engine to answer questions and perform simple actions like opening web pages.

# Installation
To use Alpha, you'll need to install the following libraries:

* openai
* pyttsx3
* speech_recognition
* webbrowser

You can install them using pip:

``` shell
pip install openai pyttsx3 SpeechRecognition
```

# Usage

To use Alpha, you'll need to set up an OpenAI API key. You can sign up for an API key on the OpenAI website.

Once you have your API key, you can set it as an environment variable:
``` shell
export OPENAI_API_KEY=your_api_key_here
```
or You can use: 
```shell 
openai.api_key = "###" 
```

Alpha will listen for your voice commands and respond accordingly.

# Functionality
Currently, Alpha can answer questions using OpenAI's API and perform simple actions like opening web pages. You can ask Alpha things like:

* "What is the weather like today?"
* "Who is the president of France?"
* "What is the capital of Japan?"
* "Open YouTube"
* "Open Google"
Alpha will use OpenAI's API to generate a response to your question and speak it out loud using the text-to-speech engine. If you ask Alpha to open a web page, it will use the webbrowser library to open the page in your default web browser.

### Improvements
While Alpha is a simple voice assistant, there are many ways it could be improved. For example, you could add more functionality like playing music or setting reminders. You could also improve the natural language processing by using a more advanced API like GPT-3. Additionally, you could add more error handling to make Alpha more reliable.

### Credits
Alpha was created by Saqib Iqbal. It uses the following libraries:

* OpenAI API
* pyttsx3
* SpeechRecognition
* webbrowser






