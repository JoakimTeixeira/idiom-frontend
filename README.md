# Idiom Frontend
Final Project - Matrix 3rd edition - Frontend

The Matrix 3.0 Project proposes to teach the English language.

## Interface - Front-end
Below are the interfaces from which the user can use to learn english. The system is based on flashcards (Space Repetition System), with audio and text support. 

### Login / Signup

In this interface, the user have 2 options: login or signup. This system uses token authentication with OAuth, to connect with a server written in Java.
![image](https://user-images.githubusercontent.com/12193814/84189364-8ce10080-aa6b-11ea-8c97-8db4e099cd99.png)


### Audio List

Here, the user have the list of audios that he's learning.

![image](https://user-images.githubusercontent.com/12193814/84193006-3080df80-aa71-11ea-89ce-d38dd712f164.png)

Features: 

* English Title
* Portuguese Title
* Action: acess audio

### Main Learning Hall

After selection the phrase from the list, the user can interact with it. 

![image](https://user-images.githubusercontent.com/12193814/84192876-ff081400-aa70-11ea-9af4-0beea01a94ec.png)

Features:

1. Go back to audio list
2. Listen to audio
3. Add bookmark, Advance 3 seconds in audio, Go back 3 seconds in audio
4. Audio speed
    * Decrease audio speed
    * Current audio speed
    * Increase audio speed
5. Show/hide keyboard shortcuts
6. Show/hide bookmark list
7. Bookmark List 
    * Bookmark start
    * Bookmark end
    * Actions: play audio or delete bookmark
8. Audio subtitles
    * Show/hide portuguese text
    * Show/hide English text
    * Show/hide all text 

## Server - Back-end

You can check out the server development in this repostory: [Idiom Backend](https://github.com/UnicariocaDev/IdiomaBackend)
