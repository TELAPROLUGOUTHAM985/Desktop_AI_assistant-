
***************************************************Desktop AI Voice Assistant************************************************************* 
--------Description :
The main aim of a desktop AI assistant is to enhance user productivity and convenience by providing voice-controlled access to information, performing tasks, and automating routine activities on a computer.
Using the speech_recognition module for voice recognition, the pyttsx3 text-to-speech library, and extra modules for different tasks, this Python script functions as a basic voice assistant. The assistant can send emails, tell the time, and retrieve information from Wikipedia, among other things.



Necessary libraries to be installed to develop a desktop ai assistant:
Speech recognition 
Pyttsx3
Wikipedia 
smtplib



The assistant will initialize, greet you according to the time, and wait for your command.

Commands available:

Ask about something on Wikipedia by saying "Wikipedia [your query]."
Get the current time by saying "What's the time?"
Send an email by saying "Email" and providing the content when prompted.
Configuration
Set your email credentials in the sendemail function:

Replace "smtp@gamil.com" with the appropriate SMTP server.
Replace "your email" and "your password" with your email credentials.
Specify the recipient's email address in the to variable within the sendemail function.

Note :
Make sure to run the script in an environment with a working microphone for voice commands.

The assistant uses the Google speech recognition API, so an internet connection is required for voice recognition.
