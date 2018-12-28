
# SIMPE MUSIC PLAYER (Mobile Android App)
## 1. Introduction :
Today, the mobile applications development has became more and more popular. especially on the Android mobile platform. Everyone can develop their own applications for specific purposes without copyright obstacles.
To summarize the knowledge of subject “Introduction to mobile application”, my team has built a simple application on Android. It is a simple music player.

## 2. Application Goal : 
- Successfully built offline music player with basic function.	
- Simple interface, easy to use.

## 3.  Function Requirement:
- Play offline music.
- Search the songs (with name of song, artist … )
- Make playlists. (add, remove …)
- Setting : Customize interface, properties.

## 4. Function Analysis :
- Songs manager: 
	+ Database of songs : Fully information (name, artist … )
	+ Sort method : By song’s name, by artist … (ascending/descending)
	+ Search method : Find the song form database.
	+ Change song’s information
	+ Add/Delete in the Music player.
- Playlist : 
	+ Make the playlist : make playlist with a music a folder … 
	+ Adjust the playlist : Add (a song, a music folder into playlist), remove (remove a song in the playlist – but not delete in the song database)
	+ Remove the playlist: Delete playlist from the Music Player app.
- Setting : 
	Customize something of the interface of the Music Player app.

## 5. Design UI:
### Main display : 
![image](https://user-images.githubusercontent.com/34700445/50510141-26f0fb00-0abb-11e9-87d3-20229166a3b5.png)

RelativeLayout : Include 

+ Toolbar : App Name, Search Button, Sort Button & Setting Button.

+ Item Song Info : Song’s name, Artist

+ Item Music Play : Mix Button, Play/Pause Button, previous/next song Button, Repeat Button, playing Song SeekBar (time)

+ Item Playlist : list of songs (name & artist) 

+ Scrolling :

### Playlist Dialog :
![image](https://user-images.githubusercontent.com/34700445/50510166-3bcd8e80-0abb-11e9-8872-21953f962056.png)
 
### Sort dialog:
![image](https://user-images.githubusercontent.com/34700445/50510178-4425c980-0abb-11e9-9a4e-c2c9f1017dbd.png)
 
### Setting Dialog:
![image](https://user-images.githubusercontent.com/34700445/50510185-4c7e0480-0abb-11e9-8854-5204b6a89b08.png)
 
## 6. Class Analysis :
![image](https://user-images.githubusercontent.com/34700445/50510198-57389980-0abb-11e9-9937-4cc340bc8d15.png)
 
## 7. Summary :
### Result of Project :
- Successful Building a Simple Music Player Application with basic functions : Listen to music (offline), Playlist manage, Setting (customize something in Interface)
- The Application works pretty well. It is easy to use and customize. It also response the app Goal which our team target.
### In future :
- This application has some errors and also lacks of functions, should be repair & develop in the future. 


