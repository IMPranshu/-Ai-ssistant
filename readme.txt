pyttsx3 module has to be installed and imported.

sapi5 - https://en.wikipedia.org/wiki/Microsoft_Speech_API
We use it to get voice feedback from the assistant.
There are by default 2 voices installed in the windows Zira & David.
We choose david for our code.

speak() func. is used to give speaking access to the AI.

datetime module has to be imported.

it will give us the time in hours or minutes so that our assistant can greet us 
as the time of the day .

wishMe() func. is used to greet us during the course of the day.

speech_recognition module has to be installed and is imported as sr.

pause_threshold is 1 sec as it is the gap in a sentence between 2 words


takeCommand() func. is just taking audio as input from the microphone and returning 
the command as a string. Also if any problems i.e. expception then it is returning None.


"AttributeError: Could not find PyAudio; check installation"
if this error faced

In Terminal type
pip install pipwin

Then

pipwin install pyaudio


We are using Google engine for speech_recognition here so it will work fine.
Also the quality from mic will differ