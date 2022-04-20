# Speech Recognition(sahi12)

Code Explanation:

1)Importing various modules:
a.---> tkinter: Graphical user Interface can be easily be created with the help of tkinter.
b.---> Messagebox: Message boxes are displayed on the tkinter window.
c.---> gtts: This module helps in playing the sound after converting text to speech.
d.--->speech_recognition: The main purpose of speechrecognition is to identify the words spoken.
e.--->os: This module is useful to interact with the operating system
   
2)Initializing main window:
a.--->Tk(): Every component of tkinter applications can easily be accessed with The help of tk.
b.--->title(): It sets the title of the window.
c.--->geometry(): It helps to set the geometry of the window.
d.--->resizable(): It helps to change the size of the tkinter window as per the requirement of a user.
   
3)Backend of speak and recordvoice function:
a.--->Recognizer(): The main purpose of this instance is to recognize the voice.
b.--->Microphone(): It uses the default microphone as the audio source.
c.--->listen(): It listens to the phrase that is spoken and extracts into audio data.
 
4)Rest Code:
a.--->TextToSpeech(): This is the main function for converting text to speech.
b.--->Label(): Display boxes are displayed on the screen where you can place the text.
c.--->Button(): It adds a button on the tkinter window.
d.--->SpeechToText(): This is the main function for converting speech to text.
e.--->mainwindow.mainloop(): It helps in running our program.

