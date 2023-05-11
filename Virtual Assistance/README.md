# Desktop Assistant README

This code is a Python-based desktop assistant that recognizes and executes voice commands given by the user. It can perform various tasks like opening webpages, telling the current day and time, and searching for information on Wikipedia.

## Requirements
This code requires the following Python libraries to be installed:
- pyttsx3
- speech_recognition
- webbrowser
- datetime
- wikipedia

The pyttsx3 library is used to convert text to speech, speech_recognition library is used to recognize the voice commands, webbrowser is used to open webpages, datetime is used to get the current time and day, and wikipedia is used to search for information on Wikipedia.

## How to use
To use the desktop assistant, simply run the code and speak a command after the prompt "hello sir I am your desktop assistant. Tell me how may I help you". The assistant will recognize the command and execute it accordingly.

The available commands are:
- "open geeksforgeeks": This command will open the GeeksforGeeks webpage in the default browser.
- "open google": This command will open the Google webpage in the default browser.
- "which day it is": This command will tell the current day of the week.
- "tell me the time": This command will tell the current time.
- "bye": This command will terminate the program.
- "from wikipedia": This command will search for information on Wikipedia. The assistant will ask for the topic to search for after the command is given.
- "tell me your name": This command will tell the name of the desktop assistant, which is "Jarvis".

Note that the assistant is programmed to recognize specific phrases for each command, so it is recommended to use the exact phrases given above for best results.

## Limitations
The assistant has some limitations and can only recognize a limited set of commands. It may also have difficulty recognizing commands if there is background noise or if the user has a heavy accent. Additionally, the assistant requires an internet connection to access the webpages and search for information on Wikipedia.

## Disclaimer
This code is for educational purposes only. The use of the code is at the user's own risk. The author assumes no responsibility for any harm or damage that may occur due to the use of this code.
