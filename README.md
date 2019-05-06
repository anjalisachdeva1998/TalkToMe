# TalkToMe
An application made for the people with hearing and speech impairment, written in Python and uses open source Python framework , Kivy for the graphical user interface.

The app currently provides 4 services 
 •	Speech to Text Conversion 
 
 •  Text to Speech Conversion
 
 •  Alarm - produces sound above an amplitude which is audible by the people with hearing impairment
 
 •  Taking Notes (Not developed currently) - To take notes in class


The Speech to Text and Text to Speech conversion uses microsoft speech reocgnition API, google API usage code is also mentioned.
The microsoft API is proven to be faster whereas google API was more accurate for hindi names.

To run the application in android -
1) Install Kivy Launcher on the android phone from google play store
2) In the external storage directory of the phone, make a directory -"Kivy"
3) Store main.py, pictures used and android.txt in kivy folder
4) The android.txt contains -

  title=<Application Title>
  author=<Your Name>
  orientation=<portrait|landscape>

5) Open the kivy launcher and run the app
