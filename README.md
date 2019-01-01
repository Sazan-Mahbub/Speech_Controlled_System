# Speech_Controlled_System
A hardware project that uses speech recognition to run a prototype of a system. We demonstrated by running a bot using voice command. We use Google-Text-To-Speech API (https://cloud.google.com/text-to-speech/docs/basics) and Google-Speech-To-Text API (https://cloud.google.com/speech-to-text/) here.

The speech-to-text API takes the voice commands and sends them to the google cloud for conversion from speech to text. The the API receives the text, which is used later in the program. For example, to move certain motors in the robots body. 

The text-to-speech API converts the texts into speeches. It is useful when we need to let the user know about the values retrieved using any sensor. It functions similarly as the speech-to-text API.
